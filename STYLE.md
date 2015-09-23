# SCSS style guidelines
SCSS style guide, based on [Google HTML/CSS style guide](https://google.github.io/styleguide/htmlcssguide.xml).

## CSS guidelines

### ID and class naming
- Use meaningful or generic ID and class names.
- Instead of presentational or cryptic names, always use ID and class names that reflect the purpose of the element in question, or that are otherwise generic.
- Generic names are simply a fallback for elements that have no particular or no meaning different from their siblings. They are typically needed as “helpers.”

```scss
/* Not recommended: meaningless */
#yee-1901 {}

/* Not recommended: presentational */
.button-green {}
.clear {}

```
```scss
/* Recommended: specific */
#gallery {}
#login {}
.video {}

/* Recommended: generic */
.aux {}
.alt {}
```
## SCSS specific guidelines



# Limitations
imports - only in application file
variables
mixins - only in the helpers section - only if input or calculation is necessary, else use extends.
extends - only in the helpers section - create less overhead than mixins.
nesting - absolute max 3 levels. keep it shallow.
Never use &, ever.

# elements
Only HTML elements. Wrap everything into element or element:state.
Always use variables!

a {
  color: black;
}

a:active {

}

a:hover {

}

# components/modules
Wrap everything in classname the same as filename.

.button {

}

.button:active {

}

.button:hover {

}

# general
- always list all things alphabetically


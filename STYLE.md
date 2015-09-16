# Coding style guidelines

Introduction...


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


# Refs and Portals
## What are Refs Why Do We Need them?

In React, "refs" (short for references) provide a way to access and interact directly with DOM elements or React components. Normally, React manages all the DOM updates for you, but there are scenarios where you need to bypass this and directly access a DOM node or React component. Refs give you this ability.


## Refs are useful when you need to:

1. Access DOM nodes directly for operations that cannot be managed by state and props.
2. Interact with third-party libraries that require direct DOM manipulation.
3. Manage focus, text selection, or media playback.
4. Trigger animations or measure the size/position of elements.

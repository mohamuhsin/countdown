# Refs and Portals
## What are Refs Why Do We Need them?

In React, "refs" (short for references) provide a way to access and interact directly with DOM elements or React components. Normally, React manages all the DOM updates for you, but there are scenarios where you need to bypass this and directly access a DOM node or React component. Refs give you this ability.


Refs are useful when you need to:

Access DOM nodes directly for operations that cannot be managed by state and props.
Interact with third-party libraries that require direct DOM manipulation.
Manage focus, text selection, or media playback.
Trigger animations or measure the size/position of elements.

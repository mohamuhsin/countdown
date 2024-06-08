# Refs and Portals
## What are Refs Why Do We Need them?

In React, "refs" (short for references) provide a way to access and interact directly with DOM elements or React components. Normally, React manages all the DOM updates for you, but there are scenarios where you need to bypass this and directly access a DOM node or React component. Refs give you this ability.


## Refs are useful when you need to:

1. Access DOM nodes directly for operations that cannot be managed by state and props.
2. Interact with third-party libraries that require direct DOM manipulation.
3. Manage focus, text selection, or media playback.
4. Trigger animations or measure the size/position of elements.

## Different Ways We Used useRef in this Project

1. We Explored useRef, and we learned how to use useRef to directly access input field values without triggering re-renders.

2. We Explored ref persistence, and we learned how to use refs to manage timers across multiple component instances, avoiding the pitfalls of using variables. This ensures clean, efficient state management for side effects.

3. We Explored forwadedRef, and we learned how to use forwardRef to pass refs between components, enabling direct DOM manipulation and advanced component interactions. 

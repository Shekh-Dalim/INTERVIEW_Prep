🟢 1. What is CSS?
```
Ans: CSS (Cascading Style Sheets) is used to style HTML elements, including layout, colors, fonts, spacing, and positioning on a webpage.
```
🟢 2. What are the types of CSS?
```

Inline CSS: Added directly inside HTML elements using the style attribute.

Internal CSS: Defined inside a <style> tag within the <head>.

External CSS: Linked via a separate .css file using <link>.
```
🟢 3. What is the difference between classes and IDs in CSS?
```

Class (.): Can be used on multiple elements.

ID (#): Should be unique and used only once per page.
```
🟢 4. What is specificity in CSS?
```
Ans: Specificity determines which style rule is applied when multiple rules match an element. Inline > ID > Class > Element.
```
🟢 5. What is the box model in CSS?
```
Ans: The CSS box model includes:

Content

Padding

Border

Margin
```
🟢 6. What is the difference between relative, absolute, fixed, and sticky positioning?
```

Relative: Positioned relative to its normal position.

Absolute: Positioned relative to the nearest positioned ancestor.

Fixed: Positioned relative to the viewport.

Sticky: Switches between relative and fixed depending on scroll position.
```
🟢 7. What is the z-index in CSS?
```
Ans: Controls the stack order of elements. Higher z-index means the element appears on top.
```
🟢 8. What is the difference between visibility: hidden and display: none?
```
visibility: hidden: Element is invisible but still takes up space.

display: none: Element is removed from the document flow.
```
🟢 9. What are pseudo-classes in CSS?
```
Ans: Used to define the special state of an element.
Examples: :hover, :focus, :nth-child(), :first-child
```
🟢 10. What are pseudo-elements?
```
Ans: Used to style parts of elements.

letter
```
🟢 11. How do media queries work in CSS?
```
Ans: Media queries apply styles based on device properties like width, height, or resolution.

css
Copy
Edit

@media (max-width: 768px) {
  body {
    background-color: lightblue;
  }
}
```
🟢 12. What is the difference between em, rem, %, px in CSS?
```

px: Fixed size

%: Relative to parent

em: Relative to the element’s font size

rem: Relative to the root element’s font size
```
🟢 13. What are Flexbox and Grid in CSS?
```
Flexbox: 1D layout (row or column)

Grid: 2D layout (rows and columns)
```
🟢 14. What is the difference between inline, block, and inline-block elements?
```
Block: Starts on a new line and takes full width.

Inline: Does not break line, only takes as much space as needed.

Inline-block: Behaves like inline but allows width/height settings.
```
🟢 15. What are transitions in CSS?
```
Ans: Transitions allow property changes to occur smoothly over a duration.

button {
  transition: background-color 0.3s ease;
}
```
🟢 16. What is the difference between min-width, max-width, and width?
```

width: Sets exact width.

min-width: Minimum possible width.

max-width: Maximum possible width.
```
🟢 17. What are important CSS functions and units?

```

Units: px, em, rem, %, vw, vh, ch

Functions: calc(), var(), clamp()
```
🟢 18. What does !important do in CSS?
```
Ans: Overrides all other declarations, including inline styles, unless another !important rule has higher specificity.
```
🟢 19. How can you center a div?
```
/* Horizontally and vertically centered */
.center {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
```
🟢 20. What is the difference between auto, initial, and inherit in CSS?
```
auto: Default behavior based on the element

initial: Resets to the default value

inherit: Inherits value from parent
```
🟢 21. What are the combinators in CSS?
```
Descendant ( ): .a .b {}

Child (>): .a > .b {}

Adjacent sibling (+): .a + .b {}

General sibling (~): .a ~ .b {}
```
🟢 22. What is a responsive design?
```
Ans: Designing web pages to work well on different screen sizes and devices using media queries, flexible layouts, and images.
```
🟢 23. What is the difference between position: static and relative?
```
static: Default, no positioning.

relative: Element is positioned relative to its normal position.
```
🟢 24. What is the object-fit property used for?
```
Ans: Defines how an <img> or <video> should fit its container.

css
Copy
Edit

img {
  object-fit: cover;
}
```
🟢 25. What is the opacity property in CSS?
```
Ans: Controls the transparency of an element. Ranges from 0 (fully transparent) to 1 (fully opaque).
```
🟢 26. What are custom properties (CSS variables)?
```
:root {
  --main-color: #4CAF50;
}
div {
  color: var(--main-color);
}
```
🟢 27. What is overflow in CSS?
```
Ans: Controls what happens when content overflows an element’s box. Values: visible, hidden, scroll, auto.
```
🟢 28. How can you apply styles to specific elements based on attributes?
```
input[type="text"] {
  border: 1px solid black;
}
```
🟢 29. What is the difference between nth-child() and nth-of-type()?
```

nth-child(n): Selects the nth child regardless of type.

nth-of-type(n): Selects the nth element of a specific type.
```
🟢 30. What tools help you debug CSS?
```

Browser DevTools

CSS Linters

Extensions like CSS Viewer
```
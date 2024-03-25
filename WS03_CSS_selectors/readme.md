# CSS Selectors

CSS selectors are used to select the HTML elements you want to style. There are several types of CSS selectors:

## Simple Selectors

- **Type selectors**: Select elements by their node name. Example: `p { color: red; }`
- **Class selectors**: Select elements by their class attribute. Example: `.my-class { color: red; }`
- **ID selectors**: Select an element by its ID attribute. Example: `#my-id { color: red; }`

## Combinator Selectors

- **Descendant selectors**: Select elements that are descendants of a certain element. Example: `div p { color: red; }`
- **Child selectors**: Select elements that are direct children of a certain element. Example: `div > p { color: red; }`
- **Adjacent sibling selectors**: Select elements that are direct siblings of a certain element. Example: `div + p { color: red; }`
- **General sibling selectors**: Select elements that are siblings of a certain element. Example: `div ~ p { color: red; }`

## Pseudo-Class Selectors

- **Hover**: Select an element when the mouse pointer is over it. Example: `a:hover { color: red; }`
- **Active**: Select an element during an activation event. Example: `a:active { color: red; }`
- **First-child**: Select an element that is the first child of its parent. Example: `p:first-child { color: red; }`

For a more comprehensive list and detailed explanations, refer to the [W3Schools CSS Selectors Reference](https://www.w3schools.com/cssref/css_selectors.php).

You can also try out different CSS selectors using the [W3Schools CSS Selectors Tester](https://www.w3schools.com/cssref/trysel.php).
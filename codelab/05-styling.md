# Styling

## Background

There are two primary ways to style react components

1. Inline styles with the `style` prop
2. Regular CSS with the `className` prop

**About the `style` prop:**

- In HTML you'd pass a string of CSS:

```html
<div style="margin-top: 20px; background-color: blue;"></div>
```

- In React, you'll pass an object of CSS:

```jsx
<div style={{marginTop: 20, backgroundColor: 'blue'}} />
```

**About the `className` prop:**

As we discussed earlier, in HTML, you apply a class name to an element with the
`class` attribute. In JSX, you use the `className` prop.

## Exercise

In this exercise we'll use both methods for styling react components.

We have the following css on the page:

```css
.box {
  border: 1px solid #333;
}
.box--large {
  width: 180px;
  height: 180px;
}
.box--medium {
  width: 120px;
  height: 120px;
}
.box--small {
  width: 60px;
  height: 60px;
}
```

Your job is to apply the right className and style props to the divs below so
the styles applied match the text content.

### Reference
[Kent C. Dodds](https://github.com/kentcdodds)

[⬅️](04-custom-component.md)  [🏠](../README.md)  [➡️](06-event-handlers.md)
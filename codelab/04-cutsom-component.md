# Custom Component

## Background

Components let you split the UI into independent, reusable pieces, and think about each piece in isolation. Conceptually, components are like JavaScript functions. They accept arbitrary inputs (called “props”) and return React elements describing what should appear on the screen.

## Function Components

The simplest way to define a component is to write a JavaScript function:

```jsx
function Message(props) {
  return <h1>{props.title}</h1>;
}
```

## Class Components

You can also use an ES6 class to define a component:

```jsx
class Message extends React.Component {
  render() {
    return <h1>{this.props.title}</h1>;
  }
}
```

## Exercise

Create custom components accepting props using function and class
components.

### Reference

[React docs: Components & props](https://reactjs.org/docs/components-and-props.html)
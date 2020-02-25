# Event handling

## Background

Handling events with React elements is very similar to handling events on DOM elements.
- React events are named using camelCase, rather than lowercase.
- With JSX you pass a function as the event handler, rather than a string.

To handle button onClick in React

```jsx
function handleClick(e) {
    console.log('Button clicked')
}

<button onClick={handleClick}>
  Press Me
</button>
```

You can attach a submit handler to a form element with the `onSubmit` prop. This will be called with the submit event which has a `target`. That `target` is a reference to the `<form>` DOM node which has a reference to the elements of the form which can be used to get the values out of the form!

## Exercise

Print the value from input element in console

There are several ways to get the value of the name input:
- Via their index: `event.target.elements[0]`
- Via the elements object by their name or id attribute: `event.target.elements.usernameInput.value`

### Reference
[Kent C. Dodds](https://github.com/kentcdodds)

[⬅️](05-styling.md)  [🏠](../README.md)  [➡️](07-useState.md)
# Rendering Arrays

## Background

One of the more tricky things with React is the requirement of a `key` prop when
you attempt to render a list of elements.

If we want to render a list like this, then there's no problem:

```jsx
const ui = (
  <ul>
    <li>One</li>
    <li>Two</li>
    <li>Three</li>
  </ul>
)
```

Then that's no problem, but rending an array of elements is very common:

```jsx
const list = ['One', 'Two', 'Three']

const ui = (
  <ul>
    {list.map(listItem => (
      <li>{listItem}</li>
    ))}
  </ul>
)
```

## Exercise

In this exercise, we are going to build small TODO app.

There is state that exists (managed by the browser) in the `<input />` for each of the todo.

### Reference
[Kent C. Dodds](https://github.com/kentcdodds)

[⬅️](07-useState.md)  [🏠](../README.md)  [➡️](09-useEffect.md)

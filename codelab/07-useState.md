# State

## Background

With React, the way you use state is via a special "hook" called `useState`. Hooks are a new addition in React 16.8

Here's a simple example of what that looks like:

```jsx
function Counter() {
  const [count, setCount] = React.useState(0)
  const increment = () => setCount(count + 1)
  return <button onClick={increment}>{count}</button>
}
```

`React.useState` accepts a default initial value and returns an array. Typically
you'll destructure that array to get the state and a state updater function.

## Exercise

In this exercise, we're going to accept two number and display their sum

### Reference
[Kent C. Dodds](https://github.com/kentcdodds)
📜 https://reactjs.org/docs/hooks-state.html
# Using JSX

## Background

JSX is more intuitive than the raw React API and is easier to understand when
reading the code. It's fairly simple HTML-like syntactic sugar on top of the raw
React APIs:

```jsx
const ui = <h1 id="greeting">Hey there</h1>

// ↓ ↓ ↓ ↓ compiles to ↓ ↓ ↓ ↓

const ui = React.createElement('h1', {id: 'greeting', children: 'Hey there'})
```

Because JSX is not actually JavaScript, you have to convert it using something
called a code compiler. Babel is one such tool.

🦉 Protip: If you'd like to see how JSX gets compiled to JavaScript,
[check out the online babel REPL here](https://babeljs.io/repl).

## Exercise

Normally you'll compile all of your code and build-time before you ship your
application to the browser, but because Babel is written in JavaScript we can
actually run it _in_ the browser to compile our code on the fly and that's what
we'll do in this exercise.

### Reference
[Kent C. Dodds](https://github.com/kentcdodds)

[⬅️](02-react-create-element.md)  [🏠](../README.md)  [➡️](04-custom-component.md)
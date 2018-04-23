> Crash Course into Redux

- React is a library for building user interfaces
- React basically gives us details into
    - Composition
    - Unideirectional Dataflow
    - Explicit mutations
    - Just Javascript

- `Composition` deals with how we can compose various blocks of components and we are able to group or compose all these components together

JSX is transpiled into objects by babel so to learn how react works we can use React.createELement to understand the flow

```
React.createElement(
  'html tag',
  'attributes we want to add on the tag',
  'and the children i.e. content'
)
```

```
React.createElement(
  'h1',
  {id : 'header'},
  'Tyler'
)
```
equivalent to `<h1 id="header">Tyler</h1>`
- createElement is going to create an object representation of the dom node(tag)
- the first argument it takes in is the html tag
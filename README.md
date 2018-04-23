>## Crash Course into Redux
This is basically a react practice crash course to unserstand the fundamentals of react and to track my react jouney along the way
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
- React basically keeps a object representation of the actual DOM so that it can keep track of the changes an update only those nodes
- A component is a function or a class which optionally accepts a input and returns a react element

- We can also pass components to `React.createElement(NameComponent)`
- We can basically pass data i.e. props into our components 
`React.createElement(NameComponent,{name:"Claudia"})`
- Instead of using all the createElement objects to create dom nodes we can use JSX ,which stands for Javascript and XML it's an amalgam of the two to give us the best of both worlds.
- Babel helps us a lot to convert JSX into object representaional form .[Try Babel out here](babeljs.io)
- We can use map to loop over the array.
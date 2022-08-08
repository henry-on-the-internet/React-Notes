
## Refs and the DOM
`https://reactjs.org/docs/refs-and-the-dom.html`

### Refs provide a way to access DOM nodes or React elements created in the render method.

#### In the typical React dataflow, props are the only way that parent components interact with their children. To modify a child, you re-render it with new props. However, there are a few cases where you need to imperatively modify a child outside of the typical dataflow. The child to be modified could be an instance of a React component, or it could be a DOM element.
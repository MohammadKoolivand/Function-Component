# Function-Component

## Deffinition
React has ability to operate with reusable components. React component are two types of **Class Component** & **Function Copmonent**. Here we are focusing on Function Components.

## Function Component Sample

```js
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}
```
## Function Components Lifecycle
Lifecycle in react is managed by **`useEffect`** hook. If useEffect doesnt have any dependency, it acts like **ComponentDidMount** ans if it has dependency, it looks like **ComponentDidUpdate**

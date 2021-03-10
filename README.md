# Function-Component

## Deffinition
React has ability to operate with reusable components. React component are two types of **Class Component** & **Function Copmonent**. Here we are focusing on Function Components.

## Creating a Function Component
creating a Function component has some steps to do:
1. every class component must start with an upper case letter.
2. every component must include **`extends React.Component`**. This gets inheritance to the component.
3. components must have **`render()`** method also. This method returns an HTML tag

## Function Component Sample

```js
function Welcome(props) {
  return <h2>This is a function Component</h2>;
}

```
## Function Components Lifecycle

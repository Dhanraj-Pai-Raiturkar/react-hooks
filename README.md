# React Hooks

## What are Hooks?
Hooks are a new addition to react 16.8 which allows us to use react features without having to write a class.
Hooks dont work inside a class.

## Why Hooks?

### Reason set 1
* Since we dont have to use class components we need not worry about how <i>this</i> keyword works in javascript.
* Dont have to bind event handlers in class components.
* Classes dont minify very well and make hot loading unreliable.

### Reason set 2
* No way to reuse stateful component logic.
* Need to use HOC(Higher Order Components) and Render Props pattern to reuse stateful logic which makes code hard to read and follow.
* Need to share stateful logic in a better way.

### Reason set 3
* Create components for complex scenarios such as data fetching and subscribing to events.
* Related code is not organized in one place.
* Ex: Data fetching in componentDidMount and componentDidUpdate.
* Ex: Event listeners in componentDidMount and componentDidUpdate.
* Due to stateful logic cannot break components into smaller ones.

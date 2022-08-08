# dive-into-react

## Author

Jeffrey Smith

### A High Level Overview Of React

1.What is React?

React is a JavaScript library developed by Facebook which, among other things, was used to build Instagram.com. Its aim is to allow developers to easily create fast user interfaces for websites and applications alike. The main concept of React. js is virtual DOM.

2.What is a component?

Components are the building blocks of any React app and a typical React app will have many of these.

3.What is the dataflow of React?

React, a Javascript library, uses unidirectional data flow. The data from the parent is known as props. You can only transfer data from parent to child and not vice versa. This means that the child components cannot update or modify the data on their own, making sure that a clean data flow architecture is followed.

4.How do we make a React element a DOM element?

const element = React.createElement(
  'h1',
  {className: 'greeting'},
  'Hello, world!'
);

1.Call React.createElement() and describe its arguments.
2.Use ReactDOM.render() to render an element to a page.
3.Describe how we can build elements out of other React elements.
4.Add child elements and nested child elements.
5.Pass properties to an element.

5.React is a User Interface ______.

Agnostic user interface library 

Example:

import React from 'react';
import ReactDom from 'react-dom';
import Header from './Header';
import Content from './Content';
import Footer from './Footer';

```function App() (
  <div className="app">
  <Header />
  <Content />
  <Footer />
);

ReactDom.render(
<App />
document.getElementById("root")
);
```

6.Which direction does data flow in React?

In React JS, data flows in one direction, from Parent to Child. This helps components to be simple and predictable.

7.Every component manages its own ____.1.
State

## Reading Sources

[A High Level Overview Of React. You Tube video by Zac Gordon](https://www.youtube.com/watch?v=FRjlF74_EZk),

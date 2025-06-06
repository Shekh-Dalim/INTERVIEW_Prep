1. What is React?
```
React is a JavaScript library for building user interfaces, especially single-page applications. It allows developers to create reusable UI components.
```

2. What are components in React?
```
Components are the building blocks of a React application. They split the UI into independent, reusable pieces. There are two types: Class components and Functional components.
```

3. What is JSX?
```
JSX stands for JavaScript XML. It is a syntax extension for JavaScript, which allows writing HTML-like code inside JavaScript. It is used to describe what the UI should look like.
```

4. What is the virtual DOM?
```
The virtual DOM is a lightweight copy of the real DOM. React uses it to improve performance by minimizing direct DOM manipulation and updating only what’s necessary.
```

5. What is a state in React?
```
State is a built-in object that stores property values that belong to the component. It allows a component to keep track of changing information.
```

6. What are props in React?
```
Props (short for properties) are read-only components used to pass data from one component to another.
```

7. Difference between state and props?
```
State is managed within the component, while props are passed from parent to child. State can be changed, props cannot.
```

8. What is a functional component?
```
A functional component is a plain JavaScript function that takes props as an argument and returns a React element.
```

9. What is a class component?
```
A class component is a React component defined using an ES6 class. It can hold and manage state and lifecycle methods.
```

10. What are hooks in React?
```
Hooks are functions that let you use state and other React features in functional components. Examples include useState, useEffect, useRef, etc.
```

11. What is useState hook?
```
useState is a React hook that lets you add state to functional components.
```

12. What is useEffect hook?
```
useEffect is a hook that lets you perform side effects in function components, like fetching data, DOM updates, etc.
```

13. What is the difference between useEffect and componentDidMount?
```
useEffect can be used for componentDidMount, componentDidUpdate, and componentWillUnmount combined. componentDidMount is only available in class components.
```

14. What is lifting state up in React?
```
Lifting state up means moving the state to a common ancestor of components that need to share it.
```

15. What is conditional rendering in React?
```
Conditional rendering means rendering components or elements based on a certain condition using JavaScript operators like if, ternary, &&.
```

16. What are keys in React and why are they important?
```
Keys help React identify which items have changed, are added, or removed in a list. They should be unique.
```

17. What is context API?
```
The Context API allows you to pass data through the component tree without passing props manually at every level.
```

18. What is prop drilling and how do you avoid it?
```
Prop drilling is the process of passing props down multiple levels. You can avoid it using Context API or state management libraries like Redux.
```

19. What is Redux?
```
Redux is a state management library used to manage and centralize application state. It uses actions, reducers, and a global store.
```

20. What is the difference between Redux and Context API?
```
Context API is simpler and used for light use-cases, while Redux is more powerful and suitable for complex state management.
```

21. What are controlled and uncontrolled components?
```
Controlled components are managed by React state, while uncontrolled components rely on the DOM to manage their state.
```

22. What is React Router?
```
React Router is a standard library for routing in React. It enables navigation between views of various components.
```

23. What is lazy loading in React?
```
Lazy loading means loading components only when they are required. React provides React.lazy and Suspense for this.
```

24. What is a higher-order component (HOC)?
```
An HOC is a function that takes a component and returns a new component with additional features.
```

25. What is memoization in React?
```
Memoization is an optimization technique to cache the result of expensive function calls. React provides React.memo and useMemo hooks.
```

26. What is useCallback hook?
```
useCallback is a hook that returns a memoized version of the callback function that only changes if one of the dependencies changes.

27. What is reconciliation in React?
```
Reconciliation is the process through which React updates the DOM when a component's state or props change.
```

28. How does React handle forms?
```
React handles forms using controlled components by binding input values to the component’s state and updating the state on user input.
```

29. What are portals in React?
```
Portals allow rendering children into a DOM node that exists outside the parent component hierarchy.
```

30. What are error boundaries?
```
Error boundaries are components that catch JavaScript errors in child components and display a fallback UI instead of crashing.
```
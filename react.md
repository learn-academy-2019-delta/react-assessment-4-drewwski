# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1a. Indicate which of the following statements about React are false:

- React is a modern, efficient answer to complex UI applications
 TRUE

- React will only render on the server using Node.js 
  FALSE

- React is a full stack framework for modern web applications
  FALSE

- React is a flexible library that plays the role of V in an MVC framework
 TRUE

- You should always update a component's state directly using this.state
 FALSE

- React is made up of encapsulated components that manage their own state
 TRUE

- React components render HTML
FALSE


1b. Add an interesting true fact about React to the list.

2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer: Smart components keep track of state. Dumb components only know how to work when they are called.

  Researched answer: Smart component keep track of state and concern with how things work. They receive data or functions via props and can pass it to another smart component or dumb component as props. This component only responsible to present something to DOM. There will be no logic at all inside this component therefore it is called dumb component.



3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer: it adds packages and JSON

  Researched answer: Installs a package and any packages that it depends on.



4. How would you explain state to a friend who doesn't know code?

  Your answer: State is the what the object is doing at that specific point in time. If you make any changes then the current state will also change and become a new state.

  Researched answer: The heart of every React component is its “state”, an object that determines how that component renders & behaves. In other words, “state” is what allows you to create components that are dynamic and interactive.



5. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer: Props are passed into the state of the parent to make changes to the state.

  Researched answer: In a React component, props are variables passed to it by its parent component. State on the other hand is still variables, but directly initialized and managed by the component. Any other method in this class can reference the props using this.props.

# Answers

- [ ] What is React JS and what problems does it try and solve? Support your answer with concepts introduced in class and from your personal research on the web.

REACTJS is not only a UI library, but is also a way of building web apps that breaks down the process into components. It allows us to build a component seprerately and re-use it on the webpage at any point without compromising the code. It also uses declarative code which allows us to scale out more easily readable code.

- [ ] What does it mean to _think_ in react?

The nature of React breaking down into components means that we are 'seperating concerns'. For example we are thinking about creating components that do one and only one thing which makes it easier to debug.

- [ ] Describe state.

Mutable data that is held in a components memory. When state updates so too do the components. 

- [ ] Describe props.

Non-mutable data that is held in a components memory, however, it must be passed down from a parents state memory.

- [ ] What are side effects, and how do you sync effects in a React component to state or prop changes?

Side effects are anything that affects something outside the scope of the function being executed. You sync side effects to state or prop changes using the effect hook.
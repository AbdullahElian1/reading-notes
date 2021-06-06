# Component Lifecycle
Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
render

What is the very first thing to happen in the lifecycle of React?

Mounting

Put the following things in the order that they happen: 

1-constructor

2--render
 
3- React Updates
 
4- componentDidMount
  
5- componentWillUnmount.


Avoid using this.setState() in the constructor because it can lead to 

side effects, and it is unnecessary.

# Props VS State
1-What types of things can you pass in the props?

argument like counter , title ,elc.

2-What is the big difference between props and state?

props you pass into the component and state is handle inside of that 

component and props handle outside.

3-When do we re-render our application?

when you change the state inside of your application.

4-What are some examples of things that we could store in state?

like counter and any thing change inside the component.
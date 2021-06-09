#  thinking in React

How would you break a mock into a component heirarchy?
by devide the mock into subcomponents

What is the single responsibility principle and how does it apply to components?

a component should ideally only do one thing.

and how does apply ? divide our work into componentsand subcomponents

What does it mean to build a ‘static’ version of your application?

bulid the UI without interactivity

Once you have a static application, what do you need to add?

make the website interactive by adding state

What are the three questions you can ask to determine if something is state?

1-Is it passed in from a parent via props?

2- Does it remain unchanged over time? 

3-Can you compute it based on any other state or props in your component?

How can you identify where state needs to live?

Identify every component that renders something based on that state.
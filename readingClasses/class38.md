# class 38
### I read about these topics and how they work in react :
- Conditional Rendering

- Lists & Keys

- Forms

- Lifting State

- Composition vs Inheritance

### Thinking in React
- Start With A Mock
- Break The UI Into A Component Hierarchy

The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names.
But how do you know what should be its own component? Use the same techniques for deciding if you should create a new function or object. One such technique is the single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

Since you’re often displaying a JSON data model to a user, you’ll find that if your model was built correctly, your UI (and therefore your component structure) will map nicely. That’s because UI and data models tend to adhere to the same information architecture. Separate your UI into components, where each component matches one piece of your data model.

- Build A Static Version in React
- Identify The Minimal (but complete) Representation Of UI State
- Add Inverse Data Flow

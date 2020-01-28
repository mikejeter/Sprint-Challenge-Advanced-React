- [ ] Why would you use class component over function components (removing hooks from the question)?

Because a functional component is just a plain JavaScript function, you cannot use setState() in your component. That’s the reason why they also get called functional stateless components.

- [ ] Name three lifecycle methods and their purposes.

componentWillMount, is executed just before the React Component is about to mount on the DOM. Hence, after this method the component will mount.
componentDidMount this is the hook method which is executed after the component did mount on the dom.
shouldComponentUpdate tells the React that when the component receives new props or state is being updated, should React re-render or it.

- [ ] What is the purpose of a custom hook?

A custom Hook is a JavaScript function whose name starts with ”use” and that may call other Hooks. For example, useLocalStorage.

- [ ] Why is it important to test our apps?

Automated testing minimizes the risk of bugs finding their way into production code. Testing is NOT optional, it should be a part of every developer’s workflow. The feature is not done until it’s fully tested.
# Redux Advanced

# Redux - Combined Reducers

## Review, Research, and Discussion

1. Why choose Redux instead of the Context API for global state?

   - The ability to add in middleware and because, the `Context API` (currently) is not built for high-frequency updates.

2. What is the purpose of a reducer?

   - To define case to dispatch action to and make a default case whenever a something bad happens.

3. What does an action contain?

   - I contains the logic used to change the value of states.

4. Why do we need to copy the state in a reducer?
   - To keep the reducers as pure functions that does not change variables (states) directly.

5. What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

   - I would say to load data using `redux-thunk` middleware, after all related component are mounted (componentDisMount) state, fire an action that utilize `redux-thunk`.

6. When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
   - We export the action only, as `thunk` is a middleware that will fire before each firing of the reducer it's attached to.
---

## Terms

- immutable state

  > A state that can not be modified after initialization.

- time travel in redux

  > The ability step forward and backward through the state of you application, empowering the developer understand exactly what is happening at any point in the app’s lifecycle.

- action creator

  > a function that returns an action object. Redux includes a utility function called bindActionCreators for binding one or more action creators to the store’s dispatch() function.

- reducer

  > a pure function that takes an action and the previous state of the application and returns the new state

- dispatch

  > a function of the Redux store. You call store. dispatch to dispatch an action. This is the only way to trigger a state change.

- middleware:

  > Middleware is software that enables one or more kinds of communication or connectivity between two or more applications or application components in a distributed network. Redux middleware provides a third-party extension point between dispatching an action, and the moment it reaches the reducer. This is to modify the behavior of the dispatch action

- thunk:

  > A Middleware for `redux`. `Thunks` are the recommended middleware for basic Redux side effects logic, including complex synchronous logic that needs access to the store, and simple async logic like AJAX requests.



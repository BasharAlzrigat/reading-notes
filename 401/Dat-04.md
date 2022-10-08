# Advanced State with Reducers

## How can we ensure that an effect hook runs only once?
To run the useEffect hook callback only once when the component mounts, we just have to pass in an empty array into the 2nd argument of useEffect hook.

## Can useState() update more than one state variable at the same time?
No, you can't you need to call multiple useState to update multiple states at the same time.

## Is useState() synchronous?
useState is an asynchronous hook and it doesn't change the state immediately, it has to wait for the component to re-render. 

term | definition 
--------| --------
State Hook| useState is a Hook (function) that allows you to have state variables in functional components.
Component Lifecycle| Each component in React has a lifecycle which you can monitor and manipulate during its three main phases. The three phases are: Mounting, Updating, and Unmounting.


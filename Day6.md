1.What is an event in react?

=>An event is an action that could be triggered as a result of the user action or system generated event. For example, a mouse click, loading of a web page, pressing a key, window resizes, and other interactions are called event. React has its own event handling system which is very similar to handling events on DOM elements. The react event handling system is known as Synthetic Events. The synthetic event is a cross-browser wrapper of the browser's native event.


===========================================================================================================

2.What is memory leak and how to overcome?

=>Memory leak occurs when programmers create a memory in heap and forget to delete it. The consequences of memory leak is that it reduces the performance of the computer by reducing the amount of available memory. Eventually, in the worst case, too much of the available memory may become allocated and all or part of the system or device stops working correctly, the application fails, or the system slows down vastly . Memory leaks are particularly serious issues for programs like daemons and servers which by definition never terminate.

===========================================================================================================

Do you prefer function-based or class component and why ?
=>Functional Component. A functional component is just a plain JavaScript pure function that accepts props as an argument and returns a React element(JSX). A class component requires you to extend from React. Component and create a render function which returns a React element. There is no render method used in functional components.


=============================================================================================================

4.Explain reducer as pure function in redux?

=>In Redux, a reducer is a pure function that takes an action and the previous state of the application and returns the new state. The action describes what happened and it is the reducer's job to return the new state based on that action. (previousState, action) => newState Pure functions can't do any of the following:

Access global variables
Change global variables
Mutate its arguments
Perform side effects (like make API calls)
Call any other impure function (like date and random functions)



==============================================================================================================
5.Why do we use redux thunk?

=>The most common use case for Redux Thunk is for communicating asynchronously with an external API to retrieve or save data. Redux Thunk makes it easy to dispatch actions that follow the lifecycle of a request to an external API. Redux Thunk is middleware that allows you to return functions, rather than just actions, within Redux. This allows for delayed actions, including working with promises. One of the main use cases for this middleware is for handling actions that might not be synchronous, for example, using axios to send a GET request.



================================================================================================================

6.What do you know about NPM?

=>NPM stands for 'Node Package Manager',npm is the world's largest software registry. Open source developers from every continent use npm to share and borrow packages, and many organizations use npm to manage private development as well.

npm consists of three distinct components: *the website *the Command Line Interface (CLI) *the registry
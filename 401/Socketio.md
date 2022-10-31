# Socket.io

`Socket.IO` is a library that enables real-time, bidirectional and event-based communication between the browser and the server. It consists of:  
- a `Node.js` server
- a `Javascript` client library for the browser (which can be also run from Node.js)    

### How `Socket.IO` Works: 
The socket() API creates an endpoint for communications and returns a socket descriptor that represents the endpoint. When an application has a socket descriptor, it can bind a unique name to the socket. Servers must bind a name to be accessible from the network.

### `Socket.IO` Features:  
- reliability (fallback to HTTP long-polling in case the WebSocket connection cannot be established)
- automatic reconnection
- packet buffering
- acknowledgments
- broadcasting to all clients or to a subset of clients (what we call “Room”)
- multiplexing (what we call “Namespace”)  
### Compatibility
`Socket.IO` is implemented in many languages like:  
- java
- C++
- Swift
- Dart
- Python
- .Net
- Golang
- Rust 

### Socket.io keywords with definition:
Term | Definition
--- | ---
Observer Pattern | The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.  
Listener | waiting on something to happen (a press of a mouse or a link to be pressed) to trigger a course of actions.  
Event | An action that will cause a function to start if it was listened on.  
Event Driven Programming | event-driven programming is when a program is designed to respond to user engagement in various forms. It is known as a programming paradigm in which the flow of program execution is determined by “events.” Events are any user interaction, such as a click or key press, in response to prompt from the system.  
Event Loop | The Event Loop has one simple job — to monitor the Call Stack and the Callback Queue. If the Call Stack is empty, the Event Loop will take the first event from the queue and will push it to the Call Stack, which effectively runs it. Such an iteration is called a tick in the Event Loop.
Event Queue | An event queue is a repository where events from an application are held prior to being processed by a receiving program or system. Event queues are often used in the context of an enterprise messaging system
Call Stack | call stack is a stack data structure that stores information about the active subroutines of a computer program
Emit/Raise/Trigger | The trigger() method triggers the specified event and the default behavior of an event (like form submission) for the selected elements. The emit method (the publish method), allows you to "emit" an event, which causes all callbacks registered to the event to 'fire', (get called). Short: Emit's job is to trigger named event(s) which in turn cause functions called listeners to be called. Raise (I think it's related to throwing errors)  
Subscribe | This is a JavaScript object that defines the handlers for the notifications you receive. The subscribe() call returns a Subscription object that has an unsubscribe() method, which you call to stop receiving notifications.
database | A database is a data structure that stores organized information like SQL and noSQL

### 
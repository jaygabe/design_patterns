# Observer

## The Observer, The Subjects, and Surveillance

### Type: Behavioral

> In software design and engineering, the **observer pattern**
> is a software design pattern in which an object, named the > **subject**, maintains a list of its dependents, called
> **observers**, and notifies them automatically of any state > changes, usually by calling one of their methods.

> It is often used for implementing distributed event-handling
> systems in event-driven software.

### Problems Solved by the Observer:

1. A one-to-many dependency between objects should be defined without making the objects tightly coupled
2. When one object changes state, an open-ended number of dependent objects should be updated automatically
3. An object can notify multiple other objects

## Solution

- Define `Subject` and `Observer` objects
- When a subject changes state, all registered observers are notified and updated automatically (and probably asynchronously)

![Class diagram of observer pattern in action](/images/observer.png 'The Observer Pattern')

![Observer pseudocode](/images/observer_pseudocode.png 'The Observer Pattern Pseudocode')

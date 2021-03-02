# The-Object-Oriented-Thought-Process-5th-Edition

---

### `1. Introduction to Object-Oriented Concepts`

Historically, object-oriented languages are defined by concepts like:

Encapsulation

Inheritance

Polymorphism

Composition

##### Object Wrappers

Object wrappers are object-oriented code that includes other code inside. For example, you can take structured code (such as loops and conditions) and wrap it inside an object to make it look like an object. You can also use object wrappers to wrap functionality such as security features, nonportable hardware features, and so on.

#### PROCEDURAL VERSUS OO PROGRAMMING

In OO design, the attributes and behaviors are contained within a single object, whereas in procedural, or structured, design the attributes and behaviors are normally separated.

In structured programming the data is often separated from the procedures, and often the data is global, so it is easy to modify data that is outside the scope of your code. This means that access to data is uncontrolled and unpredictable (that is, multiple functions may have access to the global data). Second, because you have no control over who has access to the data, testing and debugging are much more difficult. Objects address these problems by combining data and behavior into a nice, complete package.

##### Data Hiding

In OO terminology, data are referred to as attributes, and behaviors are referred to as methods. Restricting access to certain attributes and/or methods is called data hiding.

##### Procedural Programming

Procedural programming normally separates the data of a system from the operations that manipulate the data. For example, if you want to send information across a network, only the relevant data is sent (see Figure 1.4), with the expectation that the program at the other end of the network pipe knows what to do with it. In other words, some sort of handshaking agreement must be in place between the client and the server to transmit the data. In this model, it is quite possible that no code is actually sent over the wire.

##### OO Programming

The fundamental advantage of OO programming is that the data and the operations that manipulate the data (the code) are both encapsulated in the object. For example, when an object is transported across a network, the entire object, including the data and behavior, goes with it.

```
Proper Design

A good example of this concept is an object that is loaded by a browser. Often, the browser has no idea of what the object will do ahead of time because the code is not there previously. When the object is loaded, the browser executes the code within the object and uses the data contained within the objec
```

#### WHAT EXACTLY IS AN OBJECT?

Objects are the building blocks of an OO program. A program that uses OO technology is basically a collection of objects. To illustrate, let’s consider that a corporate system contains objects that represent employees of that company. Each of these objects is made up of the data and behavior described in the following sections.

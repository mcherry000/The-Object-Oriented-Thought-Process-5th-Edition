# The-Object-Oriented-Thought-Process-5th-Edition

---

### `1. Introduction to Object-Oriented Concepts`

Historically, object-oriented languages are defined by concepts like:

Encapsulation

Inheritance

Polymorphism

Composition

##### Object Wrappers

```
Object wrappers are object-oriented code that includes other code inside.
For example, you can take structured code (such as loops and conditions)
and wrap it inside an object to make it look like an object. You can also
use object wrappersto wrap functionality such as security features,
nonportable hardware features, and so on.
```

##### PROCEDURAL VERSUS OO PROGRAMMING

- In structured programming the data is often separated from the procedures,
  and often the data is global, so it is easy to modify data that is outside the scope of your code. Access to data is uncontrolled and unpredictable.
- Testing and debugging are much more difficult because you have no control over who has access to the data.
- In OO design, Objects address these problems by combining data and behavior within a single object.

##### Procedural Programming

Procedural programming normally separates the data of a system from the operations that manipulate the data. For example, if you want to send information across a network, only the relevant data is sent (see Figure 1.4), with the expectation that the program at the other end of the network pipe knows what to do with it. In other words, some sort of handshaking agreement must be in place between the client and the server to transmit the data. In this model, it is quite possible that no code is actually sent over the wire.

##### OO Programming

The fundamental advantage of OO programming is that the data and the operations that manipulate the data (the code) are both encapsulated in the object. For example, when an object is transported across a network, the entire object, including the data and behavior, goes with it.

```
Proper Design

A good example of this concept is an object that is loaded by a browser. Often, the browser has no idea of what the object will do ahead of time because the code is not there previously. When the object is loaded, the browser executes the code within the object and uses the data contained within the objec
```

##### WHAT EXACTLY IS AN OBJECT?

Objects are the building blocks of an OO program. A program that uses OO technology is basically a collection of objects. Advantage of using objects is that the data is part of the package—it is not separated from the code.

##### WHAT EXACTLY IS A CLASS?

- A class is a blueprint for an object. When you instantiate an object, you use a class as the basis for how the object is built.
- Classes can be thought of as the templates, or cookie cutters, for objects.
- A class can be thought of as a sort of higher-level data type.
- Classes are pieces of code and objects instantiated from classes can be distributed individually or as part of a library.

In short, you must design a class before you can create an object.

##### ENCAPSULATION AND DATA HIDING

One of the primary advantages of using objects is that the object need not reveal all its attributes and behaviors.

`Data hiding is a major part of encapsulation.`

For data hiding to work properly, all attributes should be declared as private. Thus, attributes are never part of the interface. Only the public methods are part of the class interface. Declaring an attribute as public breaks the concept of data hiding.

##### Data Hiding

In OO terminology, restricting access to certain attributes and/or methods is called data hiding.

```
Getters and Setters

The concept of getters and setters supports the concept of data hiding.
Because other objects should not directly manipulate data within another
object, the getters and setters provide controlled access to an object's
data. Getters and setters are sometimes called accessor methods and
mutator methods, respectively.
```

---

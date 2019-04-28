---
layout: essay
type: essay
title: The Organized Chaos That Is Code
# All dates must be YYYY-MM-DD format!
date: 2019-04-27
labels:
  - Design Patterns
  - Template
  - Problem-Solving
---

In software engineering, there are so many, many, MANY ways to approach a problem. However, some approaches work better for some problems and not as well for others. These techniques can be sorted into categories of design patterns, conceptual outlines used to plan the development of programs. [Design Patterns: Elements of Reusable Object-Oriented Software](https://en.wikipedia.org/wiki/Design_Patterns) is a book written by the Gang of Four, a group of four prolific computer scientists who documented the advantages of using design patterns when writing code. In it they describe, three main categories of design patterns.

## Creational

Creational patterns are based on the instantiation of objects by creating a blueprint for future objects to be based on. One of the Creational Design Patterns is the Abstract Factory method, where an abstract class can be used for its children to derive their data types from but the class itself is not initialized. For example, say you wanted to model Pokemon as objects. Instead of creating a new Pokemon object every time, declaring its values, and generally wasting time, it would be in your best interest to create an abstract Pokemon object, which can be used to create instantiable Pokemon subclasses. 

## Structural

Structural patterns focus on creating individual components and putting them together to form a new and more robust system. One of the Structural Design Patterns is the Composite method, where a program’s individual parts are modeled with subcomponents, which can also be modeled by their own subcomponents, all the way to their basic structures. Let’s say that you’re creating a website to manage clubs at a university to allow students to search and favorite specific clubs. There are many pieces to this website but the layout can be easily put together using the Composition method. Creating the homepage, creating the search page, establishing a database for all the clubs, allow the user to sign in/out, allow new users to join up, the list can go on but it’s made much more organized using this method.

## Behavioral

Behavioral patterns’ main concern is how classes communicate and interact with each other. One of the Behavioral Design Patterns is the Iterator method, where a class exposes information in a list/array without exposing its entire structure. As an example, at the time of writing this, I am working on modifying an API for a hybrid reality environment where the input and location information of the controllers and head tracker must be accessible by the user when they create their own applications. Information between the input class can be accessed by public methods but all the raw information is not available to the developer. This is for simplicity’s sake and to ensure that the developer can only do as much as we intend them to. 

## In conclusion...

Design patterns help us to create programs with formalized outlines and allow other developers to easily comprehend what you are creating. Don’t believe me? All three of the examples listed above are from projects that I contributed to but I didn’t have names for those approaches. They work and if you're a developer, you're probably using these methods as well. 

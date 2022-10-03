---
title: Design Patterns
description: Descriptional approach
author: Pratik Kabade
layout: post
icon: fa-pencil
image: "https://repository-images.githubusercontent.com/520895353/e86175bf-8f29-4631-b69d-0766ecd701a9"
---

Design Pattern provides a template or descriptional approach on how to solve a problem arising in multiple situations. Design Patterns however are general solution providers or they can be termed as flexible solution makers for commonly arising design pattern problems


# Design Patterns

## Content 

1. [Design Patterns](#design-pattern)

2. [Patterns Intro](#patterns-intro)

### [1. Creational Patterns](#1-creational-patterns-1)

1. Abstract Factory

2. Builder

3. Factory Method

4. Prototype

5. Singleton


### [2. Structural Patterns](#2-structural-patterns-1)

1. Adapter

2. Bridge

3. Composite

4. Decorator

5. Facade

6. Flyweight

7. Proxy


### [3. Behavioral Patterns](#3-behavioral-patterns-1)

1. Chain of Resp.

2. Command

3. Interpreter

4. Iterator

5. Mediator

6. Memento

7. Observer

8. State

9. Strategy

10. Template Method

11. Visitor

### [Example](#example-1)
 
### [References](#references-1)

## Design Pattern

Design Pattern provides a `template` or `descriptional approach` on how to solve a problem arising in **multiple situations**

Design Patterns however are general solution providers or they can be termed as **flexible solution makers** for commonly arising design pattern problems

To be specific about patterns, the choice of opting for a certain pattern in C# is not confined to solving only a *single problem*. Patterns are so efficient that they can solve millions of problems with just a *few lines of code*.

There are although plenty of design patterns in C# approximately `23` which are also known as **Gang of Four**. 



### Patterns Intro

To give you a head start, the C# source code for each pattern is provided in 2 forms: structural and real-world. Structural code uses type names as defined in the pattern definition and UML diagrams. Real-world code provides real-world programming situations where you may use these patterns.

A third form, .NET optimized, demonstrates design patterns that fully exploit built-in .NET features, such as, generics, delegates, reflection, and more. These and much more are available in our Dofactory .NET product. See the Singleton page for a .NET Optimized example.


## 1. Creational Patterns

**Creational Design Patterns** offer an effective and dynamically powered mechanism that channels the `proximity of code reusability` and enhances `flexibility` so that problems can be solved in a `wider arena`. The wider the arena the more visible it is to find it and solve it. Creational Design Patterns involve various sub-categories that have been interestingly discussed below.

##### 1. Abstract Factory

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp3.png)

    Creates an instance of several families of classes

Abstract factory pattern let us produce families of multiple related objects `without specifying which classes they belong` to. 

They remain totally under the hood.


##### 2. Builder

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp4.png)

    Separates object construction from its representation

Builder pattern will let us produce families of multiple related objects `without specifying which classes they belong` to. 

They remain totally under the hood.


##### 3. Factory Method

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp2.png)

    Creates an instance of several derived classes

**Factory Method** is mainly used to provide creational objects in the `sub-class` and these sub-classes `are allowed to alter the type of the objects` that would be created.


##### 4. Prototype

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp5.png)

    A fully initialized instance to be copied or cloned

Prototype design pattern will let us `copy` the existing objects while implementing them without having to be dependent completely on the classes defined.


##### 5. Singleton

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp   .png)

    A class of which only a single instance can exist

As the name suggests, this pattern ensures that a class should have only one instance with the condition of providing a global access point to the instance.


## 2. Structural Patterns

Structural Design Patterns offer the flexibility of constructing objects and classes in a large structure so that they can be deal with `larger problems` arising at a `certain instance`. This design pattern ensures that all the objects and classes are `assembled` to form a `large structure` **without hampering** the `efficiency` and keeping the `flexibility` on point. It consists of various sub-categories as shown below.


##### 1. Adapter

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp7.png)

    Match interfaces of different classes

This allows `collaboration with all the interfaces` that are found incompatible with the solution-based approach.


##### 2. Bridge

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp8.png)

    Separates an object’s interface from its implementation

It allows to `split a large class` or `set into several small fragments` or closely related classes based on the `hierarchies`. It can be called an `abstractional implementation` where these small classes are rationally and independently dealt with.


##### 3. Composite

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp9.png)

    A tree structure of simple and composite objects

##### 4. Decorator

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp10.png)

    Add responsibilities to objects dynamically

The decorator enables to attach various `new behaviors` to the objects. It does so by covering up these objects in `special wrapper objects` followed by the behavior contained in them.


##### 5. Facade

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp11.png)

    A single class that represents an entire subsystem

The facade offers a `simple interface` and `exposure to the library` or a framework by managing to portray the effective solutions with the `enhancement` in the interface no matter what framework we are using.


##### 6. Flyweight

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp12.png)

    A fine-grained instance used for efficient sharing

Flyweight allows us to `fit more objects` into the `RAM`. This is done by sharing a common part of the state that is found between `multiple objects` *rather than having* to have to store all the `data for each object`.


##### 7. Proxy

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp13.png)

    An object representing another object

It provides a different way or a substitute for another object. It offers a placeholder for the proxy that controls the access of the original objects. The requests are therefore processed either before or after the original object gets allowed.


## 3. Behavioral Patterns

Behavioral Design Patterns are strictly confined to `strategic` or `algorithmic approaches`. This pattern is mainly concerned with the approach of `sharing` or `putting responsibilities` between `different objects`.


##### 1. Chain of Resp.

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp14.png)

    A way of passing a request between a chain of objects

It passes the requests to the chain of handlers. When the request is received by these `handlers` in any event, these handlers decide whether they `should be passed to the request to another handler` in the chain or process the currently received request.

##### 2. Command

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp15.png)

    Encapsulate a command request as an object

It turns the `requests` into `standalone objects` and these objects contain all the data of the request being taken into consideration. Later this request is passed as a method argument for processing and supporting operations which are `undoable or queued`.


##### 3. `Interpreter`

    Encapsulate a command request as an object

##### 4. Iterator

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp16.png)

    Encapsulate a command request as an object

This will let you iterate over the collection or `list of problematic patterns` without having to expose the underlying representation.

##### 5. Mediator

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp17.png)

    Encapsulate a command request as an object

It simply reduces the dependencies causing chaos by stopping direct communication between the objects and in turn forces them to collaborate via a mediator object.


##### 6. Memento

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp18.png)

    Capture and restore an object's internal state

It simply `hides` the `implementation details` of the object and maintains the actions like saving and restoring the previous state.


##### 7. Observer

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp19.png)

    A way of notifying change to a number of classes

It helps to `define a mechanism` for a `subscription` that eventually notifies the objects about any events that may occur when they are out on the observation.


##### 8. State

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp20.png)

    Alter an object's behavior when its state changes

It allows to `change the whole state` of the object there exist some `internal changes` in the state. It might appear like an object that has changed its class.


##### 9. Strategy

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp21.png)

    Encapsulates an algorithm inside a class

It allows us to `interchange the objects` by putting them into `different classes` through a native family of algorithms.


##### 10. Template Method

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp22.png)

    Defer the exact steps of an algorithm to a subclass

It enables `overriding` of the `subclass` over some predefined phases of an algorithm without having to alter the `superclass` defying the skeleton of the proposed algorithm.


##### 11. Visitor

![image](https://static.javatpoint.com/csharp/images/design-patterns-c-sharp23.png)

    Defines a new operation to a class without change

It simply separates the objects which operate on the algorithm assigned to it.


## Example


### `Structural code` in C#

This structural code demonstrates the Abstract Factory pattern creating parallel hierarchies of objects. 

Object creation has been abstracted and there is no need for hard-coded class names in the client code.


##### MainApp startup class for Structural
##### Abstract Factory Design Pattern
```csharp
class MainApp
{
    /// <summary>
    /// Entry point into console application.
    /// </summary>

    public static void Main()
    {
        // Abstract factory #1

        AbstractFactory factory1 = new ConcreteFactory1();
        Client client1 = new Client(factory1);
        client1.Run();

        // Abstract factory #2

        AbstractFactory factory2 = new ConcreteFactory2();
        Client client2 = new Client(factory2);
        client2.Run();

        // Wait for user input

        Console.ReadKey();
    }
}
```


##### The `AbstractFactory` abstract class
```csharp
abstract class AbstractFactory
{
    public abstract AbstractProductA CreateProductA();
    public abstract AbstractProductB CreateProductB();
}
```


##### The `ConcreteFactory1` class
```csharp
class ConcreteFactory1 : AbstractFactory
{
    public override AbstractProductA CreateProductA()
    {
        return new ProductA1();
    }
    public override AbstractProductB CreateProductB()
    {
        return new ProductB1();
    }
}
```


##### The `ConcreteFactory2` class
```csharp
class ConcreteFactory2 : AbstractFactory
{
    public override AbstractProductA CreateProductA()
    {
        return new ProductA2();
    }
    public override AbstractProductB CreateProductB()
    {
        return new ProductB2();
    }
}
```


##### The `AbstractProductA` abstract class
```csharp
abstract class AbstractProductA
{
}
```


##### The `AbstractProductB` abstract class
```csharp
abstract class AbstractProductB
{
    public abstract void Interact(AbstractProductA a);
}
```


##### The `ProductA1` class
```csharp
class ProductA1 : AbstractProductA
{
}
```


##### The `ProductB1` class
```csharp
class ProductB1 : AbstractProductB
{
    public override void Interact(AbstractProductA a)
    {
        Console.WriteLine(this.GetType().Name +
            " interacts with " + a.GetType().Name);
    }
}
```


##### The `ProductA2` class
```csharp
class ProductA2 : AbstractProductA
{
}
```


##### The `ProductB2` class
```csharp
class ProductB2 : AbstractProductB
{
    public override void Interact(AbstractProductA a)
    {
        Console.WriteLine(this.GetType().Name +
            " interacts with " + a.GetType().Name);
    }
}
```


##### The `Client` class. Interaction environment for the products.
```csharp
class Client
{
    private AbstractProductA _abstractProductA;
    private AbstractProductB _abstractProductB;

    // Constructor

    public Client(AbstractFactory factory)
    {
        _abstractProductB = factory.CreateProductB();
        _abstractProductA = factory.CreateProductA();
    }

    public void Run()
    {
        _abstractProductB.Interact(_abstractProductA);
    }
}
```

### `Real-world` code in C#

This real-world code demonstrates the creation of different animal worlds for a computer game using different factories. 

Although the animals created by the Continent factories are different, the interactions among the animals remain the same.


##### MainApp startup class for Real-World
##### Abstract Factory Design Pattern
```csharp
class MainApp
{
    /// <summary>
    /// Entry point into console application.
    /// </summary>

    public static void Main()
    {
        // Create and run the African animal world

        ContinentFactory africa = new AfricaFactory();
        AnimalWorld world = new AnimalWorld(africa);
        world.RunFoodChain();

        // Create and run the American animal world

        ContinentFactory america = new AmericaFactory();
        world = new AnimalWorld(america);
        world.RunFoodChain();

        // Wait for user input

        Console.ReadKey();
    }
}
```


##### The `ContinentFactory` abstract class
```csharp
abstract class ContinentFactory
{
    public abstract Herbivore CreateHerbivore();
    public abstract Carnivore CreateCarnivore();
}
```


##### The `AfricaFactory` abstract class
```csharp
class AfricaFactory : ContinentFactory
{
    public override Herbivore CreateHerbivore()
    {
        return new Wildebeest();
    }
    public override Carnivore CreateCarnivore()
    {
        return new Lion();
    }
}
```


##### The `ConcreteFactory2` class
```csharp
class AmericaFactory : ContinentFactory
{
    public override Herbivore CreateHerbivore()
    {
        return new Bison();
    }
    public override Carnivore CreateCarnivore()
    {
        return new Wolf();
    }
}
```


##### The `AbstractProductA` abstract class
```csharp
abstract class Herbivore
{
}
```


##### The `AbstractProductB` abstract class
```csharp
abstract class Carnivore
{
    public abstract void Eat(Herbivore h);
}
```


##### The `AbstractProductB` abstract class
```csharp
/// <summary>
/// The `ProductA1` class
/// </summary>

class Wildebeest : Herbivore
{
}
```


##### The `ProductB1` class
```csharp
class Lion : Carnivore
{
    public override void Eat(Herbivore h)
    {
        // Eat Wildebeest

        Console.WriteLine(this.GetType().Name +
            " eats " + h.GetType().Name);
    }
}
```


##### The `ProductA2` class
```csharp
class Bison : Herbivore
{
}
```


##### The `ProductB2` class
```csharp
class Wolf : Carnivore
{
    public override void Eat(Herbivore h)
    {
        // Eat Bison

        Console.WriteLine(this.GetType().Name +
            " eats " + h.GetType().Name);
    }
}
```


##### The `Client` class
```csharp
class AnimalWorld
{
    private Herbivore _herbivore;
    private Carnivore _carnivore;

    // Constructor

    public AnimalWorld(ContinentFactory factory)
    {
        _carnivore = factory.CreateCarnivore();
        _herbivore = factory.CreateHerbivore();
    }

    public void RunFoodChain()
    {
        _carnivore.Eat(_herbivore);
    }
}
```

## References

[dofactory](https://www.dofactory.com/net/design-patterns)

[javatpoint](https://www.javatpoint.com/design-patterns-c-sharp)

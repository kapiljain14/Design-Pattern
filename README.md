![GoF Design Patterns](https://github.com/girirajvyas/gof-design-patterns/raw/master/resources/images/GoF_Header.PNG)

*****
<p align="center">
    This repository contains examples of all the design patterns listed in the 
    "Design patterns - Elements of Reusable Object-oriented Software" book 
    by Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides 
    popularly known as Gang of Four (GoF). 
    
</p>

*****

## Table of contents
- Introduction
  - [What is a design pattern](#what-is-a-design-pattern)
  - [Why you should learn design patterns](#why-you-should-learn-design-patterns)
  - [How to approach](#how-to-approach)
- Creational design patterns (5)
  1. [Singleton](#1-singleton-pattern-gem)
  2. [Builder](#2-builder-pattern-construction_worker)
  3. [Prototype](#3-prototype-pattern-clipboard)
  4. [Factory Method](#4-factory-method-pattern-factory)
  5. [Abstract Factory](#5-abstractfactory-pattern-factory--factory)


# Introduction

## 1. What is a design pattern?
From Wiki:-
- **A general reusable solution to a commonly occurring problem** within a given context in software design.  
- Not a finished design that can be transformed directly into source or machine code. 
- Rather, it is a **description or template for how to solve a problem** that can be used in many different situations. 
- Design patterns are **formalized best practices** that the programmer can use to solve common problems when designing an application or system.

Classification:-
- **Creational:** Deals with the creation of an object
- **Sructural:** Deals with the class structure such as Inheritance and Composition.
- **Behavioral:** Provides solution for the better interaction between objects, also how to provide lose coupling, and flexibility to extend easily in future.

## 2. Why you should learn design patterns?
- Easy to communicate a proble among fellow developers
- It provides a common vocabulary to explain about problem
- It is an abstract topic
- Revisit materails about patterns will alway give you an new perspective everytime.

## 3. How to approach?
In case you are planning to learn them, you will typically find the structure as below for most of the patterns described here.

- What is it?
- Why would you choose?
- How to implement?
  - Design considerations
  - UML Diagram
  - Example from Java
  - Implementation
- Drawbacks (Pitfalls)
- Contrast to another patterns
- Summary

# Creational design patterns (5)

|Sr. no| Pattern name                                                    | GoF book description                                                                                                                                                       |
|-----:| -------------                                                   |:-------------:                                                                                                                                                    |
|  1   | [Singleton](#1-singleton-pattern-gem)                           | Ensure a class only has one instance, and provide a global point of access to it                                                                              |
|  2   | [Builder](#2-builder-pattern-construction_worker)               | **Saperate the construction of complex object from its representation so that the same construction process can create different representations**                    |
|  3   | [Prototype](#3-prototype-pattern-clipboard)                     | Specify the kinds of objects to create using a protypical instance, and create new objects by copying this prototype                                          |
|  4   | [Factory Method](#4-factory-method-pattern-factory)             | **Define an interface for creating an object, but let sub-classess decide which class to instantiate. Factory method lets a class defer instantiation to subclasses** |
|  5   | [Abstract Factory](#5-abstractfactory-pattern-factory--factory) | Provide an interface for creating families of related or dependent objects without specifying their concrete classes.                                         |

# Structural design patterns (7)

|Sr. no| Pattern name                                      | GoF book description                                                                                                                                                                |
|-----:| -------------                                     |:-------------:                                                                                                                                                             |
|  1   | [Adapter](#1-adapter-pattern--electric_plug)      | Convert the interface of a class into another interface clients expect. Adapter lets classes work together that couldn't otherwise because of incompatible interfaces. |
|  2   | [Bridge](#2-bridge-pattern--bridge_at_night)      | **Decouple an abstraction from its implementation so that the two can vary independently**                                                                                     |
|  3   | [Composite](#3-composite-pattern--leaves)         | Compose objects into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and compositions of objects uniformly.       |
|  4   | [Decorator](#4-decorator-pattern-heart_decoration)| **Attach additional responsibilities to an object dynamically. Decorators provide a flexible alternative to subclassing for extending functionality.**                         |
|  5   | [Facade](#5-facade-pattern--notes)                | Provide a unified interface to a set of interfaces in a subsystem. Facade defines a higher-level interface that makes the subsystem easier to use.                     |
|  6   | [Flyweight](#6-flyweight-pattern-butterfly)       | **Use sharing to support large numbers of fine-grained objects efficiently.**                                                                                                  |
|  7   | [Proxy](#7-proxy-pattern-trollface)               | Provide a surrogate or placeholder for another object to control access to it.                                                                                         |

# Behavioral design patterns (11)

|Sr. no| Pattern name                                                 | GoF book description                                                                                                                                                                                                      |
|-----:| -------------                                                |:-------------:                                                                                                                                                                                                            |
|  1   | [Chain of Responsibility](#1-chain-of-responsibility-chains) | Avoid coupling the sender of a request to its receiver by giving more than one object a chance to handle the request. Chain the receiving objects and pass the request along the chain until an object handles it.   |
|  2   | [Command](#2-command-pattern-genie)                          | **Encapsulate a request as an object, thereby letting you parameterize clients with different requests, queue or log requests, and support undoable operations.**                                                             |
|  3   | [Interpreter](#3-Interpreter-pattern-speaking_head)          | Given a language, define a represention for its grammar along with an interpreter that uses the representation to interpret sentences in the language.                                                               |
|  4   | [Iterator](#4-Iterator-pattern-loop)                         | **Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.**                                                                                                  |
|  5   | [Mediator](#5-mediator-pattern-phone)                        | Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring to each other explicitly, and it lets you vary their interaction independently. |
|  6   | [Memento](#6-memento-arrow_right_hook)                       | **Without violating encapsulation, capture and externali ze an object's internal state so that the object can be restored to this state later.**                                                                             |
|  7   | [Observer](#7-observer-eyes)                                 | Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.                                                                    |
|  8   | [State](#8-state-design-pattern-arrows_counterclockwise)     | **Allow an object to alter its behavior when its internal state changes. The object will appear to change its class.**                                                                                                        |
|  9   | [Strategy](#9-strategy-design-pattern-shipit)                | Define a family of algorithms, encapsulate each one, and make them interchangeable. Strategy lets the algorithm vary independently from clients that use it.                                                         |
|  10  | [Template method](#10-template-method-design-pattern-part_alternation_mark)| **Define the skeleton of an algorithm in an operation, deferring some steps to subclasses. Template Method lets subclasses redefine certain steps of an algorithm without changing the algorithm's structure.**              |
|  11  | [Visitor](#11-visitor-design-pattern-santa)                  | Represent an operation to be performed on the elements of an object structure. Visitor lets you define a new operation without changing the classes of the elements on which it operates.                            |

# Creational design patterns

# 1. Singleton pattern :gem:

## 1. What is Singleton?

- `GoF`: Ensure a class only has `one instance`, and provide a global point of contact to access it. 
- [Wiki](https://en.wikipedia.org/wiki/Singleton_pattern): singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.  
Critics consider the singleton to be an anti-pattern in that it is frequently used in scenarios where it is not beneficial, introduces unnecessary restrictions in situations where a sole instance of a class is not actually required, and introduces global state into an application

## 2. Why would you choose?

- Only one instance created. It is achieved by providing only one entry point to create the new instance of the class
- Useful where we have to control the resources, such as database connections or sockets 
- Lazily loaded (usually)
- **Examples:**  
   - Runtime.java  
   - Logger (singleton or factory)
   - Spring beans (by default, scope is singleton in spring)

## 3. How to implement

### 3.1 Design considerations
 - Class is responsible for creating itself and its lifecycle
 - Private instance
 - Private constructor
 - No parameters required for construction, in case parameter is required for construction than it violates singleton.

### 3.2 UML Diagram

![Singleton UML](https://github.com/girirajvyas/gof-design-patterns/raw/master/resources/images/singleton/singleton_uml.PNG)

### 3.3 Example from Java

```java
    public static void main(String args[]) {
    Runtime singletonRuntime = Runtime.getRuntime();
    singletonRuntime.gc();
    System.out.println(singletonRuntime);

    Runtime anotherInstance = Runtime.getRuntime();
    System.out.println(anotherInstance);

    if (singletonRuntime == anotherInstance) {
      System.out.println("They are the same instance");
    }
```

Output:  
```cmd
java.lang.Runtime@15db9742
java.lang.Runtime@15db9742
They are the same instance
```

### 3.4 Different Variations of creating a Singleton 
 1. Eager initialization
 2. Lazy initialization with synchronized method
 3. Lazy initialization with double check locking method
 4. Lazy initialized with static inner class (Bill pugh implementation)
 5. Lazy initialized with `Enum` which leads to less code. (Recommended by Joshua bloch in Effective Java)

#### 3.4.0 Common step:  
 - Create a class with `private constructor` to prevent initialization.  
 - Making constructor private prevents the initialization via `new` keyword
 - We expose a public static method (commonly named `getInstance()`) to provide the single entry point that returns its instance 

```java
public class Singleton {
  private Singleton() { }
  public static Singleton getInstance(){ }
}
```

#### 3.4.1 Eager Initialization  
 - Instance is created at the time of class loading, this is the easiest method to create a singleton class.
 - Create a static final class variable INSTANCE and initialize this with new instance of class
 - Create static method that returns this instance.

```java
public class SingletonEager {

  private static final SingletonEager INSTANCE = new SingletonEager();

  private SingletonEager() {}

  public static SingletonEager getInstance() {
    return INSTANCE;
  }
}
```

**Disadvantages**
  - Instance is created even if the client application may not be using it.
  - It will create an issue if your singleton class in creating a database connection or creating a socket which may lead to memory leak problem.

> As a general rule, we name the method as getInstance(), this is just convention and not mandatorily to be followed

**Prevent initialization via Reflection**  
- To prevent from initialization via reflection, you can throw exception from constructor
```java
  private Singleton() {
    // In case Reflection is used for initialization
    if (INSTANCE != null) {
      throw new RuntimeException("Please instantiate via getInstance() method");
    }
  }
```

#### 3.4.2 Lazy initialization with synchronized method  
 - Create a static class variable INSTANCE.
 - Create a synchronized method to return instance. If it is not initialized, initialize it and return.
 - In case you do not make method synchronized, multiple instances might be created in multithreaded environment

```java
public class SingletonLazyWithSynchronizedMethod {

  private static SingletonLazyWithSynchronizedMethod INSTANCE;

  private SingletonLazyWithSynchronizedMethod() {
    if (INSTANCE != null) {
      throw new RuntimeException("Please instantiate via getInstance() method");
    }
  }

  public static synchronized SingletonLazyWithSynchronizedMethod getInstance() {
    if (INSTANCE == null) {
      INSTANCE = new SingletonLazyWithSynchronizedMethod();
    }
    return INSTANCE;
  }
}
```
**Disadvantages**
 - Slow performance because of locking overheand in every call
 - Unnecessary synchronization that is not required once the instance variable is initialized.
 - Demo of multiple instances in case method is not synchronized
   ```java
     private static void lazySingletonMultiThreadsIssueDemo() {
     Thread t1 = new Thread(() ->  {
       SingletonLazy instance1 = SingletonLazy.getInstance();
       System.out.println("Hashcode of instance1: "+ instance1.hashCode());
     });
     
     Thread t2 = new Thread(() ->  {
       SingletonLazy instance2 = SingletonLazy.getInstance();
       System.out.println("Hashcode of instance2: "+ instance2.hashCode());
     });
     
     t1.start();
     t2.start();
     
     Output:
     Hashcode of instance1: 60675678
     Hashcode of instance2: 1100599114
     Note: you might have to run this quite a few times to see this different output.
     As, you cannot predict the thread behaviour
     }
   ```

#### 3.4.3 Lazy initialization with double check locking method
- To overcome above slow performance issue we will use this way for initialization.
- Create a static class variable INSTANCE. 
- We are marking this variable `volatile`, so that any changes to this instance are visible to other threads instantly
- You can return instance if it is already initialized. Now, we add conditions when the instance is null. We create a synchroniized block and create an instance inside this block. We add an additional null check to avoid duplicate initialization because of two threads.
- Synchronized block will be executed only when the INSTANCE is null and prevent unnecessary synchronization once the instance variable is initialized
```java
public class SingletonLazyWithDoubleCheckLocking {

  private static volatile SingletonLazyWithDoubleCheckLocking INSTANCE;

  private SingletonLazyWithDoubleCheckLocking() {
    if (INSTANCE != null) {
      throw new RuntimeException("Please instantiate via getInstance() method");
    }
  }

  public static SingletonLazyWithDoubleCheckLocking getInstance() {
    // Check synchronization only if the instance is null. There will be a
    // little impact in performance only for the first time.
    if (INSTANCE == null) {
      synchronized (Singleton.class) {
        // double check if instance is still null, It can be the case that till the time
        // thread2 reaches here, thread1 has already initialized the instance
        if (INSTANCE == null) {
          INSTANCE = new SingletonLazyWithDoubleCheckLocking();
        }
      }
    }
    return INSTANCE;
  }
}
```

> Without volatile modifier, it’s possible for another thread in Java to see half initialized state of INSTANCE variable, but with volatile variable guaranteeing happens-before relationship, all the write will happen on volatile INSTANCE before any read of INSTANCE variable.

**Prevent duplicate object creation via serialization**  
- In case of serializing the Singleton class, you might not get the same instance. to solve this issue you have to implement readresolve method
```java
    protected Singleton readResolve() {
        return INSTANCE;
    }
``` 

#### 3.4.4 Lazy initialization with static inner class (Bill pugh)
- TODO, code available


#### 3.4.5 Enum Singleton
- Implementation added with DbSingletonEnum

```java
public enum DbSingletonEnum {

  INSTANCE;

  private Connection conn;

  private DbSingletonEnum() {
    try {
      String dbUrl = "jdbc:derby:memory:codejava/webdb;create=true";
      conn = DriverManager.getConnection(dbUrl);
    } catch (SQLException e) {
      e.printStackTrace();
    }
  }

  public Connection getConnection() {
    return conn;
  }
}
```
> The best way to implement a `Serializable Singleton` is to use an Enum

> From Joshua Bloch's Effective Java: This approach is functionally equivalent to the public field approach, except that it is more concise, provides the serialization machinery for free, and provides an ironclad guarantee against multiple instantiation, even in the face of sophisticated serialization or reflection attacks. While this approach has yet to be widely adopted, a single-element enum type is the best way to implement a singleton.

## 4. Drawbacks 
- Often overused
- Difficult to unit test
- If not careful, not threadsafe
- Sometimes confused for factory

> :stop_sign:   java.util.Calendar is not a Singleton, rather it is Prototype. It is confused as Singleton as it has getInstance() method.

## 5. Contrast to other patterns

| Singleton                        | Factory                                           |
| -------------                    |:-------------:                                    |
| Returns same instance            | Returns various instances                         |
| One constructor method - no args | Multiple constructors                             |
| No interface                     | Interface Driven                                  |
| No Subclasses                    | Always SubClasses are involved in a way or other  |
| NA                               | Adaptable to environment more easily**            |


## Summary
- Guarantees one instance
- Easy to implement
- Solves a well defined problem
- You can still violate the Singleton principle by creating more than one instance of the Singleton class by using cloning or using multiple class loaders
- Don't abuse it

## Next
Explore the Enum version of Singleton pattern

**[&#11014;  back to top](#table-of-contents)**

# 2. Builder pattern :construction_worker:

## 1. What is Builder?
- `GoF`: Separate the construction of a complex object from its representation so that the same construction process can create different representations.
- `Other`: This a pattern people often use but rarely create of there own. This pattern deals with construction of Objects with lot of parameters and want to make the object once we are done constructing it.
- [Wiki](https://en.wikipedia.org/wiki/Builder_pattern): The builder pattern is a design pattern designed to provide a flexible solution to various object creation problems in object-oriented programming. The intent of the Builder design pattern is to separate the construction of a complex object from its representation 


## 2. Why would you choose?
- Handles complex constructors
- Large number of parameters
- Immutability
- **Examples:**
  - StringBuilder
  - DocumentBuilder
  - Locale.Builder

## 3. How to implement

### 3.1 Design considerations
- Flexibility over telescoping constructors
- Generally implemented with static inner class
- Calls appropriate constructor
- Negates the need for exposed setters
- Java 1.5+ can take advantage of generics ***

### 3.2 UML Diagram

### 3.3 Example from Java

```java
public class BuilderJavaApiExample {
	
	public static void main(String[] args) {
		StringBuilder builder = new StringBuilder();
		builder.append("This is an example ");
		builder.append("of the builder pattern. ");
		builder.append("It has methods to append ");
		builder.append("almost anything we want to a String. ");
		builder.append(42);
		System.out.println(builder.toString());
	}
	
}
```

Output:  
```cmd
This is an example of the builder pattern. It has methods to append almost anything we want to a String. 42
```

### 3.4 Implementation

- Demonstrate exposed setters (LunchOrderBean.java / LunchOrderBeanDemo.java)
- Demonstrate Telescoping constructors (LunchOrderTelescopic.java / LunchOrderTelescopicDemo.java)
- Create Builder (LunchOrder.java / LunchOrderDemo.java)
- Build out example

**Steps to create:**
- Create a class which is supposed to have many fields and required immutable instance
- Decalre all fields as final, so that they can only be initialized in constructor
- Create a public static builder inner class
- Copy all the field declarations in the inner class without making them final (In case you make field inside inner class as final you have to initialize that in constructor else you will ahve compilation error)
- Create a public default constructor in Builder class (you can put any parameters here to make them mandatory)
- Now, create methods taking field type as input and returning complete instance after setting that. for example
   ```java
    public Builder bread(String bread) {
       this.bread = bread;
       return this;
    }
   ```
- Create a private constructor in Outer class that takes this Builder class and sets all the fields from the builder instance.
  ```java
    private LunchOrder(Builder builder) {
        this.bread = builder.bread;
        this.condiments = builder.condiments;
        this.dressing = builder.dressing;
        this.meat = builder.meat;
    }
  ```
- Create a build method that will return the instance of Outer class. This is achieved by passing this builder instance to the outer class constructor
  ```java
    public LunchOrder build() {
       return new LunchOrder(this);
    }
  ```
- You can test the above builder as:
  ```java
    LunchOrder.Builder builder = new LunchOrder.Builder(); 
    builder.bread("bread").condiments("condiments").dressing("dressing").meat("meat");
    LunchOrder lunchOrder = builder.build();
  ```
- Done  

## 4. Drawbacks
- Immutable objects are created
- Inner static class is generally used for implementation
- It is always Designed first 
- Adds complexity, as people are not comfortable with object returning itself with each subsequent call

## 5. Contrast to other patterns

| Builder                               | Prototype                              |
| -------------                         |:-------------:                         |
| Handles complex constructors          | Implemented around a clone             |
| No interface required                 | Avoids calling complex constructors    |
| Can be a saperate class               | NA                                     |
| Works with a legacy code              | Difficult to implement in legacy code  |


## 6. Summary
- Creative way to deal with complexity
- Easy to implement
- few drawbacks
- can refactor in with a saperate class (typically implemented with a static inner class)

## Next
Explore the Generics version of builder pattern


**[&#11014;  back to top](#table-of-contents)**

# 3. Prototype pattern :clipboard:

## 1. What is Prototype Pattern?

- `GoF`: Specify the kinds of objects to create using a protypical instance, and create new objects by copying this prototype
- `Other`: creates copy of objects that are very expensive to create
- [Wiki](https://en.wikipedia.org/wiki/Prototype_pattern):  It is used when the type of objects to create is determined by a prototypical instance, which is cloned to produce new objects. This pattern is used to:
  - avoid subclasses of an object creator in the client application, like the factory method pattern does.
  - avoid the inherent cost of creating a new object in the standard way (e.g., using the 'new' keyword) when it is prohibitively expensive for a given application.  
To implement the pattern, declare an abstract base class that specifies a pure virtual clone() method. Any class that needs a "polymorphic constructor" capability derives itself from the abstract base class, and implements the clone() operation.  
The client, instead of writing code that invokes the "new" operator on a hard-coded class name, calls the clone() method on the prototype, calls a factory method with a parameter designating the particular concrete derived class desired, or invokes the clone() method through some mechanism provided by another design pattern.  
The mitotic division of a cell — resulting in two identical cells — is an example of a prototype that plays an active role in copying itself and thus, demonstrates the Prototype pattern. When a cell splits, two cells of identical genotype result. In other words, the cell clones itself   

## 2. Why would you choose?
- Avoids costly creation
- Avoids Subclassing
- Typically doesn't use keyword "new"
- Often utilizes an Interface
- Usually implemented with a registry
- **Example:**
  - java.lang.Object#clone()

## 3. How to implement?

### 3.1 Design considerations
- Typically implements clone/cloneable
- Avoids keyword "new"
- Although copy, each instance is unique
- Costly construction not handled by client (builder is opposite of prototype)
- Can still utilize parameters for construction
- Shallow vs deep copy design considerations can be made 

### 3.2 UML Diagram

### 3.3 Example from Java
```java

```

## Example/Demo
- Create Prototype
- Demonstrate shallow copy
- Create with a registry

This design pattern can be achieved in 2 ways  
1. implementing Cloneable interface
2. create copy(method with any logical name) and return the copy of current object
First way of implementation is discouraged as specified in Effective Java:

Note: 
1. We have seen an example with `clone()` method, but this can also be achieved by creatin an interface and implementing the clone method.
2. You can replace string with enum in createItem method of registry.

## 4. Drawbacks
- Sometimes not clear when to use
- Used with other patterns
   - Registry
- Mostly shallow copy by clone, for deep copy we have to implement ourselves and it requires a lot of code

## 5. Contrast to other patterns

| Prototype                             | Factory                                                            |
| -------------                         |:-------------:                                                     |
| Light weight construction             | Flexible Objects based on request                                  |
|  - Copy constructor or clone method   |  - multiple constructors can be use instead of just clone method   |
| Choose shallow vs deep copy           | Create fresh and cconcrete instance of object                      |
| Main purpose to create copy of itself | NA                                                                 |

## 6. Summary
- Guarantee unique instance
- Often refactored in 
- Can help with performance issues
- Dont always jump to a factory

> Prototype patterns are usually implemented with a Registry

> A Prototype is used when you want to guarantee a unique instance that is lightweight to create

## Next:
you can try prototype pattern with Generics and without clone method 
References: https://refactoring.guru/design-patterns/prototype

**[&#11014;  back to top](#table-of-contents)**

# 4. Factory method pattern :factory: 

## Different naming for factory pattern

1. Creation method(Creation/Factory Method): "Refactoring" by Martin F. , "Refactoring to patterns" by Joshua K.
2. Static factory method: "Effective Java" by Joshua B. 
3. Simple (parameterized) factory: Head first Design patterns
4. Factory Method and Abstract Factory: Design Patterns: Elements of Reusable Object oriented Software


## Why would you choose?
- Doesn't expose instantiation logic
- Defer to subclasses i.e A super class has multiple sub-classes and based on input, need to return one of the sub-class
- Common interfaces
- Specified by architecture, implemented by user
- **Examples:**
   - Calendar (many consider this as Singleton example due to no arg getInstance() method)
   - ResourceBundle
   - NumberFormat
   
## Design Considerations
- Factory is responsible for lifecycle
- It has common interface
- For this common interface, there are Concrete classes
- Parameterized create method

## Example/Demo
- Create Pages
- Create Website
- Create concrete classes
- Create factory
- Create Enum

Flow:
```java
                             Website (abstract class)
                          abstract void createWebsite()
                          public List<Page> getPages()
             __________________________|___________________________
            |                                                      |
    Blog extends Website                                        Shop extends Website
    - PostPage                                                   - CartPage
    - AboutPage                                                  - ItemPage
    - CommentPage                                                - SearchPage
    - ContactPage

   WebsiteFactory
    factoryMethod(Type type) {   
       Switch (type):  
         BLOG:
           return new Blog();
         Shop
         return new Shop();
    }
```
   
## 4. Drawbacks:
- Complexity 
- Creation in subclass **
- Refactoring: This is not something that is refactored later, rather a design decision to make early in development

## 5. Contrast to other patterns

| Singleton                        | Factory                                           |
| -------------                    |:-------------:                                    |
| Returns same instance            | Returns various instances                         |
| one constructor method - no args | multiple constructors                             |
| no interface                     | Interface Driven                                  |
| No Subclasses                    | Always SubClasses are involved in a way or other  |
| NA                         | Adaptable to environment more easily**            |

## 6. Summary
- Parameter Driven (chooses type based on this)
- Solves Complex creation (Choose type at runtime)
- A little complex
- Opposite of a Singleton

**[&#11014;  back to top](#table-of-contents)**

# 5. AbstractFactory pattern :factory:  :factory:

## Why would you choose?

- Factory of Factories i.e there is a family of factories and you need a super factory for related factories
- Factory of related Objects
- Common Interface
- Defer to subclasses for instantiation
- **Examples**
   - DocumentBuilderFactory
   - Mostly in frameworks

## Design Considerations
- Groups Factories Together
- Factory is responsible for lifecycle of itself
- Common Interface
- Concrete classes are returned from the underlying factory
- Parameterized create method like factory pattern
- Built using composition, not the case with Factory.

## Example/Demo
- Create classes that will be used
- Build AbstractFactory
- Then build Factory as it will be used by abstractfactory
- Factory returns concrete implementation

Flow
```java
                                    CreditCardFactory (Abstract Factory)
                    - static CreditCardFactory getCreditCardFactory(int creditScore)
                    - abstract CreditCard getCreditCard(CardType cardType);
                    - abstract Validator getValidator(CardType cardType);
               ___________________________________|_________________________________
              |                                                                     |
        AmexFactory  (extends CreditCardFactory)                VisaFactory  (extends CreditCardFactory)
     public CreditCard getCreditCard(CardType cardType) {
        switch (cardType) {
          case GOLD:
             return new AmexGoldCreditCard();
          case PLATINUM:
             return new AmexPlatinumCreditCard();
        }
     }
    public Validator getValidator(CardType cardType) {
        switch (cardType) {
          case GOLD:
            return new AmexGoldValidator();
          case PLATINUM:
            return new AmexPlatinumValidator();
        }
    }
```

if you are not using the ORM and you have to use the db queries depending on the db you are using, this pattern will find implementation their.

## Drawbacks
- Complexity - most complex of creational design patterns
- Runtime Switch - cleenct can change the flow by passing some parameters
- Pattern within a pattern
- Problem specific (limited scope)
- Starts as a factory and the refactored to abstractFactory

## Contrast to other patterns

| Factory                              | AbstractFactory                                     |
| -------------                        |:-------------:                                      |
| Returns various instances            | Implemented with a factory                          |
|   - multiple constructors            | Hides the underlying concrete factory                |
| Interface Driven                     | 1 more layer of Abstraction added to  environment   |
| Adaptable to environment more easily | Built through composition                           |

## Summary
- Group of similar factories
- Complex
- Heavy abstraction
- Written at framework level


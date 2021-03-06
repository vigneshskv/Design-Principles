# SOLID Principles #
- [Introduction](#introduction)
  - [Acronym](#acronym)
  - [Advantage](#advantage-of-following-solid-principles)
- [Solid principles in detail](#solid-principles-in-detail)
  - [Single Responsiblity Principle](#single-responsiblity-principle-(srp))
  - [Open closed Principle](#opne-closed-principle-(osp))
  - [Liskov substitution Principle](#liskov-substitutin-principle-(lsp))
  - [Interface Segregation Principle](#interface-segregation-principle-(isp))
  - [Dependency Inversion Principle](#dependency-inversion-principle(dip))
- [Reference](#reference)

# Introduction #
Design principles to manage most of software design problems.
Helps to design a software that is understandable, flexibe and manageable.
 
## Acronym ##
 | Acronym | Meaning |
 | --- | --- |
 | S | Single Responsiblity Principle (SRP) |
 | O | Open closed Principle (OSP) |
 | L | Liskov substitution Principle (LSP) |
 | I | Interface Segregation Principle (ISP) |
 | D | Dependency Inversion Principle (DIP) }

## Advantage of following SOLID principles ##
- Achieve reduction in complexity of code.
- Increase readablity, extensiblity and maintenance.
- Reduce error and implemnt reusuablity.
- Achieve better testablity.
- Reduce tight coupling.

# Solid Principles in detail #
## Single Responsiblity Principle (SRP) ##
A class should have only one reason to change.

Every class or module should have resposiblity over a single part of the functionality provided by the software, and that responsiblity shopuld be entirely encapsulated by the class.

### Motivation ###
- Maintainablity
- Testablity
- Flexiblity and Extensiblity
- Parallel Development
- Loose Coupling


## Open closed Principle (OSP) ##
Software entities should be open for extension, but closed for modification.

The design adn writting of the code should be done in a way that new functionality shouldbe added with minimum changes in the existing code.
The design should be done in a way to allow the adding of new functionality as new classes, keeping as much as possible existing code unchanged.


## Liskov substitution Principle (LSP) ##
Objects in a program should be replaceable with instances of thier subtypes without altering the correctness of that program.

If a program module is using a Base class, then the refernce to the Base class can be replaced with a Derived class without affecting the functionality of the program module.
i.e, Derived types must be substituable for their base types.


## Interface Segregation Principle (IS{) ##
Many client-specific interfaces are better than one general-purpose interface.


We shopuld not enforce clients to implement interfaces that they don't use. Instead of creating one big interface we can break down it to smaller interfaces.

## Dependency Inversion Principle (DIP) ##
One should depend upon abstractions, not concretions.

Abstractions should not depend on the detials whereas the detials should depend on abstractions.
High-level modules should not depend on low level modules.


# Referenc #
 - [butunclebob](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
 - [Youttube Tutorial](https://www.youtube.com/watch?v=HLFbeC78YlU)

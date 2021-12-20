# SOLID Cheat Sheet.

## S: Single Responsibility Principle.

![Image of Single Responsibility Principle](/quite-solid/assets/img/srp.png "Image of Single Responsibility Principle")

Each and every class in your project should have one, and only one responsibility.

## O: Open-Closed Principle.

![Image of Open-Closed Principle](/quite-solid/assets/img/ocp.png "Image of Open-Closed Principle")

Entities in your software system should be open for extension, but closed for modification.

## L: Liskov Substitution Principle.

Functions that use pointers or references to base classes must be able to use objects of derived classes without knowing it.

It is better to use composition instead of type hierarchies.

## I: Interface Segregation Principle.

![Image of Interface Segregation Principle throught delegation](/quite-solid/assets/img/isp-delegate.png "Image of Interface Segregation Principle throught delegation")

ISP throught delegation ↑

![Image of Interface Segregation Principle throught multiple inheritance](/quite-solid/assets/img/isp-multi-inheritance.png "Image of Interface Segregation Principle throught multiple inheritance")

ISP throught multiple inheritance ↑

Clients should not have to implement interfaces that they don’t use.

ISP enforces division of responsibility between interfaces.

## D: Dependency Inversion Principle.

![Image of Dependency Inversion Principle](/quite-solid/assets/img/dip.png "Image of Dependency Inversion Principle")

High level modules should not depend on lower level modules. Both should depend on abstractions. Abstractions should not depend on details. Details should depend on abstractions.

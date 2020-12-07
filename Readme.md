# Object Oriented Programming...style
A Programming **paradigm** centered around objects rather than functions. ie grouping together related data & functions. 
C# Java Ruby Python Javascript

**Primative data** types store single simple values
**Example**
_byte    int    float   Boolean   double  char_

**Strucuture vs Arrays**
| Strucuture         | Arrays    |     |
| ------------------ | --------- | --- |
| stores data        | store day |     |
| diff types of data | cannot    |     |
|                    |

_--Procedural Programming...spaghetti_

=>**Object**
* objects are instances of a class
* Classes are templates for objects
* _properties_


## 4 pillars of oop
1. **Encapsulation**
   * bundling data with methods that can operate on that data within a class.(hiding data within class & anything outside cannot interact with...can interact with that class methods...)..Getting Methods(retrieving) & Setting Methods(changing in4)
   * _**read only**_
   * reduce complexity + increase reusability
   * _Group related objects together_

2. **Abstraction**
* Only Showing essintial details and keeping everything else hidden.
* working on problems incrementally.
   * reduce complexity + isolate impact of changes
   * Interface => sections of code communicate with one another...methods
   * Implementation...within class

3. **Inherintance**
* allows classes to derive from other classes...superclass..subclass..subclass
* class hierachy
* _**Access Modifiers**_:
  * **_public_**.. can be Accessed from anywhere
  * _**private**_...can only be Accessed within the same class that the member is defined
  * **protected**...can be Accessed within class it's defined as well as any subclasses of that class.
* Eliminate redundant code

4. **Polymorphism**
* describes methods that are able to take on many forms
* types;
    * **dynamic Polymorphism**
  occurs during runtime of program & describes method signature is in both a subclass and superclass.
  methods share same name but have different Implementation.
* ...works becoz the form of method is decided based on where in the class hierachy it is called. ..dynamically.
    *  **Static Polymorphism**.. occurs during complile-time ...this refers to when multiple methods with the same but different arguments are defined in the same class.
    *  method overloading.. diff no of parameters..

   * Refactor ugly switch/case statements
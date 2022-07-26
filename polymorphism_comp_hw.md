# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

the condition of occuring in several forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

When an object has the ability to take on many forms, in OO, this occurs when a parent class reference is used to refer to a child class object.

public interface openWindows{}
public class Building{}
public class House extends Building implements openWindows{}

House class is polymorphic as it inherits the House as a super class, and also open windows function when implementing openWindows interface

3. What can we use to implement polymorphism in Java? 

Inheritances and interfaces

4. How many 'forms' can an object take when using polymorphism?

there are no limits on interfaces that can be inherited but can only inherit from one form i.e. the Parent.

5. Give an example of when you could use polymorphism.

Group class of ojects that share one or several types together i.e. a name can be shared between a customer and an employee

# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

To allow an object to be composed of other objects

7. When would you use composition? Provide a simple example in Java.

When object/ components share the a similar outcome even with data, i.e. a Motorbike and a Car object can share same ignition function, but one can be started by turning a key and other can be by pressing a button.

8. Give a difference between composition and aggregation?

Composition is when an object is part of another object.

Aggregation is when an object has something.

9. What is/are the advantage(s) of using composition/aggregation?

The reusibility of code and software productivity.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

They also get destroyed

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

Objects can exist independently.


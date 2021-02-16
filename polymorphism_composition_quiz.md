# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
- Polymorphism means "many forms"

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
- In OO design it means that a class can be treated as if it were another type that it inherits from/ another class it connects to via an interface. For example; if you had a car class that inherited from a vehicle class you could treat the car as a vehicle.

3. What can we use to implement polymorphism in Java?
- Inheritance and Interfaces.

4. How many 'forms' can an object take when using polymorphism?
- There is no limit, as many as are needed/wanted.

5. Give an example of when you could use polymorphism.
- You could have a vehicle superclass with car, bus and motorbike classes that are it's children. If the vehicle class had a "start engine" function, all of the child classes would have access to it too.


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
- Composition is a relationship where an object is made up of (composed of) other objects.

7. When would you use composition? Provide a simple example in Java.
- You could use it when making a car class. It could be composed of engine, gearbox and wheels objects.

8. Give a difference between composition and aggregation?
- When using composition to make an object the objects it's composed of cannot exist without the parent, and will be lost if the parent is deleted. With aggregation they can still exist independently.


9. What is/are the advantage(s) of using composition/aggregation?
- It allows a class to use the behaviour of it's related classes, while giving more flexibility and reusability than simply using inheritance.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
- They are also destroyed.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
- They are not destroyed, as they are separate objects that exist independently of the parent object.

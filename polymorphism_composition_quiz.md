# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

    Many shapes.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

    In OOP Polymorphism means that we can use the same variable in different forms at different times in the programme.  
    An example of this would be implementing an interface on a class.  The class then has it's pwn properties but also those
    of the interface and can use them at different times in the programme depending on what we want it to do/function that we
    want it to perform.

3. What can we use to implement polymorphism in Java?

    We can use inheritance or interfaces.  Interfaces are the preferred way to do it as this makes the code more flexible.

4. How many 'forms' can an object take when using polymorphism?

    An object can take as mant different 'forms' as we give it as multiple interfaces can be implemented on a class.

5. Give an example of when you could use polymorphism.

    I would use polymorphism where more than one class has a shared behaviour (though they can execute that behaviour in different ways.)



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

    Composition in OOP is where an Object is made up of one or more Objects.    

7. When would you use composition? Provide a simple example in Java.

    I would use composition where there is a 'has a' relationship between two Objects.
    For example a car and an engine.  A car has an engine, therefore a car is composed of
    an engine (and other things) 

8. What is/are the advantage(s) of using composition?

    One of the advantages of composition is Strategy pattern where you give a Class the ability
    to replace an Object that it is composed of with another Object.
    Other advantages are that it makes our code dry and easy to maintain and scale up.

9. When an object is destroyed, what happens to all the objects it is composed of?

    All other Objects will remain where they were created and are available to be used by other Classes.
Polymorphism


1.What does the word 'polymorphism' mean?
The ability of an object to take on many forms;

2.What does it mean when we apply polymorphism to OO design? Give a simple Java example.
In java for example an electric car can be a car as well as a vehicle as well as any interfaces it has implemented/ has inherited from.


3.What can we use to implement polymorphism in Java?
Use interfaces, that can be implemented across many classes. To then use objects polymorphically you specify said objects, by their shared interface type.



4.How many 'forms' can an object take when using polymorphism?
As many as it's own object accommodates for; so as many interfaces as you can add provided they all have methods the interfaces promise.

5.Give an example of when you could use polymorphism.
If you were grouping two types of insurance at an insurance company, e.g. home insurance vs car insurance. They will both be very different objects but can share things through an interface like amount needed to insure, total cost expected, assumed asset costs. A calculator class can then group them both as Iinsureable objects to calculate a value for how much they pay.





Composition


6.What do we mean by 'composition' in reference to object-oriented programming?
I understand it as a "has-a", so multiple object can have a specific thing, but these are not neccessarily inherited properties. High level classes are not dependant on lower level classes rather an abstraction, like an interface that can later be linked to the lower level classes.

7.When would you use composition? Provide a simple example in Java.
When you'd want a higher level class to be able to use 'have-a' lower class as part of it. E.g. A gym has members, but some abstraction between these two classes can exist, i.e. an interface that requires certain properties/methods with the members. The gym is instead linked to the interface ('has an' interface), which then has anything that fulfills the interfaces promises rather than just the member class.


8.What is/are the advantage(s) of using composition?
Can do dependency inversion as a strategy pattern. Allows for flexibility with what classes can be linked to other ones. Not 100% sure

9.When an object is destroyed, what happens to all the objects it is composed of?
they still exist in their own object/classes? not to sure

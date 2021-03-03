# skillupafrica
polymorphism

Polymorphism
Polymorphism means many shapes in Greek.
Let's assume we have a parent class and a few child classes which inherit from it. Sometimes we want to use a collection — for example a list — which contains a mix of all these classes.
Or we have a method implemented for the parent class — but we’d like to use it for the children, too. This can be solved using polymorphism.
In other words, we can say polymorphism gives a way to use a class exactly like its parent so there’s no confusion with mixing types. But each child class keeps its own methods as they are.
This typically happens by defining a (parent) interface to be reused. It outlines a bunch of common methods. Then, each child class implements its own version of these methods.

Any time a collection (such as a list) or a method expects an instance of the parent (where common methods are outlined), the language takes care of evaluating the right implementation of 
the common method — regardless of which child is passed.


Bubble Sort Assignment.

iteration 1: [5,3,1,4,2,6] [3,5,1,4,2,6] [3,1,5,4,2,6] [3,1,4,5,2,6] [3,1,4,2,5,6] [3,1,4,2,5,6]
 
iteration2: [3,1,4,2,5,6] [1,3,4,2,5,6] [1,3,4,2,5,6] [1,3,2,4,5,6] [1,3,2,4,5,6] [1,3,2,4,5,6]

iteration3: [1,3,2,4,5,6] [1,2,3,4,5,6]

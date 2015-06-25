#Abstract Classes
-----------------
- When you DON'T want a class to be instantiated, mark the class with **abstract** keyword
- Abstract classes can _both_ abstract and non-abstract methods
- If a class has even **one** abstract method, it _must_ be marked abstract
- _ALL_ abstract methods must be implemented in the first concrete subclass
- Every class in Java is a sublass of class **Object**
- Methods can be declared with Object arguments and return types

- You can only class methods on an object based on the **reference variable type**, regardless of the actualy object type

- A reference variable of type Object can't be assigned to any other reference type without a cast
    - The cast will fail if the object on the heap is NOT a type compatible with the cast
- All objects come out of the ArrayList<object> as type object
- Multiple inheritance is not allowed in Java
	- Dead Diamond of Death
- An interface is like a 100% pure abstract class.
	- It defines _only_ abstract methods
	- interface keyword:
    ```Java
public interface OperateCar{
}
	
- Classes can implement multiple interfaces
- Inferface methods are implicitly public and abstract
- To invote superclass version of a method, use **super** keyword


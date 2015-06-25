#Memory
- Java has 2 areas of memory
	- The Stack
	- The Heap
- Instance Variables: inside class, but outside method
- Local Variables: inside method
	- Live on the stack withing the method's frame
- Object reference variables: if declared as local variable, goes on stack
- All objects live on the heap
- Instance variables: inside class
	- Live in the object on the heap
- If instance variable is reference to an object, both the reference and the object it refers to live on the Heap

- Constructor
	- Runs when you say **new** on a class type
	- Must have the same name as the class
	- **No return** type
	- Can initialize the state of object being constructed
	- Default is no args constructor
	- If you put a constructor in your class, the compiler will not build the default constructor
	


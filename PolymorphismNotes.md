#Polymorphism
---------------
- A subclass **extends** superclass
- A subclass _inherits_ all **public** instance variables and methods of the superclass
- A subclass does _**not** inherit_ the **private** instance variables and nethods
- Inherited methods can be overridden
- Instance variables cannot be overriden, but can be redefined
- **IS-A** test for inheritance
- **HAS-A** test for instance

- Inheritance guarantees subclasses have supertype's methods
- Any subclass of a supertype can be subtituted where the supertype is expected

- Polymorphism: the reference type is a superclass of the actual object type
- Polymorphic arguments and return types: arguments, return types are of superclass type, and are passed any subclass at runtime

- Method Overloading: having two methods with same name and different argument list
    - Can have different return type
    - Can't change only the return type
    - Can't vary access levels in any direction
# Access-Specifiers-in-C-
In C++, there are three access specifiers: 
• public - members are accessible from outside the class
• private - members cannot be accessed (or viewed) from outside the class • protected - members cannot be accessed from outside the class, however, they can be accessed in inherited classes.
Access modifiers are used to implement an important feature of Object Oriented Programming known as Data Hiding.

I. Public:
All the class members declared under public will be available to everyone.
The data members and member functions declared public can be accessed by other classes too.
 The public members of a class can be accessed from anywhere in the program using the direct member access operator (.) with the object of that class.

II. Private
The class members declared as private can be accessed only by the functions inside the class.
They are not allowed to be accessed directly by any object or function outside the class.
Only the member functions or the friend functions are allowed to access the private data members of a class.

The output of the program will be a compile time error because it is not allowed to access the private data members of a class directly outside the class.
However, we can access the private data members of a class indirectly using the public member functions of the class.


III. Protected
Protected access modifier is similar to that of private access modifiers, the difference is that the class member declared as Protected are inaccessible outside the class but they can be accessed by any subclass(derived class) of that class.

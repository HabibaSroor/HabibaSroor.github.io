The Ueage of CONST keyword in c++
1. For constant variables:
The const variable cannot be left un-initialized at the time of the assignment.
It cannot be assigned value anywhere in the program.
Explicit value needed to be provided to the constant variable at the time of declaration of the constant variable.
2. Constant Values: you can use the const keyword instead of the #define preprocessor directive to define constant values.
3. Pointer Variables: Pointers can be declared with a const keyword. So, there are three possible ways to use a const keyword with a pointer.
4. you can specify the size of an array with a const variable.
5. You can use pointers to constant data as function parameters to prevent the function from modifying a parameter passed through a pointer.
6. Declaring a member function with the const keyword specifies that the function is a "read-only" function that does not modify the object for which it is called.
7. For objects that are declared as const, you can only call constant member functions. This ensures that the constant object is never modified



The usage of &
1. used in C++ as a reference declarator in addition to being the address operator.
2. The bitwise AND operator (&) compares each bit of the first operand to that bit of the second operand. If both bits are 1, the bit is set to 1. Otherwise, the bit is set to 0. Both operands to the bitwise AND operator must be of integral types. 

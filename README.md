# Aim : To implement Stack operations (push, pop, display) using arrays in C++.

# Theory :

Stacking" in C++ is achieved using the std::stack container adaptor, which enforces the Last-In, First-Out (LIFO) principle—the last element added (pushed) is the first one removed (popped). All core operations (push(), pop(), and top()) have excellent O(1) constant time complexity, meaning their speed doesn't depend on the stack's size. It's the standard, safe choice for applications like recursion management, undo/redo functionality, and expression parsing, as its constrained interface prevents the bugs that might arise from using more flexible containers like std::vector directly.

# Algorithm

Start the program.

Define a class Stack with:

Data members: array arr[MAX] and integer top.

Functions: push(), pop(), display().

Initialize top = -1.

In push(val):

If top == MAX-1, print Stack Overflow.

Else increment top and insert value.

In pop():

If top == -1, print Stack Underflow.

Else decrement top.

In display():

Print all elements from index 0 to top.

In main(), perform multiple push, pop, and display operations.

End the program

# Conclusion
Implemented Stack operations using arrays.
Understood stack properties: Overflow and Underflow conditions.
Learned LIFO principle and how to simulate it programmatically.






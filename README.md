# A brief Introduction To Stack Abstract Data Type --Python

A stack is a collection of objects that are inserted and removed according to the last-in, first-out (LIFO) principle.

Stacks are the simplest of all data structures, yet they are also among the most important. 

They are used in a host of different applications, and as a tool for many more sophisticated data structures and algorithms. Formally, a stack is an abstractdata type (ADT) such that an instance S supports the following two methods:
S.push(e): Add element e to the top of stack S.
S.pop( ): Remove and return the top element from the stack S; an error occurs if the stack is empty.

Additionally, let us define the following accessor methods for convenience:

S.top( ): Return a reference to the top element of stack S, without removing it; an error occurs if the stack is empty.
S.is empty( ): Return True if stack S does not contain any elements.
len(S): Return the number of elements in stack S; in Python, we implement this with the special method len .
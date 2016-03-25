# Dynamic-Memory
Use of pointers, malloc and free functions,  linked lists, reading and writing, argv and argc, recursive functions, Dy avl balanced binary trees

This assignment will re-implement the student database with dynamic memory and saving into files. Here’s the specification for the application:

 a) Student entries should be kept in a linked list with memory allocated when a new student is introduced by the user. Memory should be deallocated when a user is removed.
 
 b) The Menu presented to the user should be:
       1) Introduce student
       2) Remove student
       3) Print student report
       4) Print report for all students
       5) Save to file
       6) Retrieve data from file
       7) Exit
       
 c) Your code should contain a insert and remove function. Ideally these will receive a pointer to pointer to the root of the list (but you can keep the head of the list as a global variable)
 
 d) You should also implement a version of insert and remove functions that use balanced binary trees. This will be worth 15% of you final mark. The user should be able to choose the data structure directly from the command line when it starts the program. This should use the argc/argv arguments to main()

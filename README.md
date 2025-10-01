# Implementation-of-Linked-list-in-CPP  

## Aim  
Implementation of Linked List in C++  

## Software Required  
- MinGW C++ Compiler  
- VS Code  
- Online C/C++ Compiler  

---

## Program 1  

### Explanation with Theory  
This program demonstrates the creation of a basic linked structure using a **Node class**. Each node stores an integer value and a pointer to the next node. Two nodes are dynamically allocated and connected to form a simple chain. The `display()` method prints the node’s data and shows whether it points to another node or terminates the list.  

This implementation introduces the concept of **pointer-based connectivity**, which is the foundation of linked lists. It also highlights **dynamic memory allocation** and **object-oriented programming design**, making it a suitable starting point for understanding linked structures in C++.  

### Algorithm  
1. Define a `Node` class with value and pointer `next`.  
2. Dynamically create two nodes using `new`.  
3. Link the first node to the second.  
4. Use `display()` to show each node’s value and linkage.  
5. End.  

---

## Program 2  

### Explanation with Theory  
This program builds a **singly linked list** using dynamic memory allocation and **head insertion**. The `Node` class defines each element with a value and a pointer to the next node.  

The `addToFront()` function inserts new nodes at the beginning of the list by updating the head pointer, while the `printList()` function traverses the list and prints each value, ending with `NULL`.  

This structure allows efficient insertion at the head in **O(1) time complexity**, making it ideal for stack-like behavior. It reinforces important concepts such as **pointer manipulation**, **dynamic allocation**, and **list traversal** in object-oriented programming.  

### Algorithm  
1. Define a `Node` class with value and pointer `next`.  
2. Initialize `head` as `nullptr`.  
3. For each new value:  
   - Create a new node.  
   - Set its `next` to the current `head`.  
   - Update `head` to this new node.  
4. Traverse the list using `printList()` and display all node values ending with `NULL`.  
5. End.  

---

## Conclusion  
Both programs illustrate the **core principles of singly linked lists in C++**, including dynamic memory allocation, node linking using pointers, and modular design through functions.  

- **Program 1** introduces the basics with a simple two-node chain.  
- **Program 2** extends this to multiple nodes with efficient **head insertion** and traversal.  

Together, these implementations provide a strong foundation for understanding linked lists. They prepare learners for more advanced features suc

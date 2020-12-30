# What is linked list ?
-A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.

-Node : Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
-Next : Each node contains a property called Next. This property contains the reference to the next node.
-Head :The Head is a reference type of type Node to the first node in a linked list.
-Current : The Current reference is a reference type of type Node that is currently being looked at.

#NOTE:When traversing a linked list, you are not able to use a foreach or for loop. 

-The best way to approach a traversal is through the use of a while() loop. This allows us to continually check that the Next node in the list is not null. If we accidentally end up trying to traverse on a node that is null, a NullReferenceException gets thrown and our program will crash/end.

When traversing through a linked list, the Current node is the most helpful. The Current will tell us where exactly in the linked list we are and will allow us to move/traverse forward until we hit the end.

---------------------------------------------

# Linear data structures :
-One characteristic of linked lists is that they are linear data structures, which means that there is a sequence and an order to how they are constructed and traversed.

- In non-linear data structures, items don’t have to be arranged in order, which means that we could traverse the data structure non-sequentially.

-The fundamental difference between arrays and linked lists is that arrays are static data structures, while linked lists are dynamic data structures. A static data structure needs all of its resources to be allocated when the structure is created; this means that even if the structure was to grow or shrink in size and elements were to be added or removed, it still always needs a given size and amount of memory. If more elements needed to be added to a static data structure and it didn’t have enough memory, you’d need to copy the data of that array, for example, and recreate it with more memory, so that you could add elements to it.

-On the other hand, a dynamic data structure can shrink and grow in memory. It doesn’t need a set amount of memory to be allocated in order to exist, and its size and shape can change, and the amount of memory it needs can change as well.

---------------------------------------

-A linked list is made up of a series of nodes, which are the elements of the list.

-A single node is also pretty simple. It has just two parts: data, or the information that the node contains, and a reference to the next node.

-Singly linked lists are the simplest type of linked list, based solely on the fact that they only go in one direction. 

-doubly linked list is called like this because there are two references contained within each node: a reference to the next node, as well as the previous node.

-A circular linked list is a little odd in that it doesn’t end with a node pointing to a null value. Instead, it has a node that acts as the tail of the list, and the node after the tail node is the beginning of the list.


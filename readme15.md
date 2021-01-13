# Trees 

Common Terminology
Node - A node is the individual item/data that makes up the data structure
Root - The root is the first/top Node in the tree
Left Child - The node that is positioned to the left of a root or node
Right Child - The node that is positioned to the right of a root or node
Edge - The edge in a tree is the link between a parent and child node
Leaf - A leaf is a node that does not contain any children
Height - The height of a tree is determined by the number of edges from the root to the bottommost node

There are two categories of traversals(traverse allows you to search for a node) when it comes to trees:

1-Depth First
2-Breadth First

 We have three methods for depth first traversal:

-Pre-order: root >> left >> right
-In-order: left >> root >> right
-Post-order: left >> right >> root

Big O
The Big O time complexity for inserting a new node is O(n). Searching for a specific node will also be O(n).
The Big O space complexity for a node insertion using breadth first insertion will be O(w), where w is the largest width of the tree. 

----------------------------------------

Binary Search Trees
A Binary Search Tree (BST) is a type of tree that does have some structure attached to it. In a BST, nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.

Searching a BST
Searching a BST can be done quickly, because all you do is compare the node you are searching for against the root of the tree or sub-tree. If the value is smaller, you only traverse the left side. If the value is larger, you only traverse the right side.

Big O
The Big O time complexity of a Binary Search Tree’s insertion and search operations is O(h), or O(height). In the worst case, we will have to search all the way down to a leaf, which will require searching through as many nodes as the tree is tall. In a balanced (or “perfect”) tree, the height of the tree is log(n). In an unbalanced tree, the worst case height of the tree is n.

The Big O space complexity of a BST search would be O(1). During a search, we are not allocating any additional space.
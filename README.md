# Non-linear_Data-Structure

### Common Trees Implementation:
1. Have a value
2. Have a reference to zero or more other Tree Nodes
3. Can add a node as a child
4. Can remove a child
5. Can traverse (or travel through) connected nodes

### Binary Search Trees
Binary search trees are a type of tree data structure with the added condition that each element 
to the left of a node must be less than that parent node, and each element to the right of a node 
must be greater than that parent node. Each left and right subtree is also itself a binary search tree, 
which makes searching for elements more efficient.

### Heaps
Heaps are another variation of the tree data structure and are adept at keeping track of the maximum or minimum 
value held within, referred to as max-heaps and min-heaps, respectively. Specifically, heaps are a type of binary tree, 
since each child node is either greater or less than its parent (depending on if it’s a max-heap or min-heap). 
They are efficient for accessing the root value, which will either be the max or min 
(again, depending on the type of heap) and inserting new values

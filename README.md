# BinarySearchTree

### Successfully built a Binary Search Tree (BST) data structure in Java.

### - a BinarySearchTree class containing value, left and right child nodes and a depth value.

### - an .insert() method to place a node of that value at the correct location in the Binary Search Tree. The time efficiency of this operation is O(logN) – if there are N nodes in the BST, the max depth of an average tree is log(n), so this method makes at most log(n) value comparisons. In the worst case of an imbalanced tree (all values on one side), the performance would be O(N).

### - a .getNodeByValue() method to retrieve a node in the tree by its value. The time efficiency of this operation is also O(logN) – if there are N nodes in the BST, the max depth of the tree is log(n), so this method makes at most log(n) value comparisons. In the worst case of an imbalanced tree (all values on one side), the performance would be O(N).

### - a .depthFirstTraversal() method to print the inorder traversal of the Binary Search Tree. This visits every single node, so if there are N nodes, time efficiency for traversal is O(N).
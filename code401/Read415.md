# What we will learn

- Trees 

The source of this summary [The first link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

______________________________________

## Trees

**In computer science, a binary tree is a tree data structure in which each node has at most two children, which are referred to as the left child and the right child. ... A binary tree is a special case of an ordered K-ary tree, where k is 2.**


**Trees Terminology**

1. Node : A Tree node is a component which may contain it’s own values, and references to other nodes

2. Root : The root is the node at the beginning of the tree

3. K : the maximum number of children any node may have in a k-ary tree.

4. Left : one child node, in a binary tree

5. Right: the other child node, in a binary tree

6. Edge : the link between a parent and child node

7. Leaf : a node that does not have any children

8. Height : The height of a tree is the number of edges till the root

![the Tree](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/BinaryTree1.PNG)

## Traversals

**Traversal is a process to visit all the nodes of a tree and may print their values too. Because, all nodes are connected via edges (links) we always start from the root (head) node.**

### There are two categories:

* Depth First

          - Pre-order: root >> left >> right            Pre-order: A, B, D, E, C, F

          - In-order: left >> root >> right             In-order: D, B, E, A, F, C

          - Post-order: left >> right >> root           Post-order: D, E, B, F, C, A



* Breadth First

*traversal iterates through the tree by going through each level of the tree node-by-node*



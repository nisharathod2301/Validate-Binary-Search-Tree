# Validate-Binary-Search-Tree
Given the root of a binary tree, determine if it is a valid binary search tree (BST).

https://leetcode.com/problems/validate-binary-search-tree/

A valid BST is defined as follows:

The left subtree of a node contains only nodes with keys less than the node's key.
The right subtree of a node contains only nodes with keys greater than the node's key.
Both the left and right subtrees must also be binary search trees.

![image](https://user-images.githubusercontent.com/109743699/184062391-554cb222-6a1e-414a-9fed-2a18386e8b95.png)

Input: root = [2,1,3]

Output: true

Constraints:

The number of nodes in the tree is in the range [1, 104].
-231 <= Node.val <= 231 - 1

# 📊 LeetCode Problem: Maximum Depth of Binary Tree

## 🧩 Problem Statement

Given the `root` of a binary tree, return its **maximum depth**.

> **Note :**
> - A binary tree's maximum depth is the number of nodes along the longest path from the `root` node down to the farthest leaf node.



## 🧠 Approach: Recursive Depth Dive :

- Use recursion to explore each branch.

- Base case:

> - If the node is NULL, return 0.

- Otherwise:

> - Recursively calculate the depth of left and right subtrees.

> - Return 1 + max(leftDepth, rightDepth) to account for the current level.

- The final answer is simply the height of the root node.



## ✅ Example Walkthrough

### Example 1

##### Input: root = [3,9,20,null,null,15,7]
##### Output: 3


### Example 2

##### Input: root = [1,null,2]
##### Output: 2



## 🛠️ Constraints

- The number of nodes in the tree is in the range `[0, 10^4]`
- `-100 <= Node.val <= 100`

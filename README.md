# Day41-50-days-coding-challenge

# Day 41: Delete Node in BST & Longest Common Prefix

## 🌲 Problem 1: Delete Node in a BST

### ✅ Problem Statement:
Given the root of a Binary Search Tree (BST) and a key, delete the node with that key and return the new root of the tree.

### 🧠 Approach:
- Traverse the tree to find the node with the given key.
- Case 1: Node has no children → Remove it.
- Case 2: Node has one child → Replace node with child.
- Case 3: Node has two children → Replace with inorder successor, then delete successor.

### 📘 Example:
Input: root = [5,3,6,2,4,null,7], key = 3  
Output: [5,4,6,2,null,null,7]

### 💡 Constraints:
- Tree contains up to 10^4 nodes.
- Each node has a unique value.
- All values are in range [-10^5, 10^5].

---

## 🔤 Problem 2: Longest Common Prefix

### ✅ Problem Statement:
Given an array of strings, return the longest common prefix string among them. If none exists, return an empty string.

### 🧠 Approach:
- Sort the array.
- Compare first and last strings character by character to get the common prefix.

### 📘 Example:
Input: ["flower","flow","flight"]  
Output: `"fl"`

Input: ["dog","racecar","car"]  
Output: `""`

### 💡 Constraints:
- 1 <= strs.length <= 200
- 0 <= strs[i].length <= 200
- strs[i] contains only lowercase letters.

---

## 🏁 Summary
- Mastering BST operations like insert and delete is key to understanding tree structures.
- Longest common prefix is a frequent string processing problem, useful in search engines, compilers, etc.

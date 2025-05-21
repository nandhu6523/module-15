# Experiment 9(a): Binary Tree (Float Values)

## Aim
To write a Python program to build a binary tree with a root, left, and right node using float values.

---

## Algorithm

1. Start the program.
2. Import the `Node` class from the `binarytree` module.
3. Create a root node using the `Node` class and input a floating-point value for the root.
4. Create left and right child nodes for the root using floating-point values.
5. Convert the binary tree to a list.
6. Print the list of nodes.
7. End the program.

---

## Program

```
from binarytree import Node
l=(float(input()),float(input()),float(input()))
root= Node(l[0])
root.left = Node(l[1])
root.right = Node(l[2])
print('List of nodes :', list(root))
```

## OUTPUT
![Screenshot 2025-05-05 005114](https://github.com/user-attachments/assets/958dc815-9434-4ea4-b949-9487de2ebc78)

## RESULT
The program accepts three float values from the user, builds a binary tree with those values, and prints the list of node values.

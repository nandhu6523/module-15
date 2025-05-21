# Experiment 9(d): Heap Tree

## Aim
To write a Python program to build a heap tree using appropriate Python package and function.

---

## Algorithm

1. Start the program.
2. Import the `heapq` module.
3. Define a function `heaptree()` that takes a list `H` as input.
4. Use `heapq.heapify(H)` to convert the list into a valid heap (min-heap).
5. Print the created heap.
6. End the program.

---

## Program

```
import heapq
def heaptree(l):
    heapq.heapify(l)
    print("The created Heap is",l)
```

## OUTPUT
![Screenshot 2025-05-05 010557](https://github.com/user-attachments/assets/7b5f060e-bd0b-42cf-bacb-d34b5f1db365)

## RESULT
Thus, the task has been completed to build heap tree using appropriate Python package and function and successfully verified.

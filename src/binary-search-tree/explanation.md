# Binary Search Tree

## Steps

Given the array **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**, the binary search tree construction is as follows:

```
            7
           / \
          5   8
         / \    \
        1   6    9
       / \
      0   3
         / \
        2   4
```

### Construction Steps:

1. 7 is the root node.
2. 5 is less than 7, so it goes to the left.
3. 1 is less than 7 and 5, so it goes to the left of 5.
4. 8 is greater than 7, so it goes to the right.
5. 3 is less than 7, less than 5, but greater than 1, so it goes to the right of 1.
6. 6 is less than 7 but greater than 5, so it goes to the right of 5.
7. 0 is less than 7, 5, and 1, so it goes to the left of 1.
8. 9 is greater than 7 and 8, so it goes to the right of 8.
9. 4 is less than 7 and 5, but greater than 3, so it goes to the right of 3.
10. 2 is less than 7, 5, and 3, but greater than 1, so it goes to the left of 3.

---

### Big-O Analysis:

- **Insertion**: Average case **O(log n)**, Worst case **O(n)**.
- **Search**: Average case **O(log n)**, Worst case **O(n)**.

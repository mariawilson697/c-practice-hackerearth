# Minimum Steps to Equalize Array Elements

This C program calculates the **minimum number of steps** required to make all elements of array `a[]` equal using a specific rule:
> In each step, set `a[i] = a[i] - b[i]` **only if** `a[i] > b[i]`.

If it's not possible to make all elements of `a[]` equal, the program returns `-1`.

---

## Problem Statement

You are given two arrays `a[0…n-1]` and `b[0…n-1]`. You are allowed to perform the following operation on any element of `a` any number of times:

if a[i] > b[i], then a[i] = a[i] - b[i]



Determine the **minimum number of such steps** required to make all `a[i]` equal. If it's not possible, return `-1`.

---

## 🧾 Input Format

- First line: Integer `n` — the number of elements.
- Second line: `n` integers — elements of array `a`.
- Third line: `n` integers — elements of array `b`.

### Example Input
5
5 7 10 5 15
2 2 1 3 5


---

## ✅ Output Format

- Single integer: Minimum number of steps required to make all elements of `a[]` equal.
- If not possible, print `-1`.

### Example Output

---

## Constraints

- `0 <= n, a[i], b[i] <= 5000`

---

## How It Works

1. The program first finds the **minimum value** in array `a[]`, called `least_num`.
2. For each element in `a[]`, it subtracts `b[i]` repeatedly until `a[i]` becomes equal to `least_num`.
3. The steps for each `a[i]` are counted and accumulated.
4. If at any point the operation is not valid (like `b[i] == 0`, or overshooting the minimum), the program returns `-1`.

---

## Files

- `main.c` — Contains the implementation of the program.

---

Developed as a C programming practice task.

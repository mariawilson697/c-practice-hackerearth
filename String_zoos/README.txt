# Zoo Word Checker

## Problem Description

You are given a word consisting only of the characters `Z` and `O`, where:
- The word starts with one or more **Zs**.
- The **Zs** are followed by one or more **Os**.
- You need to check whether the word can be considered similar to the word **"zoo"**.

### Similarity Rule:
The word is considered similar to **zoo** if:

> **Number of Os = 2 × Number of Zs**

---

## Input Format

- A single string containing only uppercase **Z** followed by **O**.
- The maximum length of the word is **20 characters**.

### Example Input:
zzzoooooo

---

## Output Format

- Print **`Yes`** if the word is similar to "zoo", otherwise print **`No`**.

### Example Output:
Yes
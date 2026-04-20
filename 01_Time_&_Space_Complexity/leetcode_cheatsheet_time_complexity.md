# ⚡ LeetCode Complexity Cheat Sheet

## 📌 Time Complexity Guide

| Complexity | Name                  | Max n (approx) | Use Case |
|------------|----------------------|---------------|---------|
| O(1)       | Constant             | Any           | Direct access (array index) |
| O(log n)   | Logarithmic          | 10^18         | Binary search |
| O(n)       | Linear               | 10^8          | Single loop |
| O(n log n) | Linearithmic         | 10^7          | Sorting, heap |
| O(n^2)     | Quadratic            | 10^4          | Nested loops |
| O(2^n)     | Exponential          | ≤ 20          | Backtracking |
| O(n!)      | Factorial            | ≤ 10          | Permutations |

---

## 🧠 Quick Decision Rules

- If `n ≤ 10^8` → O(n) works
- If `n ≤ 10^5` → O(n log n) preferred
- If `n ≤ 10^4` → O(n^2) acceptable
- If `n ≤ 20` → exponential allowed

---

## 🔁 Common Patterns vs Complexity

| Pattern              | Typical Complexity |
|---------------------|-------------------|
| Two Pointers        | O(n)              |
| Sliding Window      | O(n)              |
| HashMap / Set       | O(n)              |
| Binary Search       | O(log n)          |
| DFS / BFS           | O(V + E)          |
| Heap / PriorityQueue| O(n log n)        |
| Backtracking        | O(2^n) / O(n!)    |
| Dynamic Programming | O(n) / O(n^2)     |

---

## ⚠️ TLE (Time Limit Exceeded)

- ~10^8 operations per second
- Avoid:
  - Nested loops for large `n`
  - Recomputing values
  - Inefficient recursion

---

## 💡 Optimization Checklist

- Can I use a **HashMap**?
- Can I reduce nested loops using **Two Pointers**?
- Can I use **Binary Search on answer**?
- Can I store results (**DP / Memoization**)?
- Can I preprocess (**Prefix Sum**)?

---

## 🚀 Interview Tip

> First write brute force → then optimize

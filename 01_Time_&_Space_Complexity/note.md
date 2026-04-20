# ⏱️ Time & Space Complexity Notes

## 📌 Time Complexity
**Definition:**  
Rate of increase in execution time with respect to input size (`n`)

---

## 🔷 Big-O Notation
- Represented as: `O()`
- Describes **upper bound (worst-case scenario)**

---

## ⚙️ Rules to Follow
1. Always calculate complexity in terms of **worst case**
2. Ignore constant factors  
   - Example: `O(2n)` → `O(n)`
3. Ignore lower-order terms  
   - Example: `O(n² + n)` → `O(n²)`
4. Do not change input assumptions unless explicitly asked

---

## 📊 Types of Cases

### 1. Best Case
- Minimum time taken  
- Rarely considered in analysis  

### 2. Average Case
- Typical expected time  
- ❗ Not simply `(best + worst) / 2`

### 3. Worst Case
- Maximum time taken  
- Most important for analysis  

---

## 📐 Asymptotic Notations

| Notation | Meaning      | Case Type   |
|----------|--------------|------------|
| O (Big-O) | Upper bound  | Worst case |
| Θ (Theta) | Tight bound  | Average / Exact |
| Ω (Omega) | Lower bound  | Best case |

---

## 💾 Space Complexity
Total memory used by an algorithm

### Formula:

Space Complexity = Auxiliary Space + Input Space


### 🔹 Auxiliary Space
- Extra space used by algorithm  
- Example: variables, recursion stack, temporary arrays  

### 🔹 Input Space
- Memory used to store input data  

---

## ⚠️ Time Limit Exceeded (TLE)

### ⏳ What it means:
Your algorithm is too slow for given constraints  

### 🧠 Key Insight:
- Most platforms allow ~10⁸ operations per second  

---

## 🔢 Approximation Guide

| Complexity | Max Input Size (n) |
|------------|-------------------|
| O(1)       | Any               |
| O(log n)   | 10¹⁸              |
| O(n)       | 10⁸               |
| O(n log n) | 10⁷               |
| O(n²)      | 10⁴               |
| O(2ⁿ)      | ≤ 20              |
| O(n!)      | ≤ 10              |

---

## 🚀 Practical Tip
1. Check constraints (`n`)
2. Choose algorithm accordingly  

- `n ≤ 10⁴` → O(n²) possible  
- `n ≤ 10⁵` → aim for O(n log n) or O(n)
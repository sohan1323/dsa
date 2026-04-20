# 🐍 Python Time Complexity (Concept-wise)

---

## 🔢 1. Variables & Operators
| Operation        | Complexity |
|-----------------|-----------|
| Assignment      | O(1)      |
| Arithmetic ops  | O(1)      |
| Comparison      | O(1)      |

---

## 🔁 2. Loops
| Operation              | Complexity |
|----------------------|-----------|
| for loop (n times)   | O(n)      |
| nested loops         | O(n²)     |
| while loop           | O(n)      |

---

## 📦 3. Lists

### 🔹 Access & Update
| Operation        | Complexity |
|-----------------|-----------|
| index access    | O(1)      |
| update element  | O(1)      |

### 🔹 Insert/Delete
| Operation        | Complexity |
|-----------------|-----------|
| append()        | O(1) amortized |
| pop()           | O(1)      |
| insert()        | O(n)      |
| remove()        | O(n)      |
| pop(i)          | O(n)      |

### 🔹 Search & Sort
| Operation        | Complexity |
|-----------------|-----------|
| x in list       | O(n)      |
| index()         | O(n)      |
| sort()          | O(n log n) |
| sorted()        | O(n log n) |

---

## 🔑 4. Dictionary (HashMap)

| Operation        | Complexity |
|-----------------|-----------|
| access          | O(1) avg |
| insert          | O(1) avg |
| delete          | O(1) avg |
| search (key)    | O(1) avg |
| iteration       | O(n)     |

⚠️ Worst case: O(n) (hash collision)

---

## 🧺 5. Set

| Operation        | Complexity |
|-----------------|-----------|
| add()           | O(1) avg |
| remove()        | O(1) avg |
| in              | O(1) avg |
| union/intersection | O(n)  |

---

## 🔤 6. Strings

| Operation        | Complexity |
|-----------------|-----------|
| indexing        | O(1)      |
| slicing         | O(n)      |
| concatenation   | O(n)      |
| join()          | O(n)      |
| search (in)     | O(n)      |

⚠️ Strings are immutable → operations create new string

---

## 📚 7. Tuples

| Operation        | Complexity |
|-----------------|-----------|
| access          | O(1)      |
| iteration       | O(n)      |

---

## 🔗 8. List Comprehension

| Operation        | Complexity |
|-----------------|-----------|
| comprehension   | O(n)      |

---

## 🔄 9. Recursion

| Case                     | Complexity |
|--------------------------|-----------|
| linear recursion         | O(n)      |
| binary recursion         | O(2ⁿ)     |
| recursion + memoization  | O(n)      |

---

## 🧠 10. Sorting Algorithms (Python uses Timsort)

| Case         | Complexity |
|-------------|-----------|
| best case    | O(n)      |
| average      | O(n log n)|
| worst        | O(n log n)|

---

## 🔍 11. Searching

| Operation        | Complexity |
|-----------------|-----------|
| linear search    | O(n)      |
| binary search    | O(log n)  |

---

## 📊 12. Heap (heapq)

| Operation        | Complexity |
|-----------------|-----------|
| push            | O(log n)  |
| pop             | O(log n)  |
| peek            | O(1)      |

---

## 🌲 13. Tree / Graph (General)

| Operation        | Complexity |
|-----------------|-----------|
| DFS / BFS       | O(V + E)  |

---

## ⚡ 14. Common Python Built-ins

| Function        | Complexity |
|----------------|-----------|
| len()          | O(1)      |
| min()/max()    | O(n)      |
| sum()          | O(n)      |
| any()/all()    | O(n)      |

---

## 🚀 Key Takeaways

- List → fast access, slow insert/delete
- Dict/Set → fastest lookups (O(1))
- String → expensive modifications
- Sorting → O(n log n)
- Nested loops → O(n²) → avoid for large n

---
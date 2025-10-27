# 🔢 Sorting Algorithms Analysis
> A comparative study of Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Counting Sort.

---

## 📘 Overview
This project was developed as part of the **Higher Diploma in Science in Software Development**.  
It focuses on understanding, implementing, and comparing the performance of five fundamental sorting algorithms.  
Each algorithm was implemented in **Java**, tested with data sets of varying sizes, and analyzed for time complexity and efficiency.

---

## 🧩 Algorithms Covered

### 🫧 Bubble Sort
- **How it works:** Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.  
- **Best Case:** O(n) *(already sorted)*  
- **Average Case:** O(n²)  
- **Worst Case:** O(n²)  
- **Notes:** Simple but inefficient for large data sets.

---

### 🧮 Counting Sort
- **How it works:** Counts the number of occurrences of each value and uses these counts to place elements directly into their sorted position.  
- **Best/Average/Worst Case:** O(n + k), where *k* is the range of input values  
- **Notes:** Not a comparison sort; only works with non-negative integers or small ranges.  
- **Very efficient for limited numeric ranges.**

---

### 💡 Insertion Sort
- **How it works:** Builds the final sorted array one item at a time by inserting each new element into the correct position.  
- **Best Case:** O(n)  
- **Average Case:** O(n²)  
- **Worst Case:** O(n²)  
- **Notes:** Performs well for small or nearly sorted lists.

---

### 🧠 Merge Sort
- **How it works:** Uses the divide-and-conquer approach — splits the array into halves, sorts them recursively, and merges the sorted halves.  
- **Best Case:** O(n log n)  
- **Average Case:** O(n log n)  
- **Worst Case:** O(n log n)  
- **Notes:** Very efficient and stable but uses extra memory for merging.

---

### 🎯 Selection Sort
- **How it works:** Repeatedly selects the smallest element from the unsorted part and moves it to the beginning.  
- **Best/Average/Worst Case:** O(n²)  
- **Notes:** Performs the same number of comparisons regardless of order; good for small arrays.

---

## ⚙️ Technologies Used
- **Language:** Java  
- **Tools:** Visual Studio Code / Eclipse  
- **Testing:** Timer methods to measure execution time for each algorithm  
- **Data:** Randomly generated integer arrays  

---

## 📊 Performance Comparison
| Algorithm       | Best Case | Average Case | Worst Case | Type            | Extra Space |
|-----------------|------------|---------------|--------------|------------------|--------------|
| Bubble Sort     | O(n)       | O(n²)         | O(n²)        | Comparison-based | O(1) |
| Selection Sort  | O(n²)      | O(n²)         | O(n²)        | Comparison-based | O(1) |
| Insertion Sort  | O(n)       | O(n²)         | O(n²)        | Comparison-based | O(1) |
| Merge Sort      | O(n log n) | O(n log n)    | O(n log n)   | Comparison-based | O(n) |
| Counting Sort   | O(n + k)   | O(n + k)      | O(n + k)     | Non-comparison   | O(k) |

---

## 🧭 Learning Outcomes
- Gained a clear understanding of **algorithm efficiency** and **Big O notation**.  
- Learned to **implement and test** sorting algorithms from scratch.  
- Understood the difference between **comparison** and **non-comparison** sorts.  
- Applied **benchmarking** to measure real execution times.

---

## 🧩 Example Output

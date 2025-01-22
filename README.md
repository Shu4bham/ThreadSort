# ThreadSort

---

**Description:**

This project demonstrates an efficient implementation of the Merge Sort algorithm using multithreading in C++. It compares the performance of three sorting approaches: a traditional single-threaded merge sort, a parallelized merge sort using multithreading, and the standard inbuilt `std::sort` function provided by the C++ Standard Template Library (STL). 

### **Key Features:**
1. **Traditional Merge Sort:**
   - Implements the classic divide-and-conquer strategy for sorting.
   - Operates in \(O(n \log n)\) time complexity without multithreading.

2. **Parallel Merge Sort:**
   - Enhances merge sort with multithreading to achieve faster sorting by leveraging concurrency.
   - Threads are created dynamically to divide sorting tasks, with a threshold to avoid overhead on smaller data segments.

3. **Inbuilt Sort Benchmarking:**
   - Includes performance comparison with `std::sort` to provide a baseline for evaluation.

### **Use Case:**
This project is ideal for understanding:
- The benefits of parallel computing in algorithm optimization.
- Performance trade-offs between single-threaded and multithreaded implementations.

### **Applications:**
- Educational purposes to demonstrate algorithm optimization with multithreading.
- Use in performance-critical systems where sorting large datasets is frequent.

---

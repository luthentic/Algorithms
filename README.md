
## 🚀 Introduction

My personal on going study project about Data-Structures, Algorithms, and Design-Patterns 

<p align="center">
  <img src = "https://png.pngtree.com/png-vector/20221021/ourlarge/pngtree-tiny-cute-children-learning-coding-png-image_6334852.png" width=700 height=500>
</p>

## 🚩 Table of Contents
1. [Time Complexity](#time-complexity)
   1. What's Time Complexity?
   2. How to Calculate
   3. Why is it important
   4. Example
2. [Space Complexity](#space-complexity)
   1. What's Space Complexity?
   2. How to Calculate
   3. Why is it important
   4. Example
3. [Design Pattern](#design-pattern)
   1. [Creational Pattern](#creational-pattern)
      1. Singleton Pattern
      2. Factory Pattern
      3. Builder Pattern
      4. Prototype Pattern
   2. [Structural design pattern](#structural-design-pattern)
      1. Decorator design pattern
      2. Adapter design pattern
      3. Composite design pattern
      4. Façade design pattern
      5. Proxy design pattern
   4. [Behavioral design pattern](#behavioral-design-pattern)
      1. Strategy design pattern
      2. Observer design pattern
      3. Mediator design pattern
      4. Command design pattern
      5. Template Method design pattern
      
4. [Data Structure](#data-structure)
    1. [Arrays](arrays)
    2. [Linked Lists](linked-lists)
    3. [Stacks](stacks)
    4. [Queues](queues)
    5. [Trees](trees)
    6. [Sets](sets)
    7. [Dictionaries](dictionaries)
    8. [Graphs](graphs)
    9. [Hash Tables](hash-tables)
    10. [Heap](Heap)
    11. [Priority Queue](priority-queue)
    12. [Trie](trie)
    13. [Skip Lists](skip-lists) 
             
5. [Algorithm](#algorithm)
    1. [Searching](#searching)
         1. Binary Search
         2. Linear Search
         3. Depth First Search
         4. Breadth First Search
         5. Z Algorithm
    2. [Sorting](sorting)
         1. Insertion Sort
         2. Heap Sort
         3. Selection Sort
         4. Merge Sort
         5. Quick Sort
         6. Counting Sort
         7. Bucket Sort
         8. Bubble Sort
         9. Radix Sort
         10. Shell Sort
         11. Comb Sort
         12. Pigeonhole Sort
         13. Cycle Sort
    3. [Graphs](graph)
         1. Kruskal's Algorithm
         2. Dijkstra's Algorithm
         3. Bellman Ford Algorithm
         4. Floyd Warshall Algorithm
         5. Topological Sort Algorithm
         6. Flood Fill Algorithm
         7. Lee Algorithm
         8. Prim's Algorithm
         9. Boruvka's Algorithm
         10. Johnson's Algorithm
         11. Kosaraju's Algorithm
         12. Tarjan's Algorithm
    4. [Arrays](url)
          1. Kadane's Algorithm
          2. Floyd's Cycle Detection Algorithm
          3. Knuth-Morris-Pratt Algorithm (KMP)
          4. Boyer - More Majority Vote Algorithm
    5. [Trees](trees)
          1. Binary Trees
          2. Binary Search Trees
          3. AVL Trees, N-ary Tree
          4. B-tree
          5. Quadtree and Octree
          6. Minimum Spanning Trees
          7. segment tree
          8. Fenwick Trees
          9. AA Tree
          10. Quadtree

  
***

## 🧭Time Complexity

### What's Time Complexity?
  
  Time complexity is a fundamental concept in computer science that measures the efficiency of an algorithm.
  
  Time complexity is commonly estimated by counting the number of elementary operations performed by the algorithm, supposing that each elementary operation takes a fixed amount of time to perform.
  
### How to Calculate:

  Time complexity quantifies the amount of time an algorithm takes to run as a function of the input size. It’s typically expressed using big O notation, which provides an upper bound on the growth rate of the algorithm’s runtime.
  
  To calculate time complexity, analyze how the number of operations performed by the algorithm changes with respect to the input size. Consider the worst-case scenario (i.e., the maximum number of operations).

  For example, if you have a loop that iterates through an array of size n, the time complexity would be linear (O(n)) because the number of iterations grows linearly with n.

### Why is it important:

  Efficient algorithms are crucial for optimizing program performance. Understanding time complexity helps us:
  Compare different algorithms and choose the most efficient one for a specific problem.

  Predict how an algorithm will perform as the input size increases.
  
  Identify bottlenecks and optimize critical parts of our code.
  
  In practice, choosing an algorithm with better time complexity can significantly impact the speed of execution, especially for large datasets.
  
### Example
  
  **Big O Notation (O):**
  
  Big O notation represents an algorithm’s worst-case complexity. It describes the upper bound on the runtime of an algorithm.
  
  When we say an algorithm has a time complexity of O(f(n)), it means that the algorithm’s runtime grows no faster than a constant multiple of f(n) as the input size increases.
  
  For example, linear search has a time complexity of O(n), where n is the number of elements in the input1.
  
  **Big Omega Notation (Ω):**
  
  Big Omega notation represents an algorithm’s best-case complexity. It describes the lower bound on the runtime of an algorithm.
  
  When we say an algorithm has a time complexity of Ω(g(n)), it means that the algorithm’s runtime grows at least as fast as a constant multiple of g(n) for large inputs.
  
  For example, the best-case time complexity of quicksort is Ω(n log n)2.
  
  **Big Theta Notation (θ):**
  
  Big Theta notation represents an algorithm’s average-case complexity or tight bound.
  
  When we say an algorithm has a time complexity of θ(h(n)), it means that the algorithm’s runtime grows at the same rate as a constant multiple of h(n) for large inputs.
  
  For example, merge sort has an average-case time complexity of θ(n log n)3.
  
  **Little O Notation (o):**
  
  Little O notation represents an algorithm’s strictly upper bound.
  
  When we say an algorithm has a time complexity of o(p(n)), it means that the algorithm’s runtime grows strictly slower than a constant multiple of p(n).
  
  For example, insertion sort has a time complexity of o(n^2) (it’s faster than quadratic time, but not as fast as linearithmic time)
  


## 🏠Space Complexity
  
  ### What's Space Complexity?

  Space complexity refers to the total amount of memory that an algorithm or operation requires based on its input size.
  
  Unlike time complexity, which focuses on how long an algorithm takes to run, space complexity focuses on memory usage.
  
  ### Notations:

  **O(1)** (constant complexity): Takes the same amount of space regardless of input size.
  
  **O(log n)** (logarithmic complexity): Takes space proportional to the logarithm of the input size.
  
  **O(n)** (linear complexity): Takes space directly proportional to the input size.
  
  **O(n log n)** (log-linear/quasilinear complexity): Grows proportionally to the input size and a logarithmic factor.
  
  **O(n^2)** (square/polynomial complexity): Space complexity grows proportionally to the square of the input size

  ### Why is it important:

  **Memory Efficiency:** Efficient use of memory is crucial. By analyzing space complexity, developers can optimize their code to utilize memory more efficiently.
  
  **Resource Constraints:** In real-world scenarios (e.g., embedded systems, mobile devices, cloud servers), memory resources are limited. Algorithms that consume excessive memory can lead to performance bottlenecks.
  
  **Scalability:** As data sizes grow, inefficient memory usage becomes more pronounced. Algorithms with poor space complexity may not scale well.
  
  **Algorithm Design:** Space complexity influences algorithm design choices. Sometimes, a trade-off exists between time and space complexity.
  
  **Debugging and Maintenance:** Code that uses excessive memory can be harder to debug and maintain.
  
  ### Example:

  **O(1) - Constant Complexity:** An algorithm with constant time complexity takes the same amount of time regardless of the input size.
  
  Example: Accessing an element in an array by index

  ```csharp
  int[] myArray = { 10, 20, 30, 40 };
  int firstElement = myArray[0]; // O(1)
  ```

  **O(log n)** - Logarithmic Complexity:
  
  Logarithmic time complexity means the algorithm’s runtime grows proportionally to the logarithm of the input size.
  
  Example: Binary search in a sorted array.


  ```csharp
  int BinarySearch(int[] arr, int target)
{
    int left = 0;
    int right = arr.Length - 1;
    while (left <= right)
    {
        int mid = left + (right - left) / 2;
        if (arr[mid] == target)
            return mid;
        else if (arr[mid] < target)
            left = mid + 1;
        else
            right = mid - 1;
    }
    return -1; // Not found
}
  ```

## 🏁Design Pattern
 - ### Creational Pattern


## ⭐Data Structure

## 🤖Algorithm


## 📜References


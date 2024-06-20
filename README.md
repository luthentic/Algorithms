
## 🚀 Introduction

My personal on going study project about Data-Structures, Algorithms, and Design-Patterns 

<p align="center">
  <img src = "https://png.pngtree.com/png-vector/20221021/ourlarge/pngtree-tiny-cute-children-learning-coding-png-image_6334852.png" width=700 height=500>
</p>

## 🚩 Table of Contents
1. [Time Complexity](#time-complexity)
2. [Space Complexity](#space-complexity)
3. [Design Pattern](#design-pattern)
   1. [Creational Pattern](#creational-pattern)
      - Singleton Pattern
      - Factory Pattern 
      - Builder Pattern
      - Prototype Pattern
   2. [Structural Pattern](#structural-pattern)
      - Decorator design pattern
      - Adapter design pattern
      - Composite design pattern
      - Façade design pattern
      - Proxy design pattern
   4. [Behavioral Pattern](#behavioral-pattern)
      - Strategy design pattern
      - Observer design pattern
      - Mediator design pattern
      - Template Method design pattern
      
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
    10. [Heap](eap)
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

***

## 🧭Time Complexity:
 - https://en.wikipedia.org/wiki/Time_complexity
 - https://www.youtube.com/watch?v=D6xkbGLQesk&t=10s
 

## 🏠Space Complexity
- https://en.wikipedia.org/wiki/Space_complexity



## 🏁Design Pattern
  ### Creational Pattern:
   Creational design patterns are a category of design patterns that deal with object creation mechanisms, trying to create objects in a manner suitable to the situation. 
They aim to provide flexibility in the instantiation process while promoting code reuse and maintainability.

   - Singleton design pattern:

     https://javascriptpatterns.vercel.app/patterns/design-patterns/singleton-pattern

     ```js
        let counter = 0;
        
        // 1. Create an object containing the `getCount`, `increment`, and `decrement` method.
        const counterObject = {
          getCount: () => counter,
          increment: () => ++counter,
          decrement: () => --counter,
        };
        
        // 2. Freeze the object using the `Object.freeze` method, to ensure the object is not modifiable.
        const singletonCounter = Object.freeze(counterObject);
        
        // 3. Export the object as the `default` value to make it globally accessible.
        export default singletonCounter;
      ```
     
   - Factory design pattern:
     
     https://javascriptpatterns.vercel.app/patterns/design-patterns/factory-pattern

     Not really a pattern: In JavaScript, the factory pattern isn't much more than a function that returns an object without using the new keyword. ES6 arrow functions allow us to create small factory functions that implicitly return an object each time. However, in many cases it may be more memory efficient to create new instances instead of new objects each time.

     ```js
     class User {
        constructor(firstName, lastName, email) {
          this.firstName = firstName;
          this.lastName = lastName;
          this.email = email;
        }
      
        async getPosts() {
          const posts = await fetch(`https://my.cms.com/posts/user/${this.id}`);
          return posts;
        }
     }
    
      const user1 = new User({
        firstName: "John",
        lastName: "Doe",
        email: "john@doe.com",
      });
      
      const user2 = new User({
        firstName: "Jane",
        lastName: "Doe",
        email: "jane@doe.com",
      });
     ```


      
     
     
   - Builder design pattern:
     
   - Prototype Pattern:

     
  ### Structural Pattern:
   - Decorator design pattern:
     
   - Adapter design pattern:
     
   - Composite design pattern:
     
   - Façade design pattern:
     
   - Proxy design pattern:
     
  ### Behavioral Pattern:
   - Strategy design pattern:
     
   - Observer design pattern:
     
   - Mediator design pattern:
     
   - Command design pattern:
     
   - Template Method design pattern:


## ⭐Data Structure:

### Array:


## 🤖Algorithm


## 📜References


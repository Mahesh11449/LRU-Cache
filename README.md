# LRU Cache Implementation in Java 🚀

## About the Project

This project implements a **Least Recently Used (LRU) Cache** in Java using a combination of **HashMap** and **Circular Doubly Linked List**. The cache supports efficient insertion, retrieval, and eviction operations while maintaining constant-time performance.

---

## Key Features ✨

* O(1) time complexity for 'get()' and 'put()'
* Automatic removal of least recently used entries
* Efficient cache management using HashMap and CDLL
* Optimized memory utilization
* Custom implementation without built-in cache libraries

---

## Tech Stack 🛠️

* Java
* HashMap
* Circular Doubly Linked List
* Object-Oriented Programming

---

## Sample Input 📥

Capacity = 2

put(1,1)
put(2,2)
get(1)
put(3,3)
get(2)
put(4,4)
get(1)
get(3)
get(4)

---

## Sample Output 📤

1
-1
-1
3
4

---

## Performance ⚡

| Operation | Time Complexity |
| --------- | --------------- |
| get()     | O(1)            |
| put()     | O(1)            |

---

## Applications

* Database Caching
* Browser History Management
* API Response Caching
* Memory Management Systems

---

## Conclusion 🎯

This project demonstrates an efficient implementation of the LRU caching mechanism, combining fast data access with optimized memory management through O(1) cache operations.

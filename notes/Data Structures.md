
# Data Structures

* **Dynamic Arrays**

    - Implement the `vector` interface 
        + Using normal arrays & pointers
        + `insert`, `delete` etc.

    - Table doubling for amortized constant time?

* **Linked Lists**

    - Singly / Doubly
    - Implement with tail pointer (& without)

    - Insertion
        + At beginning
        + At n'th position

    - Deletion
        + At n'th position

    - Reversal

* **Stack**

    - Infix, Prefix, Postfix
        + Conversion
        + Evaluation

* **Queue**

    - Using linked lists / arrays
    
    - Interface
        + `push_back`, `pop_front`

---

* **Hash Table**
    
    - Collision Resolution
        + Chaining
        + Open Addressing

    - Table doubling

    - Interface
        + `insert(k, v)`, `find(k)`, `delete(k)`


## Trees

* Construction

* Implementation

    - Using arrays
        + `2*i`, `2*i + 1`

    - Pointers (linked list)
        + `struct Node`, `struct Node* left`, `right`

* Traversal

    - BFS
        + Level Order

    - DFS
        + Pre-order
        + In-order
        + Post-order

* **Binary Search Trees**

    - Interface
        + `insert`, `find`, `delete`
        + `min`, `max`

* **Heaps**

    - Min / Max

    - Priority Queue interface

    - `build_heap`
    - `heapify`
    - `heap_sort`

* **Self-balancing**

* **Trie**

* **Treaps**

* **Skip Lists**

* **Segment Trees**

## Graphs

* Implementation

    - Objects & Pointers
        + `struct Vertex`, `struct Edge`

    - Adjacency Matrix
        + When <code>e = O(v<sup>2</sup>)</code>

    - Adjacency List

    - Adjacency Map (dict)

    - Pros / Cons of each
        + Tradeoffs
        + When to use which?
        + [Skiena's Video](https://youtu.be/OiXxhDrFruw?t=3220)

* Traversal / Search
    - BFS
    - DFS
    - When to apply which?

    - DFS Based?
        + Cycle Detection
        + Topological Sorting
        + Strongly Connected Components
        + Bipartite Detection

* Shortest Paths
    - Dijkstra
    - Bellman Ford
    - Floyd Warshall

* Minimum Spanning Tree
    - Prim
    - Kruskal

* Max Flow
* Min Cut

* Advanced
    - [Speeding Up Dijkstra - MIT](https://youtube.com/watch?v=CHvQ3q_gJ7E)
    - [Algorithms on Graphs - Coursera](https://www.coursera.org/learn/algorithms-on-graphs)

    - A\*
    - Bi-directional
        + Dijkstra
        + A\*

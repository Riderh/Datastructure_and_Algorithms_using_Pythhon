# Datastructure_and_Algorithms_using_Python

**Data Structure:- A data Structure is a data organization, management, and storage format that enables efficient access and modification.**

**Following are the Data Structure**
- **Linked Lists:**
  consists of a sequence of elements, each of which contains a reference (or pointer) to the next element in the sequence. Unlike an array, which stores elements in contiguous memory locations, a linked list allows for dynamic memory allocation and efficient insertion and deletion of elements.

- **Stacks:**
  A stack is an ordered collection of elements where elements are added and removed from the same end, called the "top" of the stack. The last element added to the stack is the first one to be removed, a property known as "last in, first out" (LIFO).

- **Queues:**
  A queue, on the other hand, is an ordered collection of elements where elements are added to one end, called the "rear" of the queue, and removed from the other end, called the "front" of the queue. The first element added to the queue is the first one to be removed, a property known as "first in, first out" (FIFO).

- **Deques:**
  A deque, short for "double-ended queue," is a data structure that allows elements to be added or removed from both ends, unlike a stack or a queue, which only allow operations on one end. A deque can be visualized as a generalization of both a stack and a queue, where elements can be added to or removed from either the front or the back of the deque.


**Algorithm:- A set of steps or instruction for completing a task.**

**Hints:-**
- Clearly definned problem statement, input and output.
- The steps i Algorithm need to be very specific order.
- Steps also need distinct.
- Algorithm should produce a result.
- Algorithm should complete in a finite amount of time.
- correctness and efficiency (time complexity and space complexity).

**Following are 25 major Algorithm for fresher and experienced persons**

**Basics**
- **Huffman coding compression Algo:**
  Huffman coding is a lossless data compression algorithm that was developed by David A.The basic idea of Huffman coding is to use variable-length codes to represent symbols in a message, where the more frequently occurring symbols are assigned shorter codes and the less frequently occurring symbols are assigned longer codes. This allows for efficient compression of the message without losing any information.

- **Euclid's Algo:**
  is an efficient method for computing the greatest common divisor (GCD) of two integers (numbers), the largest number that divides them both without a remainder.

- **Union Find Algo:**
  Union-Find algorithm is a data structure that is used to solve problems that involve grouping elements into disjoint sets and performing certain operations on those sets. It is also known as Disjoint Set Union (DSU).


**Searching**
- **Linear Search:**
  Linear search, also known as sequential search, is a simple searching algorithm used to find a target value within a list or array. It sequentially checks each element in the list until it finds the target or reaches the end of the list.the algorithm may need to examine every element in the list before finding the target. Therefore, linear search is more suitable for small lists or unsorted lists

- **Binary Search:**
  Binary search is an efficient searching algorithm used to find a target value within a sorted list or array. It works by repeatedly dividing the search space in half until the target is found or the search space is exhausted.

- **Depth First Search(DFS):**
  Depth-first search (DFS) is a graph traversal algorithm that explores as far as possible along each branch before backtracking. It starts at a selected node (often called the "source" node) and explores as deep as possible along each adjacent node before backtracking.

- **Breath First Search(BFS):**
  Breadth-first search (BFS) is a graph traversal algorithm that explores all the vertices of a graph in breadth-first order, i.e., it visits all the vertices at the same level before moving on to the next level. It starts at a selected node (often called the "source" node) and explores all its neighbors before moving to the next level of neighbors.readth-first search ensures that all nodes at the current level are visited before moving to the next level. This way, it explores the graph in a layer-by-layer fashion, gradually moving away from the source node.


**Sorting**
- **Innsertion sort:**
  Insertion sort is a simple sorting algorithm that builds the final sorted array one item at a time. It works by repeatedly taking an element from the unsorted part of the array and inserting it into its correct position within the sorted part of the array.

- **Heap sort:**
  Heap sort is a comparison-based sorting algorithm that uses a binary heap data structure to sort elements. It divides the input array into a sorted and an unsorted region, and repeatedly extracts the maximum (for ascending order) or minimum (for descending order) element from the unsorted region and places it at the end of the sorted region. This process is repeated until the entire array is sorted.

- **Selection sort:**
  Selection sort is a simple comparison-based sorting algorithm. It works by repeatedly finding the minimum (or maximum) element from the unsorted part of the array and placing it at the beginning of the sorted part. This process is repeated until the entire array is sorted.

- **Merge sort:**
  Merge sort is a divide-and-conquer sorting algorithm. It works by dividing the input array into smaller halves, recursively sorting each half, and then merging the sorted halves to obtain a fully sorted array.

- **Quick sort:**
  Quick sort is a popular sorting algorithm that uses a divide-and-conquer approach. It works by selecting a pivot element from the array and partitioning the other elements into two sub-arrays, according to whether they are less than or greater than the pivot. The sub-arrays are then recursively sorted, and the results are combined to obtain the sorted array.

- **Counnting sort:**
   Counting sort is an integer sorting algorithm that operates by counting the number of occurrences of each distinct element in the input array. It requires knowledge of the range of input values and creates a count array to store the frequency of each element. Based on the count array, it then constructs a sorted output array.


**Graphs**
- **Kruskal's Algo:**
  Kruskal's algorithm is a greedy algorithm used to find a minimum spanning tree (MST) in a connected, weighted graph. A minimum spanning tree is a tree that spans all the vertices of the graph with the minimum possible total edge weight.At the end of the algorithm, the set of edges included in the minimum spanning tree forms the MST of the given graph.

- **Dijkstra's Algo:**
  Dijkstra's algorithm is a popular algorithm used to find the shortest path between a source vertex and all other vertices in a weighted graph. It operates by iteratively expanding the frontier of vertices until all vertices have been visited and their shortest distances have been determined.Additionally, you can keep track of the previous vertex for each visited vertex to reconstruct the shortest path from the source to any other vertex.

- **Bellmann Ford Algo:**
  The Bellman-Ford algorithm is a popular algorithm used to find the shortest path between a source vertex and all other vertices in a weighted graph. It is capable of handling graphs with negative edge weights, unlike Dijkstra's algorithm. However, it cannot handle graphs with negative cycles.

- **Floyd warshall Algo:**
  

- **Topological sort Algo:**


- **Flood Fill Algo:**


- **Lee Algo:**



**Array**
- **Kodane's Algo:**


- **Floy's cycle detection:**


- **KMP Algo:**


- **quick select Algo:**


- **Boyer more majority vote Algo:**



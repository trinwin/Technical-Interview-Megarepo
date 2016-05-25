# Algorithms

## Sorting
![sorting algorithm comparison](https://d262ilb51hltx0.cloudfront.net/max/800/1*w3vKy_JFKd50dixxFkpPPg.png)
* Mergesort

| Worst Case | Average Cast | Best Case                               | Worse Case (Space) |
|------------|--------------|-----------------------------------------|--------------------|
| O(n log n) | O(n log n)   | O(n log n) typical,O(n) natural variant | O(n)               |

* Quicksort

| Worst Case       | Average Cast | Best Case          | Worse Case (Space)       |
|------------------|--------------|--------------------|--------------------------|
| O(n<sup>2</sup>) | O(n log n)   | O(n log n) or O(n) | O(n) (naive) or O(log n) |

  * [Wikipedia Article on Quicksort](https://en.wikipedia.org/wiki/Quicksort)
  * "Typically, quicksort is significantly faster in practice than other Θ(nlogn) algorithms, because its inner loop can be efficiently implemented on most architectures, and in most real-world data, it is possible to make design choices which minimize the probability of requiring quadratic time."
  * Low memory requirement
* Heapsort
* BST Sort

## Searching / Graph Traversal
* Binary Search
* Breadth-First
* Depth-First
* Uniform-Cost/Dijkstra's
* A*
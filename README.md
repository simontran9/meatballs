<div align="center">
  <img width="120px" src="docs/meatballs.png">
  <h1>meatballs</h1>
  <p>data structures and algorithms library</p>
</div>

## Features

### Data structures

| abstract data type        | data structure(s)                                              |
|---------------------------|----------------------------------------------------------------|
| list                      | dynamic array, linked list (singly and doubly)                 |
| stack                     | dynamic array, linked list (singly)                            |
| queue                     | dynamic circular array, linked list (singly)                   |
| priority queue            | binary heap (max and min)                                      |
| map and set               | hash table (chaining and linear probing open addressing), trie |
| sorted map and sorted set | AVL tree, red-black tree, in-memory b-tree                     |
| disjoint set              | forest with path compression and union by rank heuristics      |
| graph                     | adjacency list, adjacency matrix                               |

> [!WARNING]  
> Abstract data types were not implemented with thread safety in mind.

### Algorithms

*coming soon...*

| Problem           | Algorithms                                                                                                        |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| searching                    | linear search, binary search                                                                                      |
| sorting                      | bubble sort, selection sort, insertion sort, merge sort, quicksort, heapsort                                      |
| graph traversal              | breadth-first search, depth-first search                                                                          |
| topological sort             | kahn's algorithm, depth-first search & linked list algorithm                                                      |
| strongly connected component | tarjan's algorithm, kosajaru's algorithm                                                                          |
| shortest path                | dijkstra's algorithm, bellman-ford algorithm, floyd-warshall algorithm, algorithm for a DAG                                  |
| minimum spanning tree        | kruskal's algorithm, prim's algorithm                                                                             |
| data compression             | huffman coding                                                                                                    |
| maximum flow                 | ford-fulkerson algorithm                                                                                          |
| stable matching              | gale-shapley algorithm                                                                                            |
| string-matching              | naive algorithm, knuth-moris-pratt algorithm, boyer-moore algorithm, aho-corasick algorithm, rabin-karp algorithm |

## Installation (static linking)

**Requirements**

- [C compiler](https://gcc.gnu.org/)
- [GNU Make](https://www.gnu.org/software/make/)

**Steps**

## Usage

See `docs/` for the particular available methods


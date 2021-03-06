# Algorithms in [Algorithm Design](https://www.amazon.com/Algorithm-Design-Kleinberg-published-Addison-Wesley/dp/B00E31S1LW/ref=sr_1_5?ie=UTF8&qid=1537642967&sr=8-5&keywords=Algorithm+Design)
## Summary
Personal implementation of Algorithm Design (*Jon Kleinberg and Éva Tardos*, 1st Edition, ISBN: 9780321295354) in Java. 
### Introduction
* *[Gale-Shapley](src/GaleShapleyAlgorithm.java)* - for Stable Matching Problem. Section 1.1, 9/6/2018
### Graphs
* *[Adjacency List](src/AdjacencyList.java)* - a way to represent graph, support the implement of BFS and DFS. 9/22/2018
* *[Breadth-First Search](src/BreadthFirstSearch.java)* - BFS for graph traversal. Section 3.3, 9/22/2018
* *[Depth-First Search](src/DepthFirstSearch.java)* - DFS for graph traversal. Section 3.3, 9/22/2018
* *[Find Topological Ordering](src/FindTopologicalOrdering.java)*  - show the topological ordering of a DAG. Section 3.6, 9/24/2018
* *[Bipartite Graph](src/BipartiteGraph.java)*  - generate, label, and test a bipartite graph. To help the implementation of the Bipartite Matching Problem. Section 3.4, 11/14/2018
### Greedy Algorithm
* *[Interval Scheduling](src/IntervalScheduling.java)* - interval scheduling problem. Section 4.1, 10/5/2018
* *[Interval Partitioning](src/IntervalPartitioning.java)* - interval partitioning problem (interval coloring problem). Section 4.1, 10/5/2018
* *[Minimizing Lateness](src/MinimizingLateness.java)* - scheduling to minimize lateness. Section 4.2, 10/5/2018
* *[Dijkstra's Algorithm](src/DijkstrasAlgorithm.java)* - single-pair shortest path problem. Section 4.4, 10/7/2018
* *[Prim's Algorithm](src/PrimsAlgorithm.java)* - minimum spanning tree problem. Section 4.5, 10/8/2018
* *[Union-Find Data Structure](src/UnionFind.java)* - help to implement Kruskal's Algorithm. Section 4.6, 10/8/2018
* *[Kruskal's Algorithm](src/KruskalsAlgorithm.java)* - another algorithm to solve minimum spanning tree problem. Section 4.6, 10/8/2018
### Dynamic Programming
* *[Weighted Interval Scheduling](src/WeightedIntervalScheduling.java)* - a version of interval scheduling problem with weight. Section 6.1, 11/3/2018
* *[Segmented Least Squares](src/SegmentedLeastSquares.java)* - segmented least squares problem. Section 6.3, 11/3/2018
* *[Knapsack Problem](src/Knapsack.java)* - a pseudo-polynomial time algorithm for Knapsack Problem. Section 6.4, 11/4/2018
* *[Sequence Alignment Problem](src/SequenceAlignment.java)* - an algorithm for Sequence Alignment Problem. Section 6.6, 11/4/2018
* *[Bellman-Ford Algorithm](src/BellmanFordAlgorithm.java)* - an algorithm for shortest path problem (with negative edges). Section 6.8, 11/10/2018
### Network Flow
* *[Ford-Fulkerson Algorithm](src/FordFulkersonAlgorithm.java)* - find max flow in graph. Section 7.1, 11/11/2018.  
Update: two versions with improved time complexity by shortest augmenting path or capacity scaling. Section 7.3, 11/14/2018.
* *[Bipartite Matching](src/BipartiteMatching.java)* - use max flow to find matching in a bipartite graph. Section 7.5, 11/15/2018. 

# Others
personal implementation of some useful algorithms and data structure.
* *[Trie Data Structure](cpp/Trie/Trie.cpp)* - use trie to speedup looking up word and finding prefixes. C++, 3/22/2019

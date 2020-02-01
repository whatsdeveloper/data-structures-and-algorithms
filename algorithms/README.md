# Algorithms

An algorithm is an unambiguous specification of how to solve a class of problems. It is
a set of rules that precisely define a sequence of operations.

`B` - Beginner, `A` - Advanced

## Algorithms by Topic

- **Math**
  - `B` [Bit Manipulation](math/bits) - set/get/update/clear bits, multiplication/division by two, make negative etc.
  - `B` [Factorial](math/factorial)
  - `B` [Fibonacci Number](math/fibonacci) - classic and closed-form versions
  - `B` [Primality Test](math/primality-test) (trial division method)
  - `B` [Euclidean Algorithm](math/euclidean-algorithm) - calculate the Greatest Common Divisor (GCD)
  - `B` [Least Common Multiple](math/least-common-multiple) (LCM)
  - `B` [Sieve of Eratosthenes](math/sieve-of-eratosthenes) - finding all prime numbers up to any given limit
  - `B` [Is Power of Two](math/is-power-of-two) - check if the number is power of two (naive and bitwise algorithms)
  - `B` [Pascal's Triangle](math/pascal-triangle)
  - `B` [Complex Number](math/complex-number) - complex numbers and basic operations with them
  - `B` [Radian & Degree](math/radian) - radians to degree and backwards conversion
  - `B` [Fast Powering](math/fast-powering)
  - `A` [Integer Partition](math/integer-partition)
  - `A` [Square Root](math/square-root) - Newton's method
  - `A` [Liu Hui π Algorithm](math/liu-hui) - approximate π calculations based on N-gons
  - `A` [Discrete Fourier Transform](math/fourier-transform) - decompose a function of time (a signal) into the frequencies that make it up
- **Sets**
  - `B` [Cartesian Product](sets/cartesian-product) - product of multiple sets
  - `B` [Fisher–Yates Shuffle](sets/fisher-yates) - random permutation of a finite sequence
  - `A` [Power Set](sets/power-set) - all subsets of a set (bitwise and backtracking solutions)
  - `A` [Permutations](sets/permutations) (with and without repetitions)
  - `A` [Combinations](sets/combinations) (with and without repetitions)
  - `A` [Longest Common Subsequence](sets/longest-common-subsequence) (LCS)
  - `A` [Longest Increasing Subsequence](sets/longest-increasing-subsequence)
  - `A` [Shortest Common Supersequence](sets/shortest-common-supersequence) (SCS)
  - `A` [Knapsack Problem](sets/knapsack-problem) - "0/1" and "Unbound" ones
  - `A` [Maximum Subarray](sets/maximum-subarray) - "Brute Force" and "Dynamic Programming" (Kadane's) versions
  - `A` [Combination Sum](sets/combination-sum) - find all combinations that form specific sum
- **Strings**
  - `B` [Hamming Distance](string/hamming-distance) - number of positions at which the symbols are different
  - `A` [Levenshtein Distance](string/levenshtein-distance) - minimum edit distance between two sequences
  - `A` [Knuth–Morris–Pratt Algorithm](string/knuth-morris-pratt) (KMP Algorithm) - substring search (pattern matching)
  - `A` [Z Algorithm](string/z-algorithm) - substring search (pattern matching)
  - `A` [Rabin Karp Algorithm](string/rabin-karp) - substring search
  - `A` [Longest Common Substring](string/longest-common-substring)
  - `A` [Regular Expression Matching](string/regular-expression-matching)
- **Searches**
  - `B` [Linear Search](search/linear-search)
  - `B` [Jump Search](search/jump-search) (or Block Search) - search in sorted array
  - `B` [Binary Search](search/binary-search) - search in sorted array
  - `B` [Interpolation Search](search/interpolation-search) - search in uniformly distributed sorted array
- **Sorting**
  - `B` [Bubble Sort](sorting/bubble-sort)
  - `B` [Selection Sort](sorting/selection-sort)
  - `B` [Insertion Sort](sorting/insertion-sort)
  - `B` [Heap Sort](sorting/heap-sort)
  - `B` [Merge Sort](sorting/merge-sort)
  - `B` [Quicksort](sorting/quick-sort) - in-place and non-in-place implementations
  - `B` [Shellsort](sorting/shell-sort)
  - `B` [Counting Sort](sorting/counting-sort)
  - `B` [Radix Sort](sorting/radix-sort)
- **Linked Lists**
  - `B` [Straight Traversal](linked-list/traversal)
  - `B` [Reverse Traversal](linked-list/reverse-traversal)
- **Trees**
  - `B` [Depth-First Search](tree/depth-first-search) (DFS)
  - `B` [Breadth-First Search](tree/breadth-first-search) (BFS)
- **Graphs**
  - `B` [Depth-First Search](graph/depth-first-search) (DFS)
  - `B` [Breadth-First Search](graph/breadth-first-search) (BFS)
  - `B` [Kruskal’s Algorithm](graph/kruskal) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  - `A` [Dijkstra Algorithm](graph/dijkstra) - finding shortest paths to all graph vertices from single vertex
  - `A` [Bellman-Ford Algorithm](graph/bellman-ford) - finding shortest paths to all graph vertices from single vertex
  - `A` [Floyd-Warshall Algorithm](graph/floyd-warshall) - find shortest paths between all pairs of vertices
  - `A` [Detect Cycle](graph/detect-cycle) - for both directed and undirected graphs (DFS and Disjoint Set based versions)
  - `A` [Prim’s Algorithm](graph/prim) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  - `A` [Topological Sorting](graph/topological-sorting) - DFS method
  - `A` [Articulation Points](graph/articulation-points) - Tarjan's algorithm (DFS based)
  - `A` [Bridges](graph/bridges) - DFS based algorithm
  - `A` [Eulerian Path and Eulerian Circuit](graph/eulerian-path) - Fleury's algorithm - Visit every edge exactly once
  - `A` [Hamiltonian Cycle](graph/hamiltonian-cycle) - Visit every vertex exactly once
  - `A` [Strongly Connected Components](graph/strongly-connected-components) - Kosaraju's algorithm
  - `A` [Travelling Salesman Problem](graph/travelling-salesman) - shortest possible route that visits each city and returns to the origin city
- **Cryptography**
  - `B` [Polynomial Hash](cryptography/polynomial-hash) - rolling hash function based on polynomial
- **Machine Learning**
  - `B` [NanoNeuron](https://github.com/trekhleb/nano-neuron) - 7 simple JS functions that illustrate how machines can actually learn (forward/backward propagation)
- **Uncategorized**
  - `B` [Tower of Hanoi](uncategorized/hanoi-tower)
  - `B` [Square Matrix Rotation](uncategorized/square-matrix-rotation) - in-place algorithm
  - `B` [Jump Game](uncategorized/jump-game) - backtracking, dynamic programming (top-down + bottom-up) and greedy examples
  - `B` [Unique Paths](uncategorized/unique-paths) - backtracking, dynamic programming and Pascal's Triangle based examples
  - `B` [Rain Terraces](uncategorized/rain-terraces) - trapping rain water problem (dynamic programming and brute force versions)
  - `B` [Recursive Staircase](uncategorized/recursive-staircase) - count the number of ways to reach to the top (4 solutions)
  - `A` [N-Queens Problem](uncategorized/n-queens)
  - `A` [Knight's Tour](uncategorized/knight-tour)

## Algorithms by Paradigm

An algorithmic paradigm is a generic method or approach which underlies the design of a class
of algorithms. It is an abstraction higher than the notion of an algorithm, just as an
algorithm is an abstraction higher than a computer program.

- **Brute Force** - look at all the possibilities and selects the best solution
  - `B` [Linear Search](search/linear-search)
  - `B` [Rain Terraces](uncategorized/rain-terraces) - trapping rain water problem
  - `B` [Recursive Staircase](uncategorized/recursive-staircase) - count the number of ways to reach to the top
  - `A` [Maximum Subarray](sets/maximum-subarray)
  - `A` [Travelling Salesman Problem](graph/travelling-salesman) - shortest possible route that visits each city and returns to the origin city
  - `A` [Discrete Fourier Transform](math/fourier-transform) - decompose a function of time (a signal) into the frequencies that make it up
- **Greedy** - choose the best option at the current time, without any consideration for the future
  - `B` [Jump Game](uncategorized/jump-game)
  - `A` [Unbound Knapsack Problem](sets/knapsack-problem)
  - `A` [Dijkstra Algorithm](graph/dijkstra) - finding shortest path to all graph vertices
  - `A` [Prim’s Algorithm](graph/prim) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  - `A` [Kruskal’s Algorithm](graph/kruskal) - finding Minimum Spanning Tree (MST) for weighted undirected graph
- **Divide and Conquer** - divide the problem into smaller parts and then solve those parts
  - `B` [Binary Search](search/binary-search)
  - `B` [Tower of Hanoi](uncategorized/hanoi-tower)
  - `B` [Pascal's Triangle](math/pascal-triangle)
  - `B` [Euclidean Algorithm](math/euclidean-algorithm) - calculate the Greatest Common Divisor (GCD)
  - `B` [Merge Sort](sorting/merge-sort)
  - `B` [Quicksort](sorting/quick-sort)
  - `B` [Tree Depth-First Search](tree/depth-first-search) (DFS)
  - `B` [Graph Depth-First Search](graph/depth-first-search) (DFS)
  - `B` [Jump Game](uncategorized/jump-game)
  - `B` [Fast Powering](math/fast-powering)
  - `A` [Permutations](sets/permutations) (with and without repetitions)
  - `A` [Combinations](sets/combinations) (with and without repetitions)
- **Dynamic Programming** - build up a solution using previously found sub-solutions
  - `B` [Fibonacci Number](math/fibonacci)
  - `B` [Jump Game](uncategorized/jump-game)
  - `B` [Unique Paths](uncategorized/unique-paths)
  - `B` [Rain Terraces](uncategorized/rain-terraces) - trapping rain water problem
  - `B` [Recursive Staircase](uncategorized/recursive-staircase) - count the number of ways to reach to the top
  - `A` [Levenshtein Distance](string/levenshtein-distance) - minimum edit distance between two sequences
  - `A` [Longest Common Subsequence](sets/longest-common-subsequence) (LCS)
  - `A` [Longest Common Substring](string/longest-common-substring)
  - `A` [Longest Increasing Subsequence](sets/longest-increasing-subsequence)
  - `A` [Shortest Common Supersequence](sets/shortest-common-supersequence)
  - `A` [0/1 Knapsack Problem](sets/knapsack-problem)
  - `A` [Integer Partition](math/integer-partition)
  - `A` [Maximum Subarray](sets/maximum-subarray)
  - `A` [Bellman-Ford Algorithm](graph/bellman-ford) - finding shortest path to all graph vertices
  - `A` [Floyd-Warshall Algorithm](graph/floyd-warshall) - find shortest paths between all pairs of vertices
  - `A` [Regular Expression Matching](string/regular-expression-matching)
- **Backtracking** - similarly to brute force, try to generate all possible solutions, but each time you generate next solution you test
  if it satisfies all conditions, and only then continue generating subsequent solutions. Otherwise, backtrack, and go on a
  different path of finding a solution. Normally the DFS traversal of state-space is being used.
  - `B` [Jump Game](uncategorized/jump-game)
  - `B` [Unique Paths](uncategorized/unique-paths)
  - `B` [Power Set](sets/power-set) - all subsets of a set
  - `A` [Hamiltonian Cycle](graph/hamiltonian-cycle) - Visit every vertex exactly once
  - `A` [N-Queens Problem](uncategorized/n-queens)
  - `A` [Knight's Tour](uncategorized/knight-tour)
  - `A` [Combination Sum](sets/combination-sum) - find all combinations that form specific sum
- **Branch & Bound** - remember the lowest-cost solution found at each stage of the backtracking
  search, and use the cost of the lowest-cost solution found so far as a lower bound on the cost of
  a least-cost solution to the problem, in order to discard partial solutions with costs larger than the
  lowest-cost solution found so far. Normally BFS traversal in combination with DFS traversal of state-space
  tree is being used.

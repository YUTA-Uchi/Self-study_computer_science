# Self-study_computer_science
for self-studying computer science, I made a memo, link page.

# ありがたき指針
ありがたいことに、CSの分野は独学しようとする人が多いのか、よい文献、サイト、curriculaが多い。とりあえず目についた体系的なのを張り付けてく。  
どうやらACM（The Association for Computing Machinery)とIEEE（The Institute of Electrical and Electronics Engineers)は10年ごとにカリキュラを改訂しているらしく、下記のPDFもその最中？のものらしいのだが、詳細な機微は初学者にはわからないのでガイドマップとして使わせてもらう。  
[ACMの2023年版コンピューターサイエンスカリキュラ](https://www.google.co.jp/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwixoKOOovGJAxVJklYBHaTFHU0QFnoECA0QAQ&url=https%3A%2F%2Fcsed.acm.org%2Fwp-content%2Fuploads%2F2023%2F03%2FVersion-Beta-v2.pdf&usg=AOvVaw1iHARdm_1bLe8iDUZA88gS&opi=89978449)  
[IEEEの2023年版コンピューターサイエンスカリキュラ](https://www.google.co.jp/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwixoKOOovGJAxVJklYBHaTFHU0QFnoECB8QAQ&url=https%3A%2F%2Fieeecs-media.computer.org%2Fmedia%2Feducation%2Freports%2FCS2023.pdf&usg=AOvVaw2JZq4qwIhl35VDcM8Zb68W&opi=89978449)  
[self-study CSみたいな検索で上位に引っかかったサイトの日本語訳](https://github.com/ralphplumley/TeachYourselfCS-JP/blob/main/%E6%97%A5%E6%9C%AC%E8%AA%9E.md)  
[おなじみ、CS50(日本語版）](https://cs50.jp/)  

## The Body of Knowledge
Algorithms and Complexity (AL)アルゴリズムと複雑性  
Architecture and Organization (AR)アーキテクチャと機構  
Artificial Intelligence (AI)人工知能  
Data Management (DM)データ管理  
Foundations of Programming Languagesプログラミング言語の基礎 (FPL)  
Graphics and Interactive Techniques (GIT)グラフィック・インタラクティブ技術  
Human-Computer Interaction (HCI)ヒューマン・コンピュータ　インタラクティブ  
Mathematical and Statistical Foundations (MSF) 数学・統計学的基礎 
Networking and Communication (NC)ネットワークコミュニケーション  
Operating Systems (OS)オペレーティングシステム  
Parallel and Distributed Computing (PDC)並行・分散コンピューティング  
Security (SEC)セキュリティ  
Society, Ethics and Professionalism (SEP)社会、倫理、プロ規範  
Software Development Fundamentals (SDF)ソフトウェア開発の基本  
Software Engineering (SE)ソフトウェアエンジニアリング  
Specialized Platform Development (SPD)特定のプラットフォームでの開発  
Systems Fundamentals (SF)システムの基本  

# Algorithms and Complexity (AL)アルゴリズムと複雑性  
## Fundamental Data Structures and Algorithms
### 必須知識
●  Abstract Data Types (ADTs) including Bag, Collection, Dictionary, List, and Set properties[cross-reference SDF/Fundamental Data Structures]  
●  Arrays: single and multi-dimensional  
  ○  Linear and Binary Search  
●  Cryptography (e.g. SHA-256, RSA) [crosslist: SEC/Cryptography]  
●  Graphs [cross-reference: MF/Graphs and Trees]  
  ○  (un)directed, (a)cyclic, (un)connected, and (un)weighted○  Adjacency List and Matrix representations  
●  Graph Algorithms  
  ○  Breadth-First Search  
    ■  Connectivity, Shortest-Path  
  ○  Depth-First Search  
    ■  Acyclicity, Connectivity, Transitive Closure, Topological Sort  
  ○  Hamiltonian Circuit  
  ○  Minimal Spanning Tree  
    ■  Prim’s and Kruskal’s algorithms  
  ○  Shortest-Path  
    ■  Bellman-Ford,  
    ■  Dijkstrat’s/Uniform-Cost,  
    ■  Floyd-Warshall  
  ○  Transitive Closure: Warshall’s Algorithm  
●  Hash Tables / Maps○  Collision resolution: Linear/Quadratic Probing, Chaining, and Rehashing  
●  Linked Lists: single, doubly linked, and circular  
●  Objects [cross-reference PL/Object-Oriented Programming]  
●  Queues, Priority Queues, and Dequeues  
●  Records/Structs and Tuples  
●  Stacks  
●  Strings  
  ○  String Matching: (Boyer-Moore),  
●  Sorting Algorithms:  
  ○ O(n2) Selection, Insertion  
  ○ O(n log n) Quicksort, Merge, and Heap  
  ○ O(n) Fast-Sorting: Bucket and Radix  
  ○ Lexicographical Ordering  
  ○  Partial Ordering  
  ○  Topological Ordering  
●  Trees  
  ○  Binary, N-ary, Search, Balanced, and Heaps  
  ○  Depth-First, Bread-First, Best-First, Backtracking search  
  ○  Balancing approaches (e.g., for AVL, Red-Black, 2-3, or B trees)  
  ○  Huffman Coding  
●  Differential Privacy  
●  Basic Linear Algebra (e.g., Strassen’s Matrix Multiplication)  
●  Invariants (in: loops, search algorithms, etc.)  
### あるといい知識
  ○  Consensus Algorithms (e.g. Blockchain)  
  ○  Geometric Algorithms (e.g., Graham Scan for Convex Hull)  
  ○  Linear Programming (e.g., Simplex algorithm)  
  ○  Approximation algorithms (e.g., for Knapsack, Traveling Salesperson)  
  ○  Randomized Algorithms (e.g. MaxCut, Balls and Bins)  
  ○  Computational Geometry (e.g. Closest Pair, Convex Hull)  
  ○  Branch and Bound  
### 発展的選択知識
●  Quantum Algorithms (e.g., Deutsch-Jozsa, Bernstein-Vazirani, Simon’s, Shor’s, Grover’s)  
●  Signal Processing (e.g. Fast Fourier Transform and Convolution)  
●  Cryptographic Hashing (e.g. Rabin’s Algorithm (Digital Fingerprint)  
●  Evolutionary Algorithms (e.g., Genetic Algorithms) [crosslist: Artificial Intelligence]  

## Algorithmic Strategies
### 必須知識
●  Algorithmic Strategy  
●  Approximation [cross-reference AL/Complexity Analysis]  
  ○  Polynomial approximation  
●  Backtracking [crosslist: Artificial Intelligence]  
●  Branch and Bound [cross-reference Artificial Intelligence]  
●  Brute-Force/Exhaustive Search○  Selection Sort, Traveling Salesman, Knapsack  
●  Consensus algorithms [cross-reference SEC/Cryptography]  
  ○  Blockchain  
●  Decrease-and-Conquer  
  ○  Insertion sort, Depth and Breadth-First search, Topological sort  
●  Divide-and-Conquer  
  ○  Binary Search, Quicksort, Mergesort, Strassen’s algorithm  
●  Dynamic Programming  
  ○  Warshall’s algorithm and Floyd’s algorithm  
●  Greedy  
  ○  Dijkstra’s Kruskal’s algorithms  
●  Heuristic: A*  [cross-reference Artificial Intelligence]  
●  Iterative  
  ○  Linear Search  
●  Parallel [crosslist: PD/Parallel Algorithms, Analysis, and Programming]  
  ○  Parallel Mergesort  
●  Randomized/Stochastic Algorithms  
  ○  MaxCut, Balls and Bins  
●  Recursive  
  ○  Depth-First, Breadth-First Search, Factorial  
●  Space and Time Tradeoff  
  ○  Hashing  
●  Transform-and-Conquer/Reduction  
  ○  2-3, AVL, Red-Black trees, Heapsort  

## Complexity Analysis
### 必須知識
●  Algorithmic Analysis  
●  Analysis Framework  
  ○  Average, Best, and Worst case performance  
  ○  Empirical and Relative (Order of Growth) Measurements  
  ○  Input Size and Primitive Operations  
  ○  Time and Space Efficiency  
●  Asymptotic complexity analysis  
  ○  Big O, Little O, Big Omega, and Big Theta  
  ○  Foundational Complexity/Efficiency classes  
    ■  Constant, Logarithmic, Linear, Log Linear, Quadratic, Cubic, Exponential, and Factorial  
●  Iterative and recursive algorithm analysis  
  ○  Recurrence Relations  
    ■  Master Theorem Analysis  
    ■  Substitution Analysis  
●  Tractability and Intractability  
  ○  P, NP and NP-C complexity classes  
    ■  Hamiltonian Circuit, Knapsack, and SAT problems  
●  Time and space trade-off in algorithms
### あるといい知識
●  Turing Machine-Based Models of Complexity  
  ○  P, NP, and NP-C complexity classes  
●  Space Complexity: Savitch’s Theorem, NSpace, PSpace  

## Computational Models
### 必須知識
●  Formal Languages and Grammars  
  ○  Chomsky Hierarchy  
  ○  Regular, Context-Free, Context-Sensitive, and Recursively Enumerable  
  ○  Regular expressions  
●  Formal Automata  
  ○  Finite State, Pushdown, Linear-Bounded, and Turing Machine  
  ○  Deterministic versus Nondeterministic and equivalencies  
  ○  Relations among formal automata, languages and grammars  
  ○  Decidability and limitations  
●  Decidability, Computability, Halting problem  
●  The Church-Turing Thesis  
●  The P, NP, and NPC complexity [crosslist: AL/Complexity Analysis]
### あるといい知識
●  Equivalent Models of Computation  
  ○  Turing Machine variations (e.g. multi-tape, non-deterministic)  
  ○  Lambda Calculus and Mu-Recursive Functions  
●  Pumping Lemmas (Finite State and Pushdown Automata)  
●  Decidability (Arithmetization and Diagonalization)  
●  Reducibility  
●  Time Complexity based on Turing Machine  
●  Space Complexity (e.g. PSPACE, Savitch’s Theorem)  
●  Quantum Computing  
●  Concurrent Systems (e.g., non-termination, non-determinism, “thread” interference)  

## Algorithms and Society
### 必須知識
●  Context-Aware Computing [crosslist: SEP/Social Context]  
●  Social, Ethical, and Secure Algorithms  
●  Differential Privacy  
●  Algorithmic Fairness [crosslist: AI?]  
●  Accountability/Transparency  

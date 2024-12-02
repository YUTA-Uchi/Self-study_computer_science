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
-	Abstract Data Types (ADTs) including Bag, Collection, Dictionary, List, and Set properties[cross-reference SDF/Fundamental Data Structures]  
-	Arrays: single and multi-dimensional  
	-	Linear and Binary Search  
-	Cryptography (e.g. SHA-256, RSA) [crosslist: SEC/Cryptography]  
-	Graphs [cross-reference: MF/Graphs and Trees]  
	-	(un)directed, (a)cyclic, (un)connected, and (un)weighted
	-	Adjacency List and Matrix representations  
-	Graph Algorithms  
	-	Breadth-First Search  
		-	Connectivity, Shortest-Path  
	-	Depth-First Search  
		-	Acyclicity, Connectivity, Transitive Closure, Topological Sort  
	-	Hamiltonian Circuit  
	-	Minimal Spanning Tree  
		-	Prim’s and Kruskal’s algorithms  
	-	Shortest-Path  
		-	Bellman-Ford,  
		-	Dijkstrat’s/Uniform-Cost,  
		-	Floyd-Warshall  
	-	Transitive Closure: Warshall’s Algorithm  
-	Hash Tables / Maps
	-	Collision resolution: Linear/Quadratic Probing, Chaining, and Rehashing  
-	Linked Lists: single, doubly linked, and circular  
-	Objects [cross-reference PL/Object-Oriented Programming]  
-	Queues, Priority Queues, and Dequeues  
-	Records/Structs and Tuples  
-	Stacks  
-	Strings  
	-	String Matching: (Boyer-Moore),  
-	Sorting Algorithms:  
	- O(n2) Selection, Insertion  
	- O(n log n) Quicksort, Merge, and Heap  
	- O(n) Fast-Sorting: Bucket and Radix  
	- Lexicographical Ordering  
	-	Partial Ordering  
	-	Topological Ordering  
-	Trees  
	-	Binary, N-ary, Search, Balanced, and Heaps  
	-	Depth-First, Bread-First, Best-First, Backtracking search  
	-	Balancing approaches (e.g., for AVL, Red-Black, 2-3, or B trees)  
	-	Huffman Coding  
-	Differential Privacy  
-	Basic Linear Algebra (e.g., Strassen’s Matrix Multiplication)  
-	Invariants (in: loops, search algorithms, etc.)  
### あるといい知識
-	Consensus Algorithms (e.g. Blockchain)  
-	Geometric Algorithms (e.g., Graham Scan for Convex Hull)  
-	Linear Programming (e.g., Simplex algorithm)  
-	Approximation algorithms (e.g., for Knapsack, Traveling Salesperson)  
-	Randomized Algorithms (e.g. MaxCut, Balls and Bins)  
-	Computational Geometry (e.g. Closest Pair, Convex Hull)  
-	Branch and Bound  
### 発展的選択知識
-	Quantum Algorithms (e.g., Deutsch-Jozsa, Bernstein-Vazirani, Simon’s, Shor’s, Grover’s)  
-	Signal Processing (e.g. Fast Fourier Transform and Convolution)  
-	Cryptographic Hashing (e.g. Rabin’s Algorithm (Digital Fingerprint)  
-	Evolutionary Algorithms (e.g., Genetic Algorithms) [crosslist: Artificial Intelligence]  

## Algorithmic Strategies
### 必須知識
-	Algorithmic Strategy  
-	Approximation [cross-reference AL/Complexity Analysis]  
	-	Polynomial approximation  
-	Backtracking [crosslist: Artificial Intelligence]  
-	Branch and Bound [cross-reference Artificial Intelligence]  
-	Brute-Force/Exhaustive Search
	-	Selection Sort, Traveling Salesman, Knapsack  
-	Consensus algorithms [cross-reference SEC/Cryptography]  
	-	Blockchain  
-	Decrease-and-Conquer  
	-	Insertion sort, Depth and Breadth-First search, Topological sort  
-	Divide-and-Conquer  
	-	Binary Search, Quicksort, Mergesort, Strassen’s algorithm  
-	Dynamic Programming  
	-	Warshall’s algorithm and Floyd’s algorithm  
-	Greedy  
	-	Dijkstra’s Kruskal’s algorithms  
-	Heuristic: A*	[cross-reference Artificial Intelligence]  
-	Iterative  
	-	Linear Search  
-	Parallel [crosslist: PD/Parallel Algorithms, Analysis, and Programming]  
	-	Parallel Mergesort  
-	Randomized/Stochastic Algorithms  
	-	MaxCut, Balls and Bins  
-	Recursive  
	-	Depth-First, Breadth-First Search, Factorial  
-	Space and Time Tradeoff  
	-	Hashing  
-	Transform-and-Conquer/Reduction  
	-	2-3, AVL, Red-Black trees, Heapsort  

## Complexity Analysis
### 必須知識
-	Algorithmic Analysis  
-	Analysis Framework  
	-	Average, Best, and Worst case performance  
	-	Empirical and Relative (Order of Growth) Measurements  
	-	Input Size and Primitive Operations  
	-	Time and Space Efficiency  
-	Asymptotic complexity analysis  
	-	Big O, Little O, Big Omega, and Big Theta  
	-	Foundational Complexity/Efficiency classes  
		-	Constant, Logarithmic, Linear, Log Linear, Quadratic, Cubic, Exponential, and Factorial  
-	Iterative and recursive algorithm analysis  
	-	Recurrence Relations  
		-	Master Theorem Analysis  
		-	Substitution Analysis  
-	Tractability and Intractability  
	-	P, NP and NP-C complexity classes  
		-	Hamiltonian Circuit, Knapsack, and SAT problems  
-	Time and space trade-off in algorithms
### あるといい知識
-	Turing Machine-Based Models of Complexity  
	-	P, NP, and NP-C complexity classes  
-	Space Complexity: Savitch’s Theorem, NSpace, PSpace  

## Computational Models
### 必須知識
-	Formal Languages and Grammars  
	-	Chomsky Hierarchy  
	-	Regular, Context-Free, Context-Sensitive, and Recursively Enumerable  
	-	Regular expressions  
-	Formal Automata  
	-	Finite State, Pushdown, Linear-Bounded, and Turing Machine  
	-	Deterministic versus Nondeterministic and equivalencies  
	-	Relations among formal automata, languages and grammars  
	-	Decidability and limitations  
-	Decidability, Computability, Halting problem  
-	The Church-Turing Thesis  
-	The P, NP, and NPC complexity [crosslist: AL/Complexity Analysis]
### あるといい知識
-	Equivalent Models of Computation  
	-	Turing Machine variations (e.g. multi-tape, non-deterministic)  
	-	Lambda Calculus and Mu-Recursive Functions  
-	Pumping Lemmas (Finite State and Pushdown Automata)  
-	Decidability (Arithmetization and Diagonalization)  
-	Reducibility  
-	Time Complexity based on Turing Machine  
-	Space Complexity (e.g. PSPACE, Savitch’s Theorem)  
-	Quantum Computing  
-	Concurrent Systems (e.g., non-termination, non-determinism, “thread” interference)  

## Algorithms and Society
### 必須知識
-	Context-Aware Computing [crosslist: SEP/Social Context]  
-	Social, Ethical, and Secure Algorithms  
-	Differential Privacy  
-	Algorithmic Fairness [crosslist: AI?]  
-	Accountability/Transparency  

# Architecture and Organization (AR) 
## AR/Digital Logic and Digital Systems
###　あるといい知識
 
-	Overview and history of computer architecture  
-	Combinational vs sequential logic/field programmable gate arrays (FPGAs)  
	-	Fundamental combinational  
	-	Sequential logic building block  
-	Functional hardware and software multi‐layer architecture  
-	Computer‐aided design tools that process hardware and architectural representations  
-	High‐level synthesis  
	-	Register transfer notation  
	-	Hardware description language (e.g. Verilog/VHDL/Chisel)  
-	System‐on‐chip (SoC) design flow  
-	Physical constraints  
	-	Gate delays  
	-	Fan‐in and fan‐out  
	-	Energy/power  
	-	Speed of light  
## AR/Machine‐Level Data Representation 
### 必須知識
 
-	Bits, bytes, and words  
-	Numeric data representation and number bases  
	-	Fixed‐point  
	-	Floating‐point  
-	Signed and twos‐complement representations  
-	Representation of non‐numeric data   
-	Representation of records and arrays  

## AR/Assembly Level Machine Organization
### 必須知識
 
-	von Neumann machine architecture  
-	Control unit; instruction fetch, decode, and execution  
-	Introduction to SIMD vs. MIMD and the Flynn taxonomy  
-	Shared memory multiprocessors/multicore organization  
### あるといい知識
 
-	Instruction set architecture (ISA) (e.g. x86, ARM and RISC‐V)  
	-	Instruction formats  
	-	Data manipulation, control, I/
-	
	-	Addressing modes  
	-	Machine language programming  
	-	Assembly language programming  
-	Subroutine call and return mechanisms (xref PL/language translation and execution)  
-	I/O and interrupts  
-	Heap, static,  stack and code segments  

## AR/Memory Hierarchy 
### 必須知識
 
-	Memory hierarchy: the importance of temporal and spatial locality  
-	Main memory organization and operations  
-	Persistent memory (e.g. SSD, standard disks)  
-	Latency, cycle time, bandwidth and interleaving  
-	Cache memories  
	-	Address mapping  
	-	Block size  
	-	Replacement and store policy  
-	Multiprocessor cache coherence  
-	Virtual memory (hardware support, cross‐reference OS/Virtual Memory)  
-	Fault handling and reliability  
-	Reliability (cross‐reference SF/Reliability through Redundancy)  
	-	Error coding  
	-	Data compression  
	-	Data integrity   
-	Non‐von Neumann Architectures  
	-	In‐Memory Processing (PIM)  

## AR/Interfacing and Communication
### 必須知識
 
-	I/O fundamentals  
	-	Handshaking and buffering  
	-	Programmed I/O  
	-	Interrupt‐driven I/O  
-	Interrupt structures: vectored and prioritized, interrupt acknowledgement  
-	External storage, physical organization and drives  
-	Buses fundamentals  
	-	Bus protocols  
	-	Arbitration  
	-	Direct‐memory access (DMA)  
-	Network‐on‐chip (NoC)  

## AR/Functional Organization
### あるといい知識
 
-	Implementation of simple datapaths, including instruction pipelining, hazard detection and resolution  
-	Control unit  
	-	Hardwired implementation  
	-	Microprogrammed realization  
-	Instruction pipelining  
-	Introduction to instruction‐level parallelism (ILP)  

## AR/Performance and Energy Efficiency
### あるといい知識
 
-	Performance‐energy evaluation (introduction): performance, power consumption, memory and communication costs  
-	Branch prediction, speculative execution, out‐of‐order execution, Tomasulo's algorithm  
-	Prefetching  
-	Enhancements for vector processors and GPUs  
-	Hardware support for Multithreading  
	-	Race conditions  
	-	Lock implementations  
	-	Point‐to‐point synchronization  
	-	Barrier implementation  
-	Scalability  
-	Alternative architectures, such as VLIW/EPIC, accelerators and other special‐purpose processors  
-	Dynamic voltage and frequency scaling (DVFS)  
-	Dark Silicon  

## AR/Heterogeneous Architectures
### あるといい知識
 
-	SIMD and MIMD architectures (e.g. General‐Purpose GPUs, TPUs and NPUs)  
-	Heterogeneous memory system  
	-	Shared memory versus distributed memory  
	-	Volatile vs non‐volatile memory  
	-	Coherence protocols  
-	Domain‐Specific Architectures (DSAs)  
	-	Machine Learning Accelerator  
	-	In‐networking computing  
	-	Embedded systems for emerging applications  
	-	Neuromorphic computing   
-	Packaging and integration solutions such as 3DIC and Chiplets  

## AR/Quantum Architectures 
### あるといい知識
 
-	Principles  
	-	The wave‐particle duality principle  
	-	The uncertainty principle in the double‐slit experiment  
	-	What is a Qubit? Superposition and measurement. Photons as qubits.  
	-	Systems of two qubits. Entanglement. Bell states. The No‐Signaling theorem.  
-	Axioms of QM: superposition principle, measurement axiom, unitary evolution  
-	Single qubit gates for the circuit model of quantum computation: X, Z, H.  
-	Two qubit gates and tensor products. Working with matrices.  
-	The No‐Cloning Theorem. The Quantum Teleportation protocol.  
-	Algorithms  
	-	Simple quantum algorithms: Bernstein‐Vazirani, Simon’s algorithm.  
	-	Implementing Deutsch‐Josza with Mach‐Zehnder Interferometers.  
	-	Quantum factoring (Shor’s Algorithm)  
	-	Quantum search (Grover’s Algorithm)  
-	Implementation aspects  
	-	The physical implementation of qubits (there are currently nine qubit modalities)  
	-	Classical control of a Quantum Processing Unit (QPU)  
	-	Error mitigation and control. NISQ and beyond.  
-	Emerging Applications  
	-	Post‐quantum encryption  
	-	The Quantum Internet  
	-	Adiabatic quantum computation (AQC) and quantum annealing  

# Artificial Intelligence (AI)
## AI/Fundamental Issues 
### 必須知識
 
-	Overview of AI problems, Examples of successful recent AI applications  
-	Definitions of agents with examples (e.g., reactive, deliberative)  
-	What is intelligent behavior?   
	-	The Turing test and its flaws  
	-	Multimodal input and output  
	-	Simulation of intelligent behavior  
	-	Rational versus non-rational reasoning  
-	Problem characteristics  
	-	Fully versus partially observable  
	-	Single versus multi-agent  
	-	Deterministic versus stochastic  
	-	Static versus dynamic  
	-	Discrete versus continuous  
-	Nature of agents  
	-	Autonomous, semi-autonomous, mixed-initiative autonomy  
	-	Reflexive, goal-based, and utility-based  
	-	Decision making under uncertainty and with incomplete information  
	-	The importance of perception and environmental interactions  
	-	Learning-based agents  
	-	Embodied agents  
		-	sensors, dynamics, effectors  
-	AI Applications, growth, and Impact (economic, societal, ethics)  

### あるといい知識
 
-	Additional depth on problem characteristics with examples 
-	Additional depth on nature of agents with examples  
-	Additional depth on AI Applications, growth, and Impact (economic, societal, ethics)  

## AI/Search
### 必須知識
 
-	State space representation of a problem   
	-	Specifying states, goals, and operators  
	-	Factoring states into representations (hypothesis spaces)  
	-	Problem solving by graph search  
		-	e.g., Graphs as a space, and tree traversals as exploration of that space  
		-	Dynamic construction of the graph (you’re not given it upfront)  
-	Uninformed graph search for problem solving  
	-	Breadth-first search  
	-	Depth-first search  
		-	With iterative deepening  
	-	Uniform cost search  
-	Heuristic graph search for problem solving  
	-	Heuristic construction and admissibility   
	-	Hill-climbing  
	-	Local minima and the search landscape  
		-	Local vs global solutions  
	-	Greedy best-first search  
	-	A* search   
-	Space and time complexities of graph search algorithms  

### あるといい知識
 
-	Bidirectional search  
-	Beam search  
-	Two-player adversarial games  
	-	Minimax search  
	-	Alpha-beta pruning  
		-	Ply cutoff   
-	Implementation of A* search

### 補足的知識
 
-	Understanding the search space  
	-	Constructing search trees  
	-	Dynamic search spaces  
	-	Combinatorial explosion of search space  
	-	Search space topology (ridges, saddle points, local minima, etc.)  
-	Local search and constraint satisfaction  
-	Tabu search  
-	Variations on A* (IDA*, SMA*, RBFS)  
-	Two-player adversarial games  
	-	The horizon effect  
	-	Opening playbooks / endgame solutions  
	-	What it means to “solve” a game (e.g., checkers)  
-	Implementation of minimax search, beam search  
-	Expectimax search (MDP-solving) and chance nodes  
-	Stochastic search  
	-	Simulated annealing  
	-	Genetic algorithms  
	-	Monte-Carlo tree search  

(中略)  

# Data Management (DM)
## The Role of Data
### 必須知識
 
-	The Data Life Cycle: Creation‐Processing‐Review/Reporting‐Retention/Retrieval‐Destruction.  
-	The social/legal aspects of data collections:  
	-	scale  
	-	data privacy  
	-	database privacy (compliance) by design  
	-	anonymity  
	-	ownership  
	-	reliability  
	-	intended and unintended applications  

## Core Database System Concepts
### 必須知識
 
-	Purpose and advantages of database systems  
-	Components of database systems  
-	Design of core DBMS functions (e.g., query mechanisms, transaction management, buffer management, access methods)  
-	Database architecture, data independence, and data abstraction  
-	Use of a declarative query language  
-	Transaction mgmt  
-	Normalization  
-	Approaches for managing large volumes of data (e.g., noSQL database systems, use of MapReduce).  
-	How to support CRUD‐only applications  
-	Distributed databases/cloud‐based systems  
-	Structured, semi‐structured, and unstructured databases  

## Data Modeling
### 必須知識
 
-	Data modeling  
-	Relational data model  

## Relational Databases
### 必須知識
 
-	Entity and referential integrity  
	-	Candidate key, superkeys  
-	Relational database design  

## Query Construction
### 必須知識
-	SQL Query Formation  

# Foundations of Programming Languages (FPL)
## FPL/Object-Oriented Programming 
### 必須知識
 
-	Object-oriented design  
	-	Decomposition into objects carrying state and having behavior  
	-	Class-hierarchy design for modeling  
-	Definition of classes: fields, methods, and constructors   
-	Subclasses, inheritance (including multiple inheritance), and method overriding   
-	Dynamic dispatch: definition of method-call  
-	Exception handling  
-	Object-oriented idioms for encapsulation  
	-	Privacy, data hiding, and visibility of class members  
	-	Interfaces revealing only method signatures  
	-	Abstract base classes, traits and mixins  
-	Dynamic vs static properties  
-	Composition vs inheritance  

## FPL/Functional Programming
### 必須知識

-	Lambda expressions and evaluation  
	-	Variable binding and scope rules  
	-	Parameter passing  
	-	Nested lambda expressions and reduction order 
-	Effect-free programming  
	-	Function calls have no side effects, facilitating compositional reasoning  
	-	Immutable variables and data copying vs. reduction  
	-	Use of recursion vs. loops vs. pipelining (map/reduce)  
-	Processing structured data (e.g., trees) via functions with cases for each data variant  
	-	Functions defined over compound data in terms of functions applied to the constituent pieces  
	-	Persistent data structures  
-	Using higher-order functions (taking, returning, and storing functions)  

## FPL/Scripting
### 必須知識

-	Divide, combine, conquer  
-	Concurrency  
-	Error/exception handling  
-	I/O redirection  
-	System commands  
-	Environment variables  
-	File test operators  
-	Data structures  
	-	Arrays and lists  
	-	Slices  
	-	List Comprehensions  
-	Regular expressions  
-	Dynamic typing  
-	Function declarations  
-	Processes and threads  
-	Code objects  

## FPL/Event-Driven and Reactive Programming 
### 必須知識

-	Procedural  programming  vs.  reactive  programming:  advantages  of  reactive programming in capturing events  
-	Components of reactive programming: event-source, event signals, listeners and dispatchers, event objects, adapters, event-handlers  
-	Behavior model of event-based programming  
-	Canonical uses such as GUIs, mobile devices, robots, servers  
-	Reactive programs as state transition system  

## FPL/Parallel and Distributed Computing
### 必須知識

-	Safety and liveness 
	-	Race conditions 
	-	Dependencies/preconditions 
	-	Fault models 
	-	Termination 
-	Programming models 
	-	Actor models 
	-	Procedural and reactive models 
	-	Synchronous/asynchronous programming models 
	-	Data parallelism 
-	Semantics 
	-	Commutativity 
	-	Ordering 
	-	Independence 
	-	Consistency 
	-	Atomicity 
	-	Consensus 
-	Execution control 
	-	Async await 
	-	Promises 
	-	Threads 
-	Communication and coordination 
	-	Message-passing 
	-	Shared memory 
	-	cobegin-coend 
	-	Monitors 
	-	Channels 
	-	Threads 
	-	Guards 

## FPL/Type Systems 
### 必須知識

-	A type as a set of values together with a set of operations  
	-	Primitive types (e.g., numbers, Booleans)  
	-	Compound types built from other types (e.g., records, unions, arrays, lists, functions, references) using set operations  
-	Association of types to variables, arguments, results, and fields  
-	Type safety as an aspect of program correctness [cross-reference:  FPL/Formal  Semantics]  
-	Type safety and errors caused by using values inconsistently given their intended types  

-	Statically-typed vs dynamically-typed programming languages 
-	Type equivalence: structural vs name equivalence 
-	Goals and limitations of static and dynamic typing  
	-	Detecting and eliminating errors as early as possible 
-	Generic  types  (parametric  polymorphism)  [cross-reference:    FPL/Formal    Semantics]  
	-	Definition  and  advantages  of  polymorphism:  parametric,  subtyping, overloading and coercion  
	-	Comparison of monomorphic and polymorphic types  
	-	Comparison  with  ad-hoc  polymorphism  (overloading)  and  subtype polymorphism  
	-	Generic parameters and typing  
	-	Use of generic libraries such as collections  
	-	Comparison  with  ad  hoc  polymorphism  (overloading)  and  subtype polymorphism  
	-	Prescriptive vs. descriptive polymorphism  
	-	Implementation models of polymorphic types  

## FPL/Language Translation and Execution 
### 必須知識

-	Interpretation  vs.  compilation  to  native  code  vs.  compilation to  portable intermediate representation  
-	Language translation pipeline: syntax analysis, parsing, optional type-checking, translation/code generation and optimization, linking, loading, execution  
	-	BNF and extended BNF representation of context-free grammar  
	-	Parse tree using a simple sentence such as arithmetic expression or if-then-else statement  
	-	Ambiguity in Parsing due to lack of precedence order and resolution  
	-	Execution as native code or within a virtual machine  
	-	Alternatives  like  dynamic  loading  and  dynamic  (or  "just-in-time")  code generation  
-	Control-flow diagrams using selection and iteration  
-	Data structures for translation, execution, translation and code mobility such as stack, heap, aliasing (sharing using pointers), indexed sequence and string  
-	Direct, indirect, and indexed access to memory location  
-	Runtime representation of data abstractions such as variables, arrays, vectors, records, pointer-based data elements such as linked-lists and trees, and objects  
-	Abstract low-level  machine with simple instruction, stack and heap  to explain translation and execution  
-	Run-time layout of memory: activation record (with various pointers), static data, call-stack,  heap  [cross   reference:   AR/Memory   System   Architecture   and   Organization, OS/Memory Management]  
	-	Translating selection and iterative constructs to control-flow diagrams  
	-	Translating control-flow diagrams to low level abstract code  
	-	Implementing loops, recursion, and tail calls  
	-	Translating function/procedure calls and return from calls, including different parameter passing mechanism using an abstract machine  
-	Memory management [cross reference: OS/Memory Management, FPL/Hardware Interface]  
	-	Low level allocation and accessing of high-level data structures such as basic data types, n-dimensional array, vector, record, and objects  
	-	Return from procedure as automatic deallocation mechanism for local data elements in the stack  
	-	Manual  memory  management:  allocating,  de-allocating,  and  reusing  heap memory  
	-	Automated  memory  management:  garbage  collection  as  an  automated technique using the notion of reachability  

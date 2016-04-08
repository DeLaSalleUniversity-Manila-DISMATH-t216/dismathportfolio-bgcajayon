# dismathportfolio-bgcajayon
## Week 1
##### This week we were introduced to the basics of dismath

* Propositions - declarative sentence. EITHER true or false

* Propositional Variables - denoted by letters

* Operators - Explains the interaction between Propositional Variables
  * 1.NEGATION: Usage NOT
  * 2.Conjunction: Usage AND
  * 3.DISJUNCTION: Usage OR
  * 4.EXCLUSIVE OR: Usage XOR
  * 5.CONDITIONAL: Usage IF,THEN
  * 6.BICONDITIONAL: Usage IFF
  
* Logical connectives - a set of propositions and operators which are assumed to be equivalent.

* Truth Table - A table for truth values for logical connectives

* Truth Value - Value of propositions

* Compound Propositions - Created from existing propositions using logical operators. 



## Week 2
##### This week we started going deep in dismath, AND IT IS VERY CONFUSING but deceptively entertaining.
  
##### Propositional equivalences  ( Apparently i can't or i just don't know how to input special characters)
* Testing for equivalence the only way we have so far to prove that two propositions are equivalent is a truth table.

* Logical Equivalences - these are laws that have already been proven.
  * 1. IDENTITY LAWS
  * 2. DOMINATION LAWS
  * 3. DOUBLE NEGATION LAWS
  * 4. COMMUTATIVE LAWS
  * 5. ASSOCIATIVE LAWS
  * 6. DISTRIBUTIVE LAWS
  * 7. DE MORGAN'S LAWS
  * 8. ABSORPTION LAWS
  * 9. NEGATION LAWS

## Week 3

##### This week we started seeing life in a very different way we're not sure if superman does exist or not.


* RULES OF INFERENCE - Establishes the validity of some relatively simple argument forms

  * 1. MODUS PONENS
  * 2. MODUS TOLLENS
  * 3. HYPOTHETICAL SYLLOGISM
  * 4. DISJUNCTIVE SYLLOGISM
  * 5. ADDITION
  * 6. SIMPLIFICATION
  * 7. CONJUNCTION
  * 8. Resolution

## Week 4

##### This week we started proving algebraic equations

##### METHODS OF PROOF
1. Direct Proof
2. Proof by Contraposition
3. Vacuous Proof
4. Trivial Proof
5. Proof by Contradiction

## Week 5

#### This week we had no classes during monday

#### We were then introduced to mathematical induction

#### MATHEMATICAL INDUCTION
##### a means of proving a theorem by showing that if it is true of any particular case, it is true of the next case in a series, and then showing that it is indeed true in one particular case.

 - We were given an example:
        - _P(1) P(2) P(3) P(k) P(k+1)_
    - Steps:
        1. Basis step: _P(1)_ is shown to be true
        2. Do the inductive step:
            "If _P(k+1)_ is true whenever _P(k)_ is true, then _P_ is true for all positive integer."
    - Example: Prove _P(n) = 1 + 2 + 3 + ... + n = n(n+1)/2_

## Week 6
* **SUMMATION**
    - The notation for sum of _a<sub>m</sub>, a<sub>m+1</sub>, ..., a<sub>n</sub>_ is _∑<sup>a</sup><sub>i=m </sub>a<sub>i</sub>_ where _i_ is the index of summation.


* **RECURSIVE/INDUCTIVE DEFINITION**
    - Basis step: Specify the value of the function at zero
    - Recursive step: Give a rule for finding its value at an integer from its values at smaller integers

* **RECURSIVE ALGORITHMS**
    - It solves a problem by reducing it to an instance of the same problem with smaller input.
        - Recall: <u>Algorithm</u> - finite set of precise instructions for performing a computation/solving a problem.
 integer.

##Week 7

* **INTRODUCTION TO SET THEORY**
    - A _set_ is an unordered collection of distinct objects, which may be anything (including other sets).
        - {a,b,c,d,e}
        </br>    ↳ *Set Notation:* curly braces with commas separating out the elements 
* **Empty Set**
</br>   ↳ { } = ∅
    - no elements
    * **Set Builder Notation**
    </br>    ↳ {x | some property x satisfies}

##### SET IDENTITIES TABLE
|  **LAW**  |  **IDENTITY**  |
| :------: | :-----------------------------: |
|  _Identity Laws_  |  A ⋂ U ≡ A  <br>  A ⋃ ∅ ≡ A  |
|  _Domination Laws_  |  A ⋃ U ≡ U  <br>  A ⋂ ∅ ≡ ∅  |
|  _Idempotent Laws_  |  A ⋃ A ≡ A  <br>  A ⋂ A ≡ A  |
|  _Complementation Law_  |  (A¯)‾ ≡ A  |
|  _Commutative Laws_  |  A ⋃ B ≡ B ⋃ A  <br>  A ⋂ B ≡ B ⋂ A  |
| _Associative Laws_  |  A ⋃ (B ⋃ C) ≡ (A ⋃ B) ⋃ C  <br>  A ⋂ (B ⋂ C) ≡ (A ⋂ B) ⋂ C  |
|  _Distributive Laws_  |  A ⋃ (B ⋂ C) ≡ (A ⋃ B) ⋂ (A ⋃ C) <br>  A ⋂ (B ⋃ C) ≡ (A ⋂ B) ⋃ (A ⋂ C)  |
|  _De Morgan's Laws_  |  (A ⋂ B)‾ ≡ A‾ ⋃ B‾  <br>  (A ⋃ B)‾ ≡ A‾ ⋂ B‾  |
|  _Absorption Laws_  |  A ⋃ (A ⋂ B) ≡ A  <br>  A ⋂ (A ⋃ B) ≡ A  |
|  _Complement Laws_  |  A ⋃ A‾ ≡ U  <br>  A ⋂ A‾ ≡ ∅  |

- **SUBSETS**: A set _S_ is a subset of a set _T_ (denotes S ⊆ T) if all elements of _S_ are also elements of _T_.
- **POWER SET**: A set of all subsets.
- **CARDINALITY**: The number of element it contains. If _S_ is a set, we denote its cardinality by writing |S|.
    - **Infinite Cardinalities**: alaph-null (0,1,2,3,...)

* **FUNCTIONS**
    - _A_ & _B_ are sets
    -  A function _f_ from _A_ to _B_ is an assignment of exactly one element of _B_ to each element of _A_.
    -  Functions are also called MAPPINGS or TRANSFORMATIONS.
        - f: A to B </br>
            ↳ A: domain </br>
            ↳ B: co-domain
        - **Range** - actually occuring values

* **IMAGE**
    - If _f(a) = b_, _b- is the image of _A_.
    - The range of _f_ is the set of all images of elements of _a_.

* **TYPES OF FUNCTIONS**
    - One - to - one Function (_Injection_)</br>
        ↳ functions that never assign the same value to two different domain elements.
    - Onto Function (_Surjective_)</br>
        ↳ functions have equal range & co-domain.
    - One - to - one Correspondence (_Bijection_)</br>
        ↳ function is both one - to - one and onto.

## Week 8:
- This week we started studying algorithims and the language of pseudocode, pseudocode provided to be a very convenient way to discuss algorithms for it can be understood by most people that are in STEM courses.
* **ALGORITHMS**
    - A finite set of precise instructions for performing a computation or for solving a problem.
    - **Properties of Algorithms**: </br>
        ⇾ _Input_ - has input values from a specified set </br>
        ⇾ _Output_ - solution to the problem </br>
        ⇾ _Definiteness_ - defined precisely </br>
        ⇾ _Correctness_ - produce the correct output values </br>
        ⇾ _Finiteness_ - produce the desired output </br>
        ⇾ _Effectiveness_ - perform exactly and in a finite amount of time </br>
        ⇾ _Generality_ - applicable for all problems of the desired form
* **PSEUDOCODE**
    - high - level desciption of an algorithm that uses the structural conventions of a programming language 
    - intended for human reading
    - **Preconditions** - describe valid input
    - **Postconditions** - conditions that the output should satisfy
 
   
    
    
### Week 9:
- Continuation of the previous week's discussion about algorithms

* **SEARCHING ALGORITHMS** </br>
    ↳ Problem of locating an algorithm in an ordered list
    - **Binary Search** - comparing the middle values of a list then repeated until the desired output is found.

* **SORTING ALGORITHMS** </br>
    ↳ Problem of assorting elements into increasing order
    - **Bubble Sort** - compares the first two elements then interchanging them if they are in the incorrect order.
    - **Insertion Sort** - compares the second element with the first and inserts it before the first element if it is less. Otherwise, it is inserted after the first element.

* **GREEDY ALGORITHMS** </br>
    ↳ Algorithms that make what seems to be the "best" choice at each step.

### Week 10:

* **Big-O Notation**
    - Let _f_ and _g_ be functions from R-R; _f(x)_ is _O(g(x))_ if there are constants _C_ and _k_ such that: </br>
        |f(x)| ≤ C|g(x)| </br>
    whenever _x > k_.

* **Big-Omega and Big-Theta Notation**
    - Big-O Notation does not provide a lowerbound for the size of f(x). </br>
        ↳ **Big-Omega** (Big-Ω) - lower bound </br>
        ↳ **Big-Theta** (Big-Θ) - both upper and lower bound
___

### Quiz 2
___

### Week 11: HOLY WEEK
___

### Week 12:

* **Graph Theory**
    - Easiest coverage for the quiz
    - _Degree_ - number of degrees at a node/vertex
    - _Handshaking Theory_ - 2e = ∑deg(v)
    - _Path_ - sequence of edges travelling from vertex to vertex along the edges
    - _Euler Circuit_ - passess through every edge and goes back to starting point
    - _Euler Path_ - simple path containing every edge of the graph
    - _Hamilton Path_ - passes through every vertex
    - _Hamilton Circuit_ - passes through every vertex then goes back to the starting point
    - _Matrices of Graphs_ - 1 for adjacent; 0 for non-adjacent
    - _Incidence of Matrices_ - Matric between vertices and edges
    - _Isomorphism of Graphs_ - "rubberband"

* **Planar Graph**
    - no edges cross in a graph
    - _Euler's Formula_ - regions = edges - vertices + 2
    - _Euler's Characteristic_ - ℵ = regions - |edges| + |vertices| = 2

* **Homeomorphic Graphs**
    - can be obtained from the same graph by a sequence of elementary subdivisions
        - _Elementary Subdivision_ - everything is planar graph
    - _Kuratowski's Theorem_ - nonplanar if and only if it contains a subgraph homeophobic to K<sub>3,3</sub> and K<sub>5</sub>
___

*** QUIZ 3 - Probably everyone's most highest quiz except for rain

*** Week 13:
- Last week of lessons before finals!

* **Graph Coloring**
    - assignment of a color to each vertex of the graph so that no two adjacent vertices are assigned the same color
    - _Four Color Theorem_ - the chromatic number of a planar graph is no greater than four

* **Trees**
    - connected undirected graph with no simple circuits
    - data structure that emulates a heirarchical tree structure with a set of linked notes
    - used to construct efficient algorithms for locating an item in a set
    - _Forest_ - multiple trees
    - _Rooted Tree_ - a tree in which one vertex has been designated as the root and every edge
        - leaves - nodes that do not have children
        - ancestors - nodes on top
        - descendants - children/grandchildren
    - _Subtree_
    - _M-ary tree_ - if every internal vertex has no more than m children
        - an m-ary tree with m = 2 is called a _binary tree_

* **Modeling Computation**
    - _Language and Grammars_
        - Grammars - used to generate the words of a language and to determine whether a word is in a language
        - Compiler - reads a program written in a source language and translate it into an equivalent program in a target language.
        - Formal Language - automatic translation of one language to another
            - well defined set of rules

* **Alphabet & String**
    - common way to talk about words, numbers, etc.

* **Automata Theory**
    - studies the law of computation
    - Finite Automata - simplest model of automata
        - initial state
        - final/acceptance state
        - dead/stuck state
        - transition

* **Lexical Analysis**
    - process where the stream of characters making up the source program into a sequence of "words" that make up the source code.

* **Finite State Machine**
    - finite-state automaton (FSA, plural: automata), or simply a state machine, is a mathematical model of computation used to design both computer programs and sequential logic circuits. It is conceived as an abstract machine that can be in one of a finite number of states.


dismathportfolio-bgcajayon created by Classroom for GitHub

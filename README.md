# Data-Structures-and-Algorithm-in-Python

_In daily life, we always go with that person who can complete the task in a short amount of time with efficiency and using fewer resources. The same things happen with Coding.Knowledge of data structures like Hash Tables, Trees, Tries, Graphs, and various algorithms goes a long way in solving these problems efficiently.Data Structures are a crucial part of several computer algorithms as they allow programmers to do data management efficiently. A wise selection of data structures can improve the performance of a computer program or algorithm in a more useful way. 1. Handling complexity: Increase in complexities in computer algorithms, the volume of data usage is rising; this can affect the execution of the application and can create remarkable areas of concern like processing speed, data search, and multiple requests. To counter these data structures are used.   2. Systematic memory use: Systematic application of data structure memory usage can be optimized, e.g., we can use linked list vs. arrays when we are not particular about the data size. When there is no longer use of memory, it can be cleared.   3. Ability to reuse: Once we have executed a particular data structure, we can reuse it in any distinct position. Implementation of data structures can be assembled into libraries that can be utilized by various clients.   4. Abstraction:  Data structure acts as the foundation of abstract data types; the data structure describes the physical form of Abstract Data Type. In ADT, the set of operations is supposed to be understood, and the data structure provides physicality to them.   Data structures are the integral constituent of any programming language or complex computations. Mostly, structured data structures are crucial to designing efficient algorithms._

# DAY 1 (Introduction)

### Data structure
* Data structure is a storage that is used to store and organize data. It is a way of arranging data on a computer so that it can be accessed and updated efficiently.
* Depending on your requirement and project, it is important to choose the right data structure for your project. For example, if you want to store data sequentially in the memory, then you can go for the Array data structure.
* Data structure and data types are slightly different. Data structure is the collection of data types arranged in a specific order.
### Array
* In an array, elements in memory are arranged in continuous memory. All the elements of an array are of the same type. And, the type of elements that can be stored in the form of arrays is determined by the programming language.
### Stack
* In stack data structure, elements are stored in the LIFO principle. That is, the last element stored in a stack will be removed first.
### Queue
* Unlike stack, the queue data structure works in the FIFO principle where first element stored in the queue will be removed first.
### Linked list
* In linked list data structure, data elements are connected through a series of nodes. And, each node contains the data items and address to the next node.
### Non-linear data structures
* Unlike linear data structures, elements in non-linear data structures are not in any sequence. Instead they are arranged in a hierarchical manner where one element will be connected to one or more elements.
* Non-linear data structures are further divided into graph and tree based data structures.
* Similar to a graph, a tree is also a collection of vertices and edges. However, in tree data structure, there can only be one edge between two vertices.


# DAY2 

_there are asymptotic notations , Big-O notation, Theta notation and Omega notation_

## The efficiency of an algorithm depends on the amount of time, storage and other resources required to execute the algorithm. The efficiency is measured with the help of asymptotic notations.
* An algorithm may not have the same performance for different types of inputs. With the increase in the input size, the performance will change.
* The study of change in performance of the algorithm with the change in the order of the input size is defined as asymptotic analysis.
* Asymptotic notations are the mathematical notations used to describe the running time of an algorithm when the input tends towards a particular value or a limiting value.
    * For example: In bubble sort, when the input array is already sorted, the time taken by the algorithm is linear i.e. the best case.
*But, when the input array is in reverse condition, the algorithm takes the maximum time (quadratic) to sort the elements i.e. the worst case.


## There are mainly three asymptotic notations:

-Big-O notation:Since it gives the worst-case running time of an algorithm, it is widely used to analyze an algorithm as we are always interested in the worst-case scenario.
-Omega notation:Omega notation represents the lower bound of the running time of an algorithm. Thus, it provides the best case complexity of an algorithm.
-Theta notation:Theta notation encloses the function from above and below. Since it represents the upper and the lower bound of the running time of an algorithm, it is used for analyzing the average-case complexity of an algorithm.

## Master Theorem

* A divide and conquer algorithm is a strategy of solving a large problem by
1 breaking the problem into smaller sub-problems
2 solving the sub-problems, and
3combining them to get the desired output.
4 To use the divide and conquer algorithm, recursion is used

## How Divide and Conquer Algorithms Work?

_Here are the steps involved:

* Divide: Divide the given problem into sub-problems using recursion.
* Conquer: Solve the smaller sub-problems recursively. If the subproblem is small enough, then solve it directly.
* Combine: Combine the solutions of the sub-problems that are part of the recursive process to solve the actual problem.
### The complexity of the divide and conquer algorithm is calculated using the master theorem.

# Data Structures

Collection of classic and advanced data structure implementations written in
**C/C++**. The code is inspired by the course
**"Mastering Data Structures and Algorithms using C and C++"** by **Abdul Bari**
and is organised so each concept lives in its own folder.

## Features

- Examples for arrays, linked lists, trees, graphs, heaps and more
- Simple, portable C/C++ code with minimal dependencies
- Build every example at once with `make`
- Suitable as a reference for students and hobbyists

## Build

Clone this repository and run `make` to compile all programs:

```bash
git clone https://github.com/najm09/DataStructure.git
cd DataStructure
make
```

Compiled binaries will be placed next to their source files with the `.app`
extension.

## Contributing

Pull requests or fixes are always appreciated!

## Directories Description
### 1. [Arrays](https://github.com/najm09/DataStructure/tree/master/Arrays)
  * #### [DynamicMemory](https://github.com/najm09/DataStructure/tree/master/Arrays/DynamicMemory)
    * Dynamic memory allocation in [heap](https://github.com/najm09/DataStructure/blob/master/Arrays/DynamicMemory/array_heap.c) and use of [malloc function](https://github.com/najm09/DataStructure/blob/master/Arrays/DynamicMemory/malloc.c).
  * #### [OperationOnArrays](https://github.com/najm09/DataStructure/tree/master/Arrays/OperationsOnArrays)
      * [Insert](https://github.com/najm09/DataStructure/blob/master/Arrays/OperationsOnArrays/array_insert.c)
      * [Append](https://github.com/najm09/DataStructure/blob/master/Arrays/OperationsOnArrays/array_append.c)
      * [Delete](https://github.com/najm09/DataStructure/blob/master/Arrays/OperationsOnArrays/array_delete.c)
      * [Sort](https://github.com/najm09/DataStructure/blob/master/Arrays/OperationsOnArrays/array_insertSort.c)
      * [Display](https://github.com/najm09/DataStructure/blob/master/Arrays/OperationsOnArrays/array_display.c)
  * #### [RecursiveArrays](https://github.com/najm09/DataStructure/tree/master/Arrays/RecursiveArrays)
    * Implementation of Array using [recursive functions](https://github.com/najm09/DataStructure/blob/master/Arrays/RecursiveArrays/array_%20usingRecursion.c).
  * #### [SearchinginArrays](https://github.com/najm09/DataStructure/tree/master/Arrays/SearchingInArrays)
      * [Linear search](https://github.com/najm09/DataStructure/blob/master/Arrays/SearchingInArrays/array_linearSearch.c)
      * [Binary Search](https://github.com/najm09/DataStructure/blob/master/Arrays/SearchingInArrays/binarySearch_iterative.c)
      * [Searching with recursion](https://github.com/najm09/DataStructure/blob/master/Arrays/SearchingInArrays/binarySearch_recursive.c)
      * [Improving Linear Search](https://github.com/najm09/DataStructure/blob/master/Arrays/SearchingInArrays/array_linearSearchImproved.c)
      * [Linear Search Transposition](https://github.com/najm09/DataStructure/blob/master/Arrays/SearchingInArrays/array_linearSearschTransposition.c)
      * [searching missing single](https://github.com/najm09/DataStructure/blob/master/Arrays/SearchingInArrays/arrays_returnMissing.c) or [multiple elements](https://github.com/najm09/DataStructure/blob/master/Arrays/SearchingInArrays/array_multiple_missing.c)
  * #### [SetOperations](https://github.com/najm09/DataStructure/tree/master/Arrays/SetOperation)
      * [Intersection of Two Arrays](https://github.com/najm09/DataStructure/blob/master/Arrays/SetOperation/array_intersection.c)
      * [Union of Two Arrays](https://github.com/najm09/DataStructure/blob/master/Arrays/SetOperation/arrays_union.c)
      * [Shift](https://github.com/najm09/DataStructure/blob/master/Arrays/SetOperation/array_shift.c) [Merge](https://github.com/najm09/DataStructure/blob/master/Arrays/SetOperation/arrays_merge.c) and [Reverse](https://github.com/najm09/DataStructure/blob/master/Arrays/SetOperation/array_reverse.c) Operations on the Array
### 2. [Matrices](https://github.com/najm09/DataStructure/tree/master/Matrices)
### 3. [LinkedList](https://github.com/najm09/DataStructure/tree/master/LinkedList)
   * #### [operationsOnLinkedList](https://github.com/najm09/DataStructure/tree/master/LinkedList/operationsOnLinkedList)
        * [Check for sorted list](https://github.com/najm09/DataStructure/blob/master/LinkedList/operationsOnLinkedList/checkSort.c)
        * [Loop detection in a list](https://github.com/najm09/DataStructure/blob/master/LinkedList/operationsOnLinkedList/loopDetection.c)
        * [Merge two link lists](https://github.com/najm09/DataStructure/blob/master/LinkedList/operationsOnLinkedList/mergeTwoLinks.c)
        * [Reversing a link list](https://github.com/najm09/DataStructure/blob/master/LinkedList/operationsOnLinkedList/reversingLinks.c)
        * [Concatenation operation](https://github.com/najm09/DataStructure/blob/master/LinkedList/operationsOnLinkedList/concatLinkLists.c)
        * [Remove duplicates](https://github.com/najm09/DataStructure/blob/master/LinkedList/operationsOnLinkedList/removingDuplicates.c)
        * [Deletion of node](https://github.com/najm09/DataStructure/blob/master/LinkedList/operationsOnLinkedList/linkedList_delete.c)
  * #### [Student Challenge](https://github.com/najm09/DataStructure/tree/master/LinkedList/studentChallenge)
       * [Finding Middle element in a list](https://github.com/najm09/DataStructure/blob/master/LinkedList/studentChallenge/middleElement.c)
       * [Generation of sparse matrix using Linked List](https://github.com/najm09/DataStructure/blob/master/LinkedList/studentChallenge/sparseMatrix.c)
       * [Generation of Polynomial Linked List](https://github.com/najm09/DataStructure/blob/master/LinkedList/studentChallenge/polynomial.c)        
### 4. [Stack](https://github.com/najm09/DataStructure/tree/master/Stack)
  * Stack Implementation code using [Array](https://github.com/najm09/DataStructure/blob/master/Stack/StackArray.c) as well as [Link List](https://github.com/najm09/DataStructure/blob/master/Stack/StackLL.c)
  * Application of Stack in [infix to postfix Conversion](https://github.com/najm09/DataStructure/blob/master/Stack/application.c)
### 5. [Queue](https://github.com/najm09/DataStructure/tree/master/Queue)
  * Implementation code for Queue using [Array](https://github.com/najm09/DataStructure/blob/master/Queue/QueueArray.c), [Link List](https://github.com/najm09/DataStructure/blob/master/Queue/QueueLL.c), [Stack](https://github.com/najm09/DataStructure/blob/master/Queue/QueueStack.c).
  * [Circular Queue](https://github.com/najm09/DataStructure/blob/master/Queue/circularQueueArray.c)
  * [DEQueue](https://github.com/najm09/DataStructure/blob/master/Queue/DEQueue.c)
  * [Recursive Queue](https://github.com/najm09/DataStructure/blob/master/Queue/recursiveQueue.c)
### 6. [binarytree](https://github.com/najm09/DataStructure/tree/master/binarytree)
  * [Nodes in a binary tree](https://github.com/najm09/DataStructure/blob/master/binarytree/C/nodes.c)
  * [Level Order Traversal using Queue](https://github.com/najm09/DataStructure/blob/master/binarytree/C/levelorder.c)
  * [Post Order Traversal using one stack without recursion](https://github.com/najm09/DataStructure/blob/master/binarytree/C/postorder.c)
  * [Recursive Inorder, Postorder and Preorder traversal](https://github.com/najm09/DataStructure/blob/master/binarytree/C/create_tree.c)
### 7. [BST](https://github.com/najm09/DataStructure/tree/master/BST)
  * [Operations Binary search tree](https://github.com/najm09/DataStructure/blob/master/BST/C/main.c)
  * [Recursive](https://github.com/najm09/DataStructure/blob/master/BST/C/recursive.c) implementation of binary search tree
### 8. [AVL](https://github.com/najm09/DataStructure/tree/master/AVL)
  * Performing [Rotation](https://github.com/najm09/DataStructure/tree/master/AVL) while Generation of BST
### 9. [Heap](https://github.com/najm09/DataStructure/tree/master/Heap)
* [Heapify](https://github.com/najm09/DataStructure/blob/master/Heap/C/heapify.c) method for faster heap creation
* [Max heap](https://github.com/najm09/DataStructure/tree/master/Heap/C/MaxHeap)
* [Min heap](https://github.com/najm09/DataStructure/tree/master/Heap/C/MinHeap)
### 10. [HashTable](https://github.com/najm09/DataStructure/tree/master/HashTable)
  * [Chaining](https://github.com/najm09/DataStructure/blob/master/HashTable/chaining.cpp)
  * [Linear Probing](https://github.com/najm09/DataStructure/blob/master/HashTable/linearProbing.cpp)
  * [Quadratic Probing](https://github.com/najm09/DataStructure/blob/master/HashTable/quadraticProbing.cpp)
  * [Double Hashing](https://github.com/najm09/DataStructure/blob/master/HashTable/doubleHashing.cpp)
### 11. [Graph](https://github.com/najm09/DataStructure/tree/master/Graph)
### 12. [Advanced : Not in Course](https://github.com/najm09/DataStructure/tree/master/Advanced)
  * [Binary indexed tree](https://github.com/najm09/DataStructure/blob/master/Advanced/binaryIndexTree.cpp)
  * [Trie](https://github.com/najm09/DataStructure/blob/master/Advanced/Trie.cpp)
----------------------------------------------------------------------------------------------------------------

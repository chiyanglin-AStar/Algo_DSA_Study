#  Cracking Code interview

# Table of Contents

0. [General](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#General)

1. [Arrays and String](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Arrays-and-String)

   [MIT 2. Data Structures and Dynamic Arrays](https://www.youtube.com/watch?v=CHhwJjR0mZA&list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY&index=3&t=11s)

   [Hash Table in C/C++ - A Complete Implementation](https://www.digitalocean.com/community/tutorials/hash-table-in-c-plus-plus)

   [C++ program for hashing with chaining](https://www.geeksforgeeks.org/c-program-hashing-chaining/)
   
2. [Linked List](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Linked-List)

[3.Stack Queue](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Stack-Queue)

[4.Tree Graphs](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Tree-Graphs)

[5.Bit Manipulation](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Bit-Manipulation)

[6.Math and Logic Puzzles](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Math-and-Logic-Puzzles)

[7.Object-Oriented Design](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Object-Oriented-Design)

[8.Recursion and Dynamic Programming](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Recursion-and-Dynamic-Programming)

[9.System Design and Scalability](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#System-Design-and-Scalability)

[10.Sorting and Searching](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Sorting-and-Searching)

[11.Testing](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Testing)

[12.C and C++](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#C-and-Cplusplus)

[13.Databases](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Databases)

[14.Threads and Locks](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Threads-and-Locks)

[15.Moderate](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Moderate)

[16.Hard](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Hard)

# Arrays and String
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions

1.1 Is Unique: Implement an algorithm to determine if a string has all unique characters. What if you
cannot use additional data structures?

ref: 
  1. [Determine if a string has all Unique Characters](https://www.geeksforgeeks.org/determine-string-unique-characters/)

1.2 Check Permutation: Given two strings, write a method to decide if one is a permutation of the other.

ref: 
  1. [Check if two strings are permutation of each other](https://www.geeksforgeeks.org/check-if-two-strings-are-permutation-of-each-other/)
  2. [567. Permutation in String](https://leetcode.com/problems/permutation-in-string/)

1.3 URLify: Write a method to replace all spaces in a string with '%20'. You may assume that the string
has sufficient space at the end to hold the additional characters, and that you are given the "true"
length of the string. (Note: If implementing in Java, please use a character array so that you can
perform this operation in place.)
EXAMPLE
Input: "Mr 3ohn Smith 13
Output: "Mr%203ohn%20Smith"

ref: 
  1. [URLify a given string (Replace spaces with %20)](https://www.geeksforgeeks.org/urlify-a-given-string-replace-spaces-with-%20/)

  2. [Amazon | Phone screen | URLify a given string (replace spaces with %20)](https://leetcode.com/discuss/interview-question/124608/amazon-phone-screen-urlify-a-given-string-replace-spaces-with-20)

1.4 Palindrome Permutation: Given a string, write a function to check if it is a permutation of a palindrome.
A palindrome is a word or phrase that is the same forwards and backwards. A permutation is a rearrangement of letters. The palindrome does not need to be limited to just dictionary words.
EXAMPLE
Input: Tact Coa
Output: True (permutations: "taco cat", "atco e t a " , etc.)

ref: 
  1. [Palindrome Permutations The Problem: Write a function that checks whether any permutation of a string is a palindrome](https://medium.com/swlh/palindrome-permutations-9752d8e71c7f)

  2. [Print all palindrome permutations of a string](https://www.geeksforgeeks.org/print-all-palindrome-permutations-of-a-string/)

1.5 One Away: There are three types of edits that can be performed on strings: insert a character,
remove a character, or replace a character. Given two strings, write a function to check if they are
one edit (or zero edits) away.
EXAMPLE
p a l e , pie -> true
p a l e s , pale -> true
p a l e , bale -> true
p a l e , bake -> false
Hints: #23, #97, it 130

ref:
  1. [Check if edit distance between two strings is one](https://www.geeksforgeeks.org/check-if-two-given-strings-are-at-edit-distance-one/)

  2. [72. Edit Distance](https://leetcode.com/problems/edit-distance/)

1.6 String Compression: Implement a method to perform basic string compression using the counts
of repeated characters. For example, the string aabcccccaaa would become a2blc5a3, If the
"compressed" string would not become smaller than the original string, your method should return
the original string. You can assume the string has only uppercase and lowercase letters (a - z).


ref: 
  1. [String Compression](https://kodr.me/en/string-compression)
     
  2. [443. String Compression](https://leetcode.com/problems/string-compression/)

1.7 Rotate Matrix: Given an image represented by an NxN matrix, where each pixel in the image is 4
bytes, write a method to rotate the image by 90 degrees. Can you do this in place?

ref:
  1. [Inplace rotate square matrix by 90 degrees | Set 1](https://www.geeksforgeeks.org/inplace-rotate-square-matrix-by-90-degrees/)

  2. [48. Rotate Image](https://leetcode.com/problems/rotate-image/)

1.8 Zero Matrix: Write an algorithm such that if an element in an MxN matrix is 0, its entire row and column are set to 0.

ref:
  1. [73. Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/)

1.9 String Rotation; Assume you have a method i s S u b s t r i n g which checks if one word is a substring
of another. Given two strings, si and s2, write code to check if s2 is a rotation of si using only one
call to i s S u b s t r i n g [e.g., "water b o t t l e " is a rotation o P ' e r b o t t l e w a t " ) ,

ref:
  1. [796. Rotate String](https://leetcode.com/problems/rotate-string/)
 
Additional Questions: Object-Oriented Design (#7.12), Recursion (#8.3), Sorting and Searching (#10.9), C++
(#12.11), Moderate Problems (#16.8, #16.17, #16,22), Hard Problems (#17.4, #17.7, #17.13, #17.22, #17,26).


# Linked List
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

2.1 Remove Dups: Write code to remove duplicates from an unsorted linked list.
FOLLOW UP
How would you solve this problem if a temporary buffer is not allowed?

ref:
  1. [Remove duplicates from an unsorted linked list](https://www.geeksforgeeks.org/remove-duplicates-from-an-unsorted-linked-list/)

  2. [82. Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/)

2.2 Return Kth to Last: Implement an algorithm to find the kth to last element of a singly linked list.

ref:
  1. [Program for Nth node from the end of a Linked List](https://www.geeksforgeeks.org/nth-node-from-the-end-of-a-linked-list/)

  2. [19. Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)

2.3 Delete Middle Node: Implement an algorithm to delete a node in the middle (i.e., any node but
the first and last node, not necessarily the exact middle) of a singly linked list, given only access to
that node.
EXAMPLE
Input: the node c from the linked list a - >b- >c - >d - >e- >f
Result: nothing is returned, but the new linked list looks like a - > b - > d - > e - > f

ref: 
  1. [Delete middle of linked list](https://www.geeksforgeeks.org/delete-middle-of-linked-list/)

  2. [2095. Delete the Middle Node of a Linked List](https://leetcode.com/problems/delete-the-middle-node-of-a-linked-list/)

2.4 Partition: Write code to partition a linked list around a value x, such that all nodes less than x come
before all nodes greater than or equal to x. Ifxis contained within the list, the values of x only need
to be after the elements less than x (see below). The partition element x can appear anywhere in the
"right partition"; it does not need to appear between the left and right partitions.
EXAMPLE
Input: 3 -> 5 -> 8 -> 5 -> 10 -> 2 -> 1 [partition = 5]
Output: 3 -> 1 -> 2 -> 10 -> 5 -> 5 -> 8

ref:
  1. [Partitioning a linked list around a given value and keeping the original order](https://www.geeksforgeeks.org/partitioning-a-linked-list-around-a-given-value-and-keeping-the-original-order/)

  2. [86. Partition List](https://leetcode.com/problems/partition-list/)

2.5 Sum Lists: You have two numbers represented by a linked list, where each node contains a single
digit. The digits are stored in reverse order, such that the Vs digit is at the head of the list. Write a
function that adds the two numbers and returns the sum as a linked list.
EXAMPLE
Input: ( 7 - > 1 -> 6) + (5 -> 9 -> 2).That is,617 + 295.
Output: 2 -> 1 -> 9. That is, 912.
FOLLOW UP
Suppose the digits are stored in forward order. Repeat the above problem.
EXAMPLE
Input: (6 -> 1 -> 7) + (2 -> 9 -> 5).That is, 617 + 295,
Output:9 -> 1 -> 2,Thatis,912.

ref:
  1. [Add two numbers represented by Linked List](https://www.geeksforgeeks.org/add-two-numbers-represented-by-linked-list/)

  2. [2. Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)

2.6 Palindrome: Implement a function to check if a linked list is a palindrome.

ref:
  1. [Function to check if a singly linked list is palindrome](https://www.geeksforgeeks.org/function-to-check-if-a-singly-linked-list-is-palindrome/)

  2. [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)

2.7 Intersection; Given two (singly) linked lists, determine if the two lists intersect. Return the intersecting
node. Note that the intersection is defined based on reference, not value. That is, if the kth
node of the first linked list is the exact same node (by reference) as the j t h node of the second
linked list, then they are intersecting.

ref:
  1. [Write a function to get the intersection point of two Linked Lists](https://www.geeksforgeeks.org/write-a-function-to-get-the-intersection-point-of-two-linked-lists/)

  2. [160. Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)

2.8 Loop Detection: Given a circular linked list, implement an algorithm that returns the node at the
beginning of the loop.
DEFINITION
Circular linked list: A (corrupt) linked list in which a node's next pointer points to an earlier node, so
as to make a loop in the linked list.
EXAMPLE
Input: A - > 8 - > C - > D - > E - > C [the same C as earlier]
Output: C

Additional Questions: Trees and Graphs (#4,3), Object-Oriented Design (#7.12), System Design and Scalability
(#9.5), Moderate Problems (#16.25), Hard Problems (#17.12).

ref:
  1. [Detect loop in a linked list](https://www.geeksforgeeks.org/detect-loop-in-a-linked-list/)

  2. [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)

# Stack Queue
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions

3.1 Three in One: Describe how you could use a single array to implement three stacks.

ref:
  1. [How to efficiently implement k stacks in a single array?](https://www.geeksforgeeks.org/efficiently-implement-k-stacks-single-array/)

  2. [How to implement 3 stacks with one array?](https://stackoverflow.com/questions/4770627/how-to-implement-3-stacks-with-one-array)

3.2 Stack Min: How would you design a stack which, in addition to push and pop, has a function min
which returns the minimum eiement? Push, pop and min should ail operate in 0 ( 1 ) time.

ref:
  1. [Design a stack that supports getMin() in O(1) time and O(1) extra space](https://www.geeksforgeeks.org/design-a-stack-that-supports-getmin-in-o1-time-and-o1-extra-space/)

  2. [155. Min Stack](https://leetcode.com/problems/min-stack/)

3.3 Stack of Plates: Imagine a (literal) stack of plates. If the stack gets too high, it might topple.
Therefore, in real life, we would likely start a new stack when the previous stack exceeds some
threshold. Implement a data structure SetOfStacks that mimics this. SetOfStacks should be
composed of several stacks and should create a new stack once the previous one exceeds capacity.
SetOfStacks . p u s h ( ) and SetOfStacks . p o p ( ) should behave identically to a single stack
(that is, pop( ) should return the same values as it would if there were just a single stack).
FOLLOW UP
Implement a function popAt( i n t index) which performsa pop operation on a specific sub-stack.
Hints: #64, #81

ref: 
  1. [Stack of Plates: Cracking the coding interview](Stack of Plates: Cracking the coding interview)

  2. [Stack Of Plates](https://github.com/chiyanglin-AStar/Algo_study/edit/main/Crack_Code_Interview.md)
  
3.4 Queue via Stacks: Implement a MyQueue class which implements a queue using two stacks.

ref:
  1. [Queue using Stacks](https://www.geeksforgeeks.org/queue-using-stacks/)

  2. [232. Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/)

3.5 Sort Stack: Write a program to sort a stack such that the smallest items are on the top. You can use
an additional temporary stack, but you may not copy the elements into any other data structure
(such as an array). The stack supports the following operations: push, pop, peek, and is Empty.

ref:
  1. [Sort a stack using a temporary stack](https://www.geeksforgeeks.org/sort-stack-using-temporary-stack/)

  2. [Given a stack, sort it in non-decreasing order](https://leetcode.com/discuss/interview-question/125398/given-a-stack-sort-it-in-non-decreasing-order)

3.6 Animal SheltenAn animal shelter, which holds only dogs and cats, operates on a strictly "first in, first
out" basis. People must adopt either the "oldest" (based on arrival time) of all animals at the shelter,
or they can select whether they would prefer a dog or a cat (and will receive the oldest animal of
that type). They cannot select which specific animal they would like. Create the data structures to
maintain this system and implement operations such as enqueue, dequeueAny, dequeueDog,
and dequeueCat.You may use the built-in L i n k e d L i s t data structure.


Additional Questions: Linked Lists (#2.6), Moderate Problems (#16.26), Hard Problems (#17.9).
Hints start on page 653.

# Tree Graphs
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

4.1 Route Between Nodes: Given a directed graph, design an algorithm to find out whether there is a
route between two nodes.

ref:
  1. [Find if there is a path between two vertices in a directed graph]()

4.2 Minimal Tree: Given a sorted (increasing order) array with unique integer elements, write an algorithm
to create a binary search tree with minimal height.

ref:
  1. [Sorted Array to Balanced BST](https://www.geeksforgeeks.org/sorted-array-to-balanced-bst/)

  2. [108. Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)
  
4.3 List of Depths: Given a binary tree, design an algorithm which creates a linked list of all the nodes
at each depth (e.g., if you have a tree with depth D, you'll have D linked lists).

ref:
  1. [Flatten a binary tree into linked list](https://www.geeksforgeeks.org/flatten-a-binary-tree-into-linked-list/)
  
  2. [114. Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/)

4.4 Check Balanced: Implement a function to check if a binary tree is balanced. For the purposes of
this question, a balanced tree is defined to be a tree such that the heights of the two subtrees of any
node never differ by more than one.

ref:
  1. [How to determine if a binary tree is height-balanced?](https://www.geeksforgeeks.org/how-to-determine-if-a-binary-tree-is-balanced/)

  2. [110. Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/)

4.5 Validate BST: Implement a function to check if a binary tree is a binary search tree.

ref:
  1. [A program to check if a Binary Tree is BST or not](https://www.geeksforgeeks.org/a-program-to-check-if-a-binary-tree-is-bst-or-not/)

  2. [98. Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/)

4.6 Successor: Write an algorithm to find the "next" node (i.e., in-order successor) of a given node in a
binary search tree. You may assume that each node has a link to its parent.


4.7 Build Order: You are given a list of projects and a list of dependencies (which is a list of pairs of
projects, where the second project is dependent on the first project). Ail of a project's dependencies
must be built before the project is. Find a build order that will allow the projects to be built. If there
is no valid build order, return an error.
EXAMPLE
Input:
p r o j e c t s : a, b, c, d, e, f
dependencies: (a, d), ( f , b ) , (b, d ) , ( f , a ) , (d, c)
Output: f, e, a, b, d, c

ref: 
   [Google | OA 2020 | Delayed Projects](https://leetcode.com/discuss/interview-question/397524/)


4.8 First Common Ancestor: Design an algorithm and write code to find the first common ancestor
of two nodes in a binary tree. Avoid storing additional nodes in a data structure. NOTE: This is not
necessarily a binary search tree.
Hints: #10, # 16, #28, #36, #46, #70, #80, #96

ref: 
   1. [Lowest Common Ancestor in a Binary Tree](https://www.geeksforgeeks.org/lowest-common-ancestor-binary-tree-set-1/)

   2. [236. Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)

4.9 BST Sequences: A binary search tree was created by traversing through an array from left to right
and inserting each element. Given a binary search tree with distinct elements, print all possible
arrays that could have led to this tree.
EXAMPLE
Input:
Output: {2, 1, 3},{2, 3, 1}

ref: 
  1. [1569. Number of Ways to Reorder Array to Get Same BST](https://leetcode.com/problems/number-of-ways-to-reorder-array-to-get-same-bst/)

4.10 Check Subtree: T1 and T2 are two very large binary trees, with T1 much bigger than T2. Create an
algorithm to determine if 12 is a subtree o f T l .
AtreeT2 is a subtree of T1 if there exists a node n in T1 such that the subtree of n is identical to 12,
That is, if you cut off the tree at node n, the two trees would be identical.

ref: 
  1. [Check if a Binary Tree is subtree of another binary tree | Set 1](https://www.geeksforgeeks.org/check-if-a-binary-tree-is-subtree-of-another-binary-tree/)

  2. [Amazon Onsite | check if T2 is subtree of T1 ,both are very large trees](https://github.com/chiyanglin-AStar/Algo_study/edit/main/Crack_Code_Interview.md)
  
4.11 Random Node: You are implementing a binary tree class from scratch which, in addition to
i n s e r t , f i n d , and d e l e t e , has a method getRandomNode() which returns a random node
from the tree. All nodes should be equally likely to be chosen. Design and implement an algorithm
for getRandomNode, and explain how you would implement the rest of the methods.

ref: 
  1. [Select a Random Node from a tree with equal probability](https://www.geeksforgeeks.org/select-random-node-tree-equal-probability/)

4.12 Paths with Sum: You are given a binary tree in which each node contains an integer value (which
might be positive or negative). Design an algorithm to count the number of paths that sum to a
given value. The path does not need to start or end at the root or a leaf, but it must go downwards
(traveling only from parent nodes to child nodes).

ref: 
  1. [112. Path Sum](https://leetcode.com/problems/path-sum/)

  2. [Print all k-sum paths in a binary tree](https://www.geeksforgeeks.org/print-k-sum-paths-binary-tree/)

Additional Questions: Recursion (#8.10), System Design and Scalability (#9.2, #9.3), Sorting and Searching
(#10.10), Hard Problems (#17.7, #17.12, #17.13, #17.14, #17.17, #17.20, #17.22, #17,25).
Hints start on page 653.

# Bit Manipulation
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

5.1 Insertion: You are given two 32-bit numbers, N and M, and two bit positions, i and
j. Write a method to insert M into N such that M starts at bit j and ends at bit i. You
can assume that the bits j through i have enough space to fit all of M. That is, if
M = 10011, you can assume that there are at least 5 bits between j and i. You would not, for
example, have j = 3 and i = 2, because M could not fully fit between bit 3 and bit 2.
EXAMPLE
Input: N = 10000000000j M = 10011, i = 2, j = 6
Output: N = 10001001100
Hints: # 137, if 169, #2 IS

1. [Inserting M into N such that m starts at bit j and ends at bit i | Set-2](https://www.geeksforgeeks.org/inserting-m-into-n-such-that-m-starts-at-bit-j-and-ends-at-bit-i-set-2/)


5.2 Binary to String: Given a reai number between 0 and 1 (e.g., 0.72) that is passed in as a double, print
the binary representation. If the number cannot be represented accurately in binary with at most 32
characters, print "ERROR."

ref: 
  1. [Converting a Real Number (between 0 and 1) to Binary String](https://www.geeksforgeeks.org/converting-a-real-number-between-0-and-1-to-binary-string/)

5.3 Flip Bit to Win: You have an integer and you can flip exactly one bit from a 0 to a 1, Write code to
find the length of the longest sequence of Is you could create.
EXAMPLE
Input: 1775 (or: 11011101111)
Output: 8

ref: 
  1. [Find longest sequence of 1’s in binary representation with one flip](https://www.geeksforgeeks.org/find-longest-sequence-1s-binary-representation-one-flip/)
  
  2. [2220. Minimum Bit Flips to Convert Number](https://leetcode.com/problems/minimum-bit-flips-to-convert-number/)

5.4 Next Number: Given a positive integer, print the next smallest and the next largest number that
have the same number of 1 bits in their binary representation.

ref: 
  1. [Closest (or Next) smaller and greater numbers with same number of set bits](https://leetcode.com/problems/next-greater-element-iii/)
  
  2. [556. Next Greater Element III](https://leetcode.com/problems/next-greater-element-iii/)

5.5 Debugger: Explain what thefollowing code does: ( (n & ( n - 1 ) ) == 0).

ref: 
  1. [Using n&(n-1) trick](https://leetcode.com/problems/power-of-two/discuss/63974/Using-nand(n-1)-trick)


5.6 Conversion: Write a function to determine the number of bits you would need to flip to convert
integer A to integer B.
EXAMPLE
Input: 29 ( o r : 11101), 15 ( o r : 01111)
Output: 2

ref:
  1. [Count number of bits to be flipped to convert A to B](https://www.geeksforgeeks.org/count-number-of-bits-to-be-flipped-to-convert-a-to-b/)
  

5.7 PairwiseSwap: Write a program to swap odd and even bits in an integer with as few instructions as
possible (e.g., bit 9 and bit 1 are swapped, bit 2 and bit 3 are swapped, and so on).

ref:
  1. [Swap all odd and even bits](https://www.geeksforgeeks.org/swap-all-odd-and-even-bits/)

5.8 Draw Line: A monochrome screen is stored as a single array of bytes, allowing eight consecutive
pixels to be stored in one byte. The screen has width w, where w is divisible by 8 (that is, no byte will
be split across rows). The height of the screen, of course, can be derived from the length of the array
and the width. Implement a function that draws a horizontal line from ( x l , y) to ( x 2 , y).
The method signature should look something like:
drawl ine(byte[ ] screen., int width, int x l , i n t X2, i n t y)


Additional Questions: Arrays and Strings (#1.1, #1.4, #1.8), Math and Logic Puzzles (#6.10), Recursion (#8.4,
#8.14), Sorting and Searching (#10.7, #10.8), C++(#12.10), Moderate Problems (#16.1, #16.7), Hard Problems
(#17.1).



# Math and Logic Puzzles
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions
6.1 The Heavy Pill: You have 20 bottles of pills. 19 bottles have 1.0 gram pills, but one has pills of weight
1.1 grams. Given a scale that provides an exact measurement, how would you find the heavy bottle?
You can only use the scale once.

ref:
  1. [Puzzle | 10 identical bottles of pills](https://www.geeksforgeeks.org/puzzle-10-identical-bottles-pills/)
  
6.2 Basketball: You have a basketball hoop and someone says that you can play one of two games.
Game 1: You get one shot to make the hoop.
Game 2: You get three shots and you have to make two of three shots.
If p is the probability of making a particular shot, for which values of p should you pick one game
or the other?

ref: 
  1. [Puzzle | (Basketball shots)](https://www.geeksforgeeks.org/puzzle-basketball-shots/)

6.3 Dominos: There is an 8x8 chessboard in which two diagonally opposite corners have been cut off.
You are given 31 dominos, and a single domino can cover exactly two squares. Can you use the 31
dominos to cover the entire board? Prove your answer (by providing an example or showing why
it's impossible).

ref: 
  1. [Puzzle 25 | (Chessboard and dominos)](https://www.geeksforgeeks.org/puzzle-25chessboard-and-dominos/)

6.4 Ants on a Triangie: There are three ants on different vertices of a triangle. What is the probability of
coliision (between any two or all of them) if they start walking on the sides of the triangle? Assume
that each ant randomly picks a direction, with either direction being equally likely to be chosen, and
that they walk at the same speed.
Similarly, find the probability of collision with n ants on an n-vertex polygon.

ref:
  1. [Puzzle 21 | (3 Ants and Triangle)](https://www.geeksforgeeks.org/puzzle-21-3-ants-and-triangle/)


6.5 Jugs of Water: You have a five-quart jug, a three-quart jug, and an unlimited supply of water (but
no measuring cups). How would you come up with exactly four quarts of water? Note that the jugs
are oddly shaped, such that filling up exactly "half" of the jug would be impossible.
Hints: #149, #379, #400

6.6 Blue-Eyed Island: A bunch of people are living on an island, when a visitor comes with a strange
order: all blue-eyed people must leave the island as soon as possible. There will be a flight out at
8:00 pm every evening. Each person can see everyone else's eye color, but they do not know their
own (nor is anyone allowed to tell them). Additionally, they do not know how many people have
blue eyes, although they do know that at least one person does. How many days will it take the
blue-eyed people to leave?

ref: 
  1. [The Blue – eyed Island puzzle](https://www.geeksforgeeks.org/blue-eyed-island-puzzle/)

6.7 The Apocalypse: In the new post-apocalyptic world, the world queen is desperately concerned
about the birth rate. Therefore, she decrees that all families should ensure that they have one girl or
else they face massive fines. If all families abide by this policy—that is, they have continue to have
children until they have one girl, at which point they immediately stop—what will the gender ratio
of the new generation be? (Assume that the odds of someone having a boy or a girl on any given
pregnancy is equal.) Solve this out logically and then write a computer simulation of it.
Hints: #154, #160, #171, #188, #201

ref:
  1. [Puzzle | The Apocalypse](https://www.geeksforgeeks.org/puzzle-the-apocalypse/)


6.8 The Egg Drop Problem: There is a building of 100 floors. If an egg drops from the Nth floor or
above, it will break. If it's dropped from any floor below, it will not break. You're given two eggs. Find
N, while minimizing the number of drops for the worst case.
Hints; #156, #233, #294, #333, #357, #374, #395

ref: 
  1. [Puzzle | Set 35 (2 Eggs and 100 Floors)](https://www.geeksforgeeks.org/puzzle-set-35-2-eggs-and-100-floors/)

6.9 100 Lockers: There are 100 closed lockers in a hallway. A man begins by opening all 100 lockers.
Next, he doses every second locker. Then, on his third pass, he toggles every third locker (closes it if
it is open or opens it if it is closed). This process continues for 100 passes, such that on each pass i,
the man toggles every i t h locker. After his 100th pass in the hallway, in which he toggles only locker
#100, how many lockers are open?


6.10 Poison: You have 1000 bottles of soda, and exactly one is poisoned. You have 10 test strips which
can be used to detect poison. A single drop of poison will turn the test strip positive permanently.
You can put any number of drops on a test strip at once and you can reuse a test strip as many times
as you'd like (as long as the results are negative). However, you can only run tests once per day and
it takes seven days to return a result. How would you figure out the poisoned bottle in as few days
as possible?
FOLLOW UP
Write code to simulate your approach.

ref:
  1. [Puzzle 19 | (Poison and Rat)](https://www.geeksforgeeks.org/puzzle-19-poison-and-rat/)

Additional Problems: Moderate Problems (#16.5), Hard Problems (#17.19)


# Object-Oriented Design
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

7.1 Deck of Cards: Design the data structures for a generic deck of cards. Explain how you would
subclass the data structures to implement blackjack.

ref: 
  1. [Design the Data Structures(classes and objects)for a generic deck of cards](https://www.geeksforgeeks.org/design-data-structuresclasses-objectsfor-generic-deck-cards/)


7.2 Call Center: Imagine you have a call center with three levels of employees: respondent, manager,
and director. An incoming telephone call must be first allocated to a respondent who is free. If the
respondent can't handle the call, he or she must escalate the call to a manager. If the manager is not
free or not able to handle it, then the call should be escalated to a director. Design the classes and
data structures for this problem. Implement a method d i s p a t c h C a l l ( } which assigns a call to
the first available employee.
7
8
>
return n u l l ;

ref:
  1. [Question about OOD - Call Center (Python)](https://leetcode.com/discuss/general-discussion/1819870/question-about-ood-call-center-python)

7.3 Jukebox: Design a musical jukebox using object-oriented principles.


7.4 Parking Lot: Design a parking lot using object-oriented principles.

ref:
  1. [How to design a parking lot using object-oriented principles?](https://www.geeksforgeeks.org/design-parking-lot-using-object-oriented-principles/)

7.5 Online Book Reader: Design the data structures for an online book reader system.


7.6 Jigsaw: Implement an NxN jigsaw puzzle. Design the data structures and explain an algorithm to
solve the puzzle. You can assume that you have a f i t s W i t h method which, when passed two
puzzle edges, returns true if the two edges belong together.

ref:
   1/ [Asana | Software Engineer| Design a jigsaw puzzle | OOD](Asana | Software Engineer| Design a jigsaw puzzle | OOD)

7.7 Chat Server: Explain how you would design a chat server. In particular, provide details about the
various backend components, classes, and methods. What wouid be the hardest problems to solve?



7.8 Othello: Othello is played as follows: Each Othello piece is white on one side and black on the other.
When a piece is surrounded by its opponents on both the left and right sides, or both the top and
bottom, it is said to be captured and its color is flipped. On your turn, you must capture at least one
of your opponent's pieces. The game ends when either user has no more valid moves. The win is
assigned to the person with the most pieces. Implement the object-oriented design for Othello.
Hints: #179, #228

7.9 Circular Array: Implement a C i r c u l a r A r r a y class that supports an array-like data structure which
can be efficiently rotated. If possible, the class should use a generic type (also called a template), and
should support iteration via the standard f o r (Obj o : c i r c u l a r A r r a y ) notation.

ref:
  1. [Circular array](https://www.geeksforgeeks.org/circular-array/) 

# Recursion and Dynamic Programming
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions
8.1 Triple Step: A child is running up a staircase with n steps and can hop either 1 step, 2 steps, or 3
steps at a time, implement a method to count how many possible ways the child can run up the
stairs.

ref:
  1. [Count ways to reach the nth stair using step 1, 2 or 3](https://www.geeksforgeeks.org/count-ways-reach-nth-stair-using-step-1-2-3/)
  
  2. [70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)

8.2 Robot in a Grid: Imagine a robot sitting on the upper left corner of grid with r rows and c columns.
The robot can only move in two directions, right and down, but certain cells are "off limits" such that
the robot cannot step on them. Design an algorithm to find a path for the robot from the top left to
the bottom right.

ref:
  1. [62. Unique Paths](https://leetcode.com/problems/unique-paths/)

8.3 Magic Index: A magic index in an array A [ 0 . . . n - 1 ] is defined to be an index such that A [ i ] =
i. Given a sorted array of distinct integers, write a method to find a magic index, if one exists, in
array A.
FOLLOW UP
What if the values are not distinct?

ref:
  1. [Magical Indices in an array](https://www.geeksforgeeks.org/magical-indices-array/)

8.4 Power Set: Write a method to return all subsets of a set.

ref:
  1. [Power Set](https://www.geeksforgeeks.org/power-set/)
  
  2. [Recursive program to generate power set](https://www.geeksforgeeks.org/recursive-program-to-generate-power-set/)
  
8.5 Recursive Multiply: Write a recursive function to multiply two positive integers without using the
* operator. You can use addition, subtraction, and bit shifting, but you should minimize the number
of those operations.

ref:
  1. [Product of 2 Numbers using Recursion](https://www.geeksforgeeks.org/product-2-numbers-using-recursion/)

  2. [how to multiply two positive integers using recursion?](https://stackoverflow.com/questions/71466603/how-to-multiply-two-positive-integers-using-recursion)

8.6 Towers of Hanoi: In the classic problem of the Towers of Hanoi, you have 3 towers and N disks of
different sizes which can slide onto any tower. The puzzle starts with disks sorted in ascending order
of size from top to bottom (i.e., each disk sits on top of an even larger one). You have the following
constraints:
(1) Only one disk can be moved at a time.
(2) A disk is slid off the top of one tower onto another tower.
(3) A disk cannot be placed on top of a smaller disk.
Write a program to move the disks from the first tower to the last using stacks.

ref:
   1. [Program for Tower of Hanoi Algorithm](https://www.geeksforgeeks.org/c-program-for-tower-of-hanoi/)

8.7 Permutations without Dups: Write a method to compute all permutations of a string of unique
characters.

ref:
  1. [Distinct permutations of the string | Set 2](https://www.geeksforgeeks.org/distinct-permutations-string-set-2/)
  
  2. [47. Permutations II](https://leetcode.com/problems/permutations-ii/)

8.8 Permutations with Dups: Write a method to compute all permutations of a string whose characters
are not necessarily unique. The list of permutations should not have duplicates.


8.9 Parens; implement an algorithm to print all valid (e.g., properly opened and closed) combinations
of n pairs of parentheses.
EXAMPLE
Input: 3
O u t p u t : ( ( ( ) ) ) , ( 0 0 : ) , ( ( » ( > , 0 ( 0 ) , 0 0 0

ref:
  1. [Print all combinations of balanced parentheses](https://www.geeksforgeeks.org/print-all-combinations-of-balanced-parentheses/)
  
  2. [22. Generate Parentheses](https://leetcode.com/problems/generate-parentheses/)

8.10 Paint Fill: Implement the "paint fill"function that one might see on many image editing programs.
That is, given a screen (represented by a two-dimensional array of colors), a point, and a new color,
fill in the surrounding area until the color changes from the original cofor.


8.11 Coins: Given an infinite number of quarters (25 cents), dimes (10 cents), nickels (5 cents), and
pennies (1 cent), write code to calculate the number of ways of representing n cents.

ref: 
   1. [Coins Problem](https://leetcode.com/discuss/general-discussion/471566/coins-problem)


8.12 Eight Queens: Write an algorithm to print all ways of arranging eight queens on an 8x8 chess board
so that none of them share the same row, column, or diagonal. In this case, "diagonal" means all
diagonals, not just the two that bisect the board.

ref: 
  1. [8 queen problem](https://www.geeksforgeeks.org/8-queen-problem/)
  
8.13 Stack of Boxes: You have a stack of n boxes, with widths w4, heights ht , and depths dr The boxes
cannot be rotated and can only be stacked on top of one another if each box in the stack is strictly
larger than the box above it in width, height, and depth. Implement a method to compute the
height of the tallest possible stack. The height of a stack is the sum of the heights of each box.

ref:
  1. [Box Stacking Problem | DP-22](https://github.com/chiyanglin-AStar/Algo_study/edit/main/Crack_Code_Interview.md)

8.14 Boolean Evaluation: Given a boolean expression consisting of the symbols 0 (false), 1 (true), &
(AND), | (OR), and A (XOR), and a desired boolean result value r e s u l t , implement a function to
count the number of ways of parenthesizing the expression such that it evaluates to r e s u l t ,
EXAMPLE
c o u n t E v a l ( " l A e | 0 j l M , f a l s e ) -> 2
c o u n t E v a l ( " 0 & 0 & 0 & l A l | 0 " , t r u e ) -> 10

ref:
  1. [Boolean Parenthesization Problem | DP-37](https://www.geeksforgeeks.org/boolean-parenthesization-problem-dp-37/)
  
  2. [Boolean Parenthesization ( EASY || C++)](https://leetcode.com/discuss/general-discussion/1279635/boolean-parenthesization-easy-c)

Additional Questions: Linked Lists (#2.2, #2.5, #2.6), Stacks and Queues (#3.3), Trees and Graphs (#4.2, #4,3,
#4.4, #4.5, #4,8, #4.10, #4.11, #4.12), Math and Logic Puzzles (#6,6), Sorting and Searching (#10.5, #10.9,
#10.10), C++ (#12.8), Moderate Problems (#16,11), Hard Problems (#17,4, #17.6, #17.8, #17.12, #17.13,
#17.15,#17.16,#17.24,#17.25).


# System Design and Scalability
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions
These questions are designed to mirror a real interview, so they will not always be well defined. Think about
what questions you would ask your interviewer and then make reasonable assumptions. You may make
different assumptions than us, and that will lead you to a very different design. That's okay!
Stock Data: Imagine you are building some sort of service that will be called by up to 1,000 client
applications to get simple end-of-day stock price information (open, close, high, low). You may
assume that you already have the data, and you can store it in any format you wish. How would you
design the client-facing service that provides the information to client applications? You are responsible
for the development, rollout, and ongoing monitoring and maintenance of the feed. Describe
the different methods you considered and why you would recommend your approach. Your service
can use any technologies you wish, and can distribute the information to the client applications in
any mechanism you choose.


9.2 Social Network: How would you design the data structures for a very large social network like Facebook
or Linkedln? Describe how you would design an algorithm to show the shortest path between
two people (e.g.. Me -> Bob -> Susan -> Jason -> You).

ref:
  1. [Design data structures for a very large social network like Facebook or Linkedln](https://www.geeksforgeeks.org/design-data-structures-for-a-very-large-social-network-like-facebook-or-linkedln/)

9.3 Web Crawler: If you were designing a web crawler, how would you avoid getting into infinite loops?

ref: 
  1. [Facebook | System Design | Web Crawler](https://leetcode.com/discuss/interview-question/962461/Facebook-or-System-Design-or-Web-Crawler/782832)
  
  2. [Designing a web crawler](https://stackoverflow.com/questions/5834808/designing-a-web-crawler)

9.4 Duplicate URLs: You have 10 billion URLs. How do you detect the duplicate documents? In this
case, assume "duplicate" means that the URLs are identical.

ref:
  1. [given 10 billion URL with average length 100 characters per each url, check duplicate](https://stackoverflow.com/questions/45393165/given-10-billion-url-with-average-length-100-characters-per-each-url-check-dupl)


9.5 Cache: Imagine a web server for a simplified search engine. This system has 100 machines to
respond to search queries, which may then call out using processSearch( s t r i n g query) to
another cluster of machines to actually get the result.The machine which responds to a given query
is chosen at random, so you cannot guarantee that the same machine will always respond to the
same request. The method processSearch is very expensive. Design a caching mechanism for
the most recent queries. Be sure to explain how you would update the cache when data changes.


9.6 Sales Rank: A large eCommerce company wishes to list the best-setling products, overall and by
category. For example, one product might be the #1056th best-selling product overall but the #13th
best-selling product under "Sports Equipment" and the #24th best-seiling product under "Safety."
Describe how you would design this system.


9.7 Personal Financial Manager: Explain how you would design a personal financial manager (like
Mint.com). This system would connect to your bank accounts, analyze your spending habits, and
make recommendations.


9.8 Pastebin: Design a system like Pastebin, where a user can enter a piece of text and get a randomly
generated URL to access it.

ref:
  1. [Design Pastebin](https://leetcode.com/discuss/interview-question/system-design/124804/Design-Pastebin)

Additional Questions: Object-Oriented Design (#7.7)


# Sorting and Searching
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions
10.1 Sorted Merge: You are given two sorted arrays, A and B, where A has a large enough buffer at the
end to hold B. Write a method to merge B into A in sorted order.

ref: 
   1. [Sorted merge in one array](https://www.geeksforgeeks.org/sorted-merge-one-array/)
   
   2. [Merge two sorted arrays](https://www.geeksforgeeks.org/merge-two-sorted-arrays/)

   3. [88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/)

10.2 Group Anagrams: Write a method to sort an array of strings so that all the anagrams are next to
each other.

ref:
  1. [Given a sequence of words, print all anagrams together | Set 1](https://leetcode.com/problems/group-anagrams/)

  2. [49. Group Anagrams](https://leetcode.com/problems/group-anagrams/)

10.3 Search in Rotated Array: Given a sorted array of n integers that has been rotated an unknown
number of times, write code to find an element in the array. You may assume that the array was
originally sorted in increasing order,
EXAMPLE
Input: find 5 in [15, 16, 19, 20, 25, 1, 3, 4, 5, 7, 10, 14}
Output: 8 (the index of 5 in the array)

ref:
  1. [Search an element in a sorted and rotated Array](https://www.geeksforgeeks.org/search-an-element-in-a-sorted-and-pivoted-array/)
  
  2. [33. Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)


10.4 Sorted Search, No Size: You are given an array-like data structure L i s t y which lacks a size
method. It does, however, have an elementAt ( i ) method that returns the element at index i in
0 ( 1 ) time, if i is beyond the bounds of the data structure, it returns -1. (For this reason, the data
structure only supports positive integers.) Given a L i s t y which contains sorted, positive integers,
find the index at which an element X occurs. If x occurs multiple times, you may return any index.

ref:
  1. [Find the Missing Number in a sorted array](https://www.geeksforgeeks.org/find-the-missing-number-in-a-sorted-array/)
  

  
10.5 Sparse Search: Given a sorted array of strings that is interspersed with empty strings, write a
method to find the location of a given string.
EXAMPLE
Input: b a l l , { " a t " , " " , " " , " " , " b a l l " , "", " c a r " , " " , " " , "dad", " " ,
any
Output: 4

ref: 
  1. [Sparse Search](https://www.geeksforgeeks.org/sparse-search/)
  
  2. [Sparse search in a sorted array](https://leetcode.com/discuss/general-discussion/468170/sparse-search-in-a-sorted-array)

10.6 Sort Big File: Imagine you have a 20 GB file with one string per line. Explain how you would sort
the file.

ref:
  1. [Sorting a 20GB file with one string per line](https://stackoverflow.com/questions/14817120/sorting-a-20gb-file-with-one-string-per-line)

  2. [Sorting larger file with smaller RAM](https://www.geeksforgeeks.org/sorting-larger-file-with-smaller-ram/)

  3. [External Sorting](https://www.geeksforgeeks.org/external-sorting/)


10.7 Missing Int: Given an input file with four billion non-negative integers, provide an algorithm to
generate an integer that is not contained in the file. Assume you have 1 GB of memory available for
this task.
FOLLOW UP
What if you have only 10 MB of memory? Assume that ail the values are distinct and we now have
no more than one billion non-negative integers.

ref: 
   1. [Generate an integer that is not among four billion given ones](https://stackoverflow.com/questions/7153659/generate-an-integer-that-is-not-among-four-billion-given-ones)
   
10.8 Find Duplicates: You have an array with all the numbers from 1 to N, where N is at most 32,000.The
array may have duplicate entries and you do not know what N is. With only 4 kilobytes of memory
available, how would you print alt duplicate elements in the array?

ref:
  1. [Find Duplicates of array using bit array](https://www.geeksforgeeks.org/find-duplicates-of-array-using-bit-array/)
  
  2. [Find duplicates in O(n) time and O(1) extra space | Set 1](https://www.geeksforgeeks.org/find-duplicates-in-on-time-and-constant-extra-space/)
  
  3. [https://leetcode.com/problems/find-all-duplicates-in-an-array/](https://leetcode.com/problems/find-all-duplicates-in-an-array/)
  
10.9 Sorted Matrix Search: Given an M x N matrix in which each row and each column is sorted in
ascending order, write a method to find an element.

ref:
  1. [Search in a row wise and column wise sorted matrix](https://www.geeksforgeeks.org/search-in-row-wise-and-column-wise-sorted-matrix/)
  
  2. [Search element in a sorted matrix](https://www.geeksforgeeks.org/search-element-sorted-matrix/)
  
  3. [74. Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/)


10.10 Rank from Stream: Imagine you are reading in a stream of integers. Periodically, you wish to be able
to look up the rank of a number x (the number of values less than or equal to x). Implement the data
structures and algorithms to support these operations. That is, implement the method t r a c k ( i n t
x), which is called when each number is generated, and the method getRankOfNumber(int
x), which returns the number of values tess than or equal to x (not including x itself).
EXAMPLE
Stream (in order of appearance): 5, 4, 4, 5, 9, 7, 13, 3
getRankOfNumber(l) = 0
getRank0fNumber(3) = 1
getRank0fNumber(4) = 3

ref:
  1. [Rank of an element in a stream](https://www.geeksforgeeks.org/rank-element-stream/)
  
  2. [Amazon || SDE2 Onsite || Rank of an element in a stream](https://leetcode.com/discuss/interview-question/1057103/amazon-sde2-onsite-rank-of-an-element-in-a-stream)

10.11 Peaks and Valleys: In an array of integers, a "peak" is an element which is greater than or equal to
the adjacent integers and a "valley" is an element which is less than or equal to the adjacent integers.
For example, in the array [5, 8,6, 2, 3,4, 6), {8,6} are peaks and {5, 2} are valleys. Given an array
of integers, sort the array into an alternating sequence of peaks and valleys.
EXAMPLE
Input: IS, 3,1,2, 3)
Output: (5,1,3,2, 3}


Additional Questions: Arrays and Strings (#1.2), Recursion (#8.3), Moderate (#16.10, #16.16, #16.21, #16.24),
Hard (#17,11, #17.26).
Hints start on page 662.


# Testing
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions
11.1 Mistake: Find the mistake(s) in the following code:
unsigned i n t i;
for {i = 100; i >= 0; --i)
printf ("%d\niJj l)j

ref: 
  1. [What's the mistake in this code? unsigned int i](https://stackoverflow.com/questions/34832902/whats-the-mistake-in-this-code-unsigned-int-i-for-i-100-i-0-i-print)


11.2 Random Crashes: You are given the source to an application which crashes when it is run. After
running it ten times in a debugger, you find it never crashes in the same place. The application is
single threaded, and uses only the C standard library. What programming errors could be causing
this crash? How would you test each one?

ref: 
  1. [Debugging a program that crashes 10 times in different places](https://stackoverflow.com/questions/4531742/debugging-a-program-that-crashes-10-times-in-different-places)

11.3 Chess Test: We have the following method used in a chess game: boolean canMoveTo(int x,
i n t y). This method is part of the Piece class and returns whether or not the piece can move to
position ( x , y). Explain how you would test this method.

ref: 
  1. [Design a Chess Game](https://www.geeksforgeeks.org/design-a-chess-game/)
  
11.4 No Test Tools: How would you load test a webpage without using any test tools?


11.5 Test a Pen; How would you test a pen?


11.6 Test an ATM: How would you test an ATM in a distributed banking system?


# C and Cplusplus
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions
12.1 Last K Lines: Write a method to print the last K lines of an input file using C++.

ref:
  1. [Program to print last 10 lines](https://www.geeksforgeeks.org/print-last-10-lines-of-a-given-file/)
  
  2. [reading last n lines from file in c/c++](https://stackoverflow.com/questions/17877025/reading-last-n-lines-from-file-in-c-c)

12.2 Reverse String: Implement a function v o i d reverse( c h a r * s t r ) in C or C++which reverses
a null-terminated string.

ref:
  1. [Different Methods to Reverse a String in C++](https://www.geeksforgeeks.org/reverse-a-string-in-c-cpp-different-methods/)
  
  2. [void function(no printing)- reverse a string using recursion](https://stackoverflow.com/questions/27754181/void-functionno-printing-reverse-a-string-using-recursion)

12.3 Hash Table vs. STL Map: Compare and contrast a hash table and an STL map. How is a hash table
implemented? If the number of inputs is small, which data structure options can be used instead of
a hash table?

  1. [Hash Table vs STL Map](https://www.geeksforgeeks.org/hash-table-vs-stl-map/)
  
  2. [Hash Table v/s STL map in C++](https://stackoverflow.com/questions/2460387/hash-table-v-s-stl-map-in-c)

12.4 Virtual Functions: How do virtual functions work in C++?

ref:
  1. [Virtual Function in C++](https://www.geeksforgeeks.org/virtual-function-cpp/)

12.5 Shallow vs. Deep Copy: What is the difference between deep copy and shallow copy? Explain how
you would use each.

ref:
  1. [Difference between Shallow and Deep copy of a class](https://www.geeksforgeeks.org/difference-between-shallow-and-deep-copy-of-a-class/)
  
  2. [What is the difference between a deep copy and a shallow copy?](https://stackoverflow.com/questions/184710/what-is-the-difference-between-a-deep-copy-and-a-shallow-copy)

12.6 Volatile: What is the significance of the keyword "volatile" in C?

ref:
  1. [Understanding “volatile” qualifier in C | Set 2 (Examples)](https://www.geeksforgeeks.org/understanding-volatile-qualifier-in-c/)
  
  2. [Why is volatile needed in C?](https://stackoverflow.com/questions/246127/why-is-volatile-needed-in-c)


12.7 Virtual Base Class: Why does a destructor in base class need to be declared v i r t u a l ?

ref: 
  1. [Virtual Destructor](https://www.geeksforgeeks.org/virtual-destructor/)
  
  2. [Why should the destructor of base classes be virtual?](https://stackoverflow.com/questions/5873515/why-should-the-destructor-of-base-classes-be-virtual)
  
12.8 Copy Node; Write a method that takes a pointer to a Node structure as a parameter and returns a
complete copy of the passed in data structure. The Node data structure contains two pointers to
other Nodes.

ref: 
  1. [Insertion in Doubly Circular Linked List](https://www.geeksforgeeks.org/insertion-in-doubly-circular-linked-list/)
  
  2. [Structure Pointer in C](https://www.geeksforgeeks.org/structure-pointer-in-c/)

  3. [Interview Coding - Take a pointer to a Node structure as a parameter and return a complete copy of the passed-in data structure](https://www.geeksforgeeks.org/structure-pointer-in-c/)

12.9 Smart Pointer: Write a smart pointer class. A smart pointer is a data type, usually implemented with
templates, that simulates a pointer while also providing automatic garbage collection. It automatically
counts the number of references to a Smart P o i n t er<T*> object and frees the object of type
T when the reference count hits zero.

ref:
  1. [Smart Pointers in C++ and How to Use Them](https://www.geeksforgeeks.org/smart-pointers-cpp/)
  
  2. [What is the best way to implement smart pointers in C++?](https://stackoverflow.com/questions/503833/what-is-the-best-way-to-implement-smart-pointers-in-c)
  
  
12.10 Malloc: Write an aligned malloc and free function that supports allocating memory such that the
memory address returned is divisible by a specific power of two.
EXAMPLE
a l i g n j n a l l o c (1000,128) will return a memory address that is a multiple of 128 and that points
to memory of size 1000 bytes.
a l i g n e d _ f r e e ( ) will free memory allocated by a l i g n j u a l l o c .

ref:
  1. [aligned malloc c++ implementation](https://stackoverflow.com/questions/51936866/aligned-malloc-c-implementation)

12.11 2D Alloc: Write a function in C called riy2DAlloc which allocates a two-dimensional array. Minimize
the number of calls to m a l l o c and make sure that the memory is accessible by the notation
a r r [ i ] [ j ] .

ref:
  1. [How to dynamically allocate a 2D array in C?](https://www.geeksforgeeks.org/dynamically-allocate-2d-array-c/)

Additional Questions: Linked Lists (#2.6), Testing (#11.1), Java (#13.4), Threads and Locks (#15.3).


# Databases
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Threads and Locks
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions
15.1 Thread vs. Process: What's the difference between a thread and a process?

ref:
  1. [Difference between Process and Thread](https://www.geeksforgeeks.org/difference-between-process-and-thread/)
  
    
15.2 Context Switch: How would you measure the time spent in a context switch?

ref: 
  1. [Measure the time spent in context switch?](https://www.geeksforgeeks.org/measure-time-spent-context-switch/)
  
  2. [how can you measure the time spent in a context switch under java platform](https://stackoverflow.com/questions/6987394/how-can-you-measure-the-time-spent-in-a-context-switch-under-java-platform)


15.3 Dining Philosophers: In the famous dining philosophers problem, a bunch of philosophers are
sitting around a circular table with one chopstick between each of them. A philosopher needs
both chopsticks to eat, and always picks up the left chopstick before the right one. A deadlock
could potentially occur if all the philosophers reached for the left chopstick at the same time. Using
threads and locks, implement a simulation of the dining philosophers problem that prevents deadlocks.

ref:
  1. [Dining Philosopher Problem Using Semaphores](https://www.geeksforgeeks.org/dining-philosopher-problem-using-semaphores/)

15.4 Deadlock-Free Class: Design a class which provides a lock only if there are no possible deadlocks.

ref:
  1. [Deadlock in Java Multithreading](https://www.geeksforgeeks.org/deadlock-in-java-multithreading/)
  
  2. [Design a class which provides a lock only if there are no possible deadlocks](https://stackoverflow.com/questions/5171649/design-a-class-which-provides-a-lock-only-if-there-are-no-possible-deadlocks)

15.5 Call In Order; Suppose we have the following code:
public class Foo {
public Foo() { . . . }
public void f i r s t Q { . . . >
public void second() { . . . }
public void t h i r d ( ) { . . . }
}
The same instance of Foo will be passed to three different threads. ThreadA will call f i r s t ,
threadB will call second, and threadC will call t h i r d . Design a mechanism to ensure that
f i r s t is called before second and second is called before t h i r d .

ref:
  1. [1114. Print in Order](https://leetcode.com/problems/print-in-order/)


15.6 Synchronized Methods: You are given a class with synchronized method A and a normal method
B. If you have two threads in one instance of a program, can they both execute A at the same time?
Can they execute A and B at the same time?

ref:
  1. [If I synchronized two methods on the same class, can they run simultaneously?](https://stackoverflow.com/questions/15438727/if-i-synchronized-two-methods-on-the-same-class-can-they-run-simultaneously)


15.7 FizzBuzz: In the classic problem FizzBuzz, you are told to print the numbers from 1 to n. However,
when the number is divisible by B, print "Fizz". When it is divisible by 5, print "Buzz" When it is divisible
by 3 and 5, print "FizzBuzz". In this problem, you are asked to do this in a multithreaded way.
Implement a multithreaded version of FizzBuzz with four threads. One thread checks for divisibility
of 3 and prints"Fizz". Another thread is responsible for divisibility of 5 and prints "Buzz" A third thread
is responsible for divisibility of 3 and 5 and prints "FizzBuzz". A fourth thread does the numbers.


# Moderate
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

16.1 Number Swapper: Write a function to swap a number in place (that is, without temporary variables).

ref:
  1. [How to swap two numbers without using a temporary variable?](https://www.geeksforgeeks.org/swap-two-numbers-without-using-temporary-variable/)

16.2 Word Frequencies: Design a method to find the frequency of occurrences of any given word in a
book. What if we were running this algorithm multiple times?

ref:
  1. [Calculate the frequency of each word in the given string](https://www.geeksforgeeks.org/calculate-the-frequency-of-each-word-in-the-given-string/)

  2. [Most frequent word in an array of strings](https://www.geeksforgeeks.org/frequent-word-array-strings/)

  3. [How to find high frequency words in a book in an environment low on memory?](https://stackoverflow.com/questions/742125/how-to-find-high-frequency-words-in-a-book-in-an-environment-low-on-memory)


16.3 Intersection: Given two straight line segments (represented as a start point and an end point),
compute the point of intersection, if any.

ref:
  1. [Given n line segments, find if any two segments intersect](https://www.geeksforgeeks.org/given-a-set-of-line-segments-find-if-any-two-segments-intersect/)
  
  2. [Program for Point of Intersection of Two Lines](https://www.geeksforgeeks.org/program-for-point-of-intersection-of-two-lines/)

  3. [How to find whether two line segment(not two straight lines) intersect](https://stackoverflow.com/questions/18928803/how-to-find-whether-two-line-segmentnot-two-straight-lines-intersect)


16.4 TicTac Win: Design an algorithm to figure out if someone has won a game of tic-tac-toe.

ref:
  1. [Validity of a given Tic-Tac-Toe board configuration](https://www.geeksforgeeks.org/validity-of-a-given-tic-tac-toe-board-configuration/)
  
  2. [Algorithm for Determining Tic Tac Toe Game Over](https://stackoverflow.com/questions/1056316/algorithm-for-determining-tic-tac-toe-game-over)

  3. [1275. Find Winner on a Tic Tac Toe Game](https://leetcode.com/problems/find-winner-on-a-tic-tac-toe-game/)


16.5 Factorial Zeros: Write an algorithm which computes the number of trailing zeros in n factorial.

ref:
  1. [Count trailing zeroes in factorial of a number](https://www.geeksforgeeks.org/count-trailing-zeroes-factorial-number/)

  2. [172. Factorial Trailing Zeroes](https://leetcode.com/problems/factorial-trailing-zeroes/)


16.6 Smallest Difference: Given two arrays of integers, compute the pair of values (one value in each
array) with the smallest (non-negative) difference. Return the difference.
EXAMPLE
Input: {1, 3,1S, 11, 2}, (23,127, 235,19, 8)
Output: 3. That is, the pair (11,8).

ref:
  1. [Smallest Difference pair of values between two unsorted Arrays](https://www.geeksforgeeks.org/smallest-difference-pair-values-two-unsorted-arrays/)

  2. [Find minimum difference between any two elements (pair) in given array](https://www.geeksforgeeks.org/find-minimum-difference-pair/)

  3. [1200. Minimum Absolute Difference](https://leetcode.com/problems/minimum-absolute-difference/)

16.7 Number Max: Write a method that finds the maximum of two numbers. You should not use if-else
or any other comparison operator.

ref:
  1. [Compute the minimum or maximum of two integers without branching](https://www.geeksforgeeks.org/compute-the-minimum-or-maximum-max-of-two-integers-without-branching/)

  2. [Explain this snippet which finds the maximum of two integers without using if-else or any other comparison operator?](https://stackoverflow.com/questions/4772780/explain-this-snippet-which-finds-the-maximum-of-two-integers-without-using-if-el)

16.8 English Int: Given any integer, print an English phrase that describes the integer (e.g., "OneThousand,
Two Hundred Thirty Four").

ref:
  1. [Program to convert a given number to words](https://www.geeksforgeeks.org/convert-number-to-words/)

  2. [273. Integer to English Words](https://leetcode.com/problems/integer-to-english-words/)

  3. [print an English phrase that describes the integer](https://stackoverflow.com/questions/32943166/print-an-english-phrase-that-describes-the-integer)


16.9 Operations: Write methods to implement the multiply, subtract, and divide operations for integers.
The results of all of these are integers. Use only the add operator.

ref:
  1. [Implement *, – and / operations using only + arithmetic operator](https://www.geeksforgeeks.org/implement-and-operations-using-only-arithmetic-operator/)

  2. [282. Expression Add Operators](https://leetcode.com/problems/expression-add-operators/)

  3. [29. Divide Two Integers](https://leetcode.com/problems/divide-two-integers/)


16.10 Living People: Given a list of people with their birth and death years, implement a method to
compute the year with the most number of people alive. You may assume that all people were born
between 1900 and 2000 (inclusive). If a person was alive during any portion of that year, they should
be included in that year's count. For example. Person (birth = 1908, death = 1909) is included in the
counts for both 1908 and 1909.

ref: 
  1. [1854. Maximum Population Year](https://leetcode.com/problems/maximum-population-year/)

  2. [Find the year with the most number of people alive in Python](https://stackoverflow.com/questions/31522450/find-the-year-with-the-most-number-of-people-alive-in-python)

16.11 Diving Board: You are building a diving board by placing a bunch of planks of wood end-to-end.
There are two types of planks, one of length s h o r t e r and one of length longer. You must use
exactly K planks of wood. Write a method to generate all possible lengths for the diving board.


16.12 XML Encoding: Since XML is very verbose, you are given a way of encoding it where each tag gets
mapped to a pre-defined integer value. The language/grammar is as follows:
Element --> Tag A t t r i b u t e s END Children END
A t t r i b u t e --> Tag Value
END --> 0
Tag --> some predefined mapping to i n t
Value --> s t r i n g value
For example, the following XML might be converted into the compressed string below (assuming a
mapping o f f a m i l y -> 1, person ->2, firstName -> 3, lastName - > 4 , s t a t e
-> 5).
<family lastName="McDowell" state="CA">
•cperson firstName="Gayle">Some Message</person>
</family>
Becomes:
1 4 McDowell 5 CA 0 2 3 Gayle 0 Some Message 0 0
Write code to print the encoded version of an XML element (passed in Element and A t t r i b u t e
objects).


16.13 Bisect Squares: Given two squares on a two-dimensional plane, find a line that would cut these two
squares in half. Assume that the top and the bottom sides of the square run parallel to the x-axis.

ref:
  1. [Minimum length of square to contain at least half of the given Coordinates](https://www.geeksforgeeks.org/minimum-length-of-square-to-contain-at-least-half-of-the-given-coordinates/)

  2. [Falling Squares](https://leetcode.com/problems/falling-squares/solutions/127471/official-solution/)

  3. [Slicing two squares in half equally on a cartesian plane](https://stackoverflow.com/questions/32960654/slicing-two-squares-in-half-equally-on-a-cartesian-plane-finding-midpoint)

16.14 Best Line: Given a two-dimensional graph with points on it, find a line which passes the most
number of points.

ref:
  1. [Given a two-dimensional graph with points, find a line that passes through the largest number of points](https://stackoverflow.com/questions/52391658/given-a-two-dimensional-graph-with-points-find-a-line-that-passes-through-the-l)
 
16.15 Master Mind: The Game of Master Mind is played as follows:
The computer has four slots, and each slot will contain a ball that is red (ft), yellow (V), green (G) or
blue (B). For example, the computer might have RGGB (Slot #1 is red, Slots #2 and #3 are green. Slot
#4 is blue).
You, the user, are trying to guess the solution. You might, for example, guess YRGB.
When you guess the correct color for the correct slot, you get a "hit." If you guess a color that exists
but is in the wrong slot, you get a "pseudo-hit." Mote that a slot that is a hit can never count as a
pseudo-hit.
For example, if the actual solution is RGBY and you guess GGRR, you have one hit and one pseudo-hit.
Write a method that, given a guess and a solution, returns the number of hits and pseudo-hits.


16.16 Sub Sort: Given an array of integers, write a method to find indices m and n such that if you sorted
elements m through n, the entire array would be sorted. Minimize n - m (that is, find the smallest
such sequence).
EXAMPLE
Input: lj 2, 4j 7, 10, 11, 1, 12, 6, 7, 16, 18, 19
Output: ( 3 , 9)

ref: 
  1. [Find the Minimum length Unsorted Subarray, sorting which makes the complete array sorted](https://www.geeksforgeeks.org/minimum-length-unsorted-subarray-sorting-which-makes-the-complete-array-sorted/)
  
  2. [Shortest Unsorted Continous Subarray](https://leetcode.com/problems/shortest-unsorted-continuous-subarray/solutions/127627/official-solution/)

16.17 Contiguous Sequence: You are given an array of integers (both positive and negative). Find the
contiguous sequence with the largest sum. Return the sum.
EXAMPLE
Input:2, -8, 3, -2, 4, -10
Output: 5 ( i . e . , {3, -2, 4})

ref:
  1. [Largest Sum Contiguous Subarray (Kadane’s Algorithm)](https://www.geeksforgeeks.org/largest-sum-contiguous-subarray/)
  
  2. [53. Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)

16.18 Pattern Matching: You are given two strings, p a t t e r n and value.The p a t t e r n string consists of
just the letters a and b, describing a pattern within a string. For example, the string c a t c a t g o c a t g o
matches the pattern aabab (where cat is a and go is b). It also matches patterns like a, ab, and b.
Write a method to determine if v a l u e matches p a t t e r n .

ref:
  1. [Match a pattern and String without using regular expressions](https://www.geeksforgeeks.org/match-a-pattern-and-string-without-using-regular-expressions/)

  2. [290. Word Pattern](https://leetcode.com/problems/word-pattern/)

  3. [10. Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/)
  
16.19 Pond Sizes: You have an integer matrix representing a plot of land, where the value at that location
represents the height above sea level. A value of zero indicates water. A pond is a region of
water connected vertically, horizontally, or diagonally. The size of the pond is the total number of
connected water cells. Write a method to compute the sizes of all ponds in the matrix.
EXAMPLE
Input:
6 2 1 0
e 1 e 1
1 1 0 1
0 1 0 1
Output: 2,4,1 (in any order)

ref: 
  1. [Find number of closed islands in given Matrix](https://www.geeksforgeeks.org/find-number-of-closed-islands-in-given-matrix/)

  2. [200. Number of Islands](https://leetcode.com/problems/number-of-islands/)

  3. [695. Max Area of Island](https://leetcode.com/problems/max-area-of-island/)


16.20 T9: On old cell phones, users typed on a numeric keypad and the phone would provide a list of
words that matched these numbers. Each digit mapped to a set of 0 - 4 letters. Implement an algorithm
to return a list of matching words, given a sequence of digits. You are provided a list of valid
words (provided in whatever data structure you'd like). The mapping is shown in the diagram below:
1 2 3
abc def
4 S 6
ghi jkl mno
7 8 9
pqrs tuv wxyz
0
EXAMPLE
Input: 8733
Output: tree, used

ref: 
  1. [Print all possible words from phone digits](https://www.geeksforgeeks.org/find-possible-words-phone-digits/)

  2. [Convert a sentence into its equivalent mobile numeric keypad sequence](https://www.geeksforgeeks.org/convert-sentence-equivalent-mobile-numeric-keypad-sequence/)

16.21 Sum Swap: Given two arrays of integers, find a pair of values (one value from each array) that you
can swap to give the two arrays the same sum.
EXAMPLE
Input:{4,1,2,1,1, 2}and [3,6, 3,3}
Output: {1, 3}

ref: 
  1. [Find a pair of elements swapping which makes sum of two arrays same](https://www.geeksforgeeks.org/find-a-pair-swapping-which-makes-sum-of-two-arrays-same/)

  2. [1775. Equal Sum Arrays With Minimum Number of Operations]()

16.22 Langton's Ant: An ant is sitting on an infinite grid of white and biack squares. It initially faces right.
At each step, it does the following:
(1) At a white square, flip the coior of the square, turn 90 degrees right (clockwise), and move forward
one unit,
(2) At a black square, flip the color of the square, turn 90 degrees left (counter-clockwise), and move
forward one unit.
Write a program to simulate the first K moves that the ant makes and print the final board as a grid.
Note that you are not provided with the data structure to represent the grid. This is something you
must design yourself. The only input to your method is K. You should print the final grid and return
nothing.The method signature might be something like v o i d printKMoves( i n t K).


16.23 Rand? from Rand5: Implement a method rand7() given rand5( ).That is, given a method that
generates a random number between 0 and 4 (inclusive), write a method that generates a random
number between 0 and 6 (inclusive).

ref: 
  1. [Generate integer from 1 to 7 with equal probability](https://www.geeksforgeeks.org/generate-integer-from-1-to-7-with-equal-probability/)

  2. [Expand a random range from 1–5 to 1–7](https://stackoverflow.com/questions/137783/expand-a-random-range-from-1-5-to-1-7)

  3. [470. Implement Rand10() Using Rand7()](https://leetcode.com/problems/implement-rand10-using-rand7/)

16.24 Pairs with Sum: Design an algorithm to find all pairs of integers within an array which sum to a
specified value.

ref:
  1. [Count pairs with given sum](https://www.geeksforgeeks.org/count-pairs-with-given-sum/)

  2. [Check if a pair exists with given sum in given array](https://www.geeksforgeeks.org/given-an-array-a-and-a-number-x-check-for-pair-in-a-with-sum-as-x/)

  3. [1. Two Sum](https://leetcode.com/problems/two-sum/)

  4. [39. Combination Sum](https://leetcode.com/problems/combination-sum/)


16.25 LRU Cache: Design and build a "least recently used" cache, which evicts the least recently used
item. The cache should map from keys to values (allowing you to insert and retrieve a value associated
with a particular key) and be initialized with a max size. When it is full, it should evict the least
recently used item.


16.26 Calculator: Given an arithmetic equation consisting of positive integers, +, -, * and / (no parentheses),
compute the result.
EXAMPLE
Input; 2*3+5/6*3+15
Output: 23.5

ref:
  1. [Arrange given numbers in a mathematical expression using operators [+, -, *, /] and parentheses to get value 2](https://www.geeksforgeeks.org/arrange-given-numbers-in-a-mathematical-expression-using-operators-and-parentheses-to-get-value-24/)

   2. [Find all possible outcomes of a given expression](https://www.geeksforgeeks.org/find-all-possible-outcomes-of-a-given-expression/)

   3. [2232. Minimize Result by Adding Parentheses to Expression](https://leetcode.com/problems/minimize-result-by-adding-parentheses-to-expression/)

# Hard
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

17.1 Add Without Plus: Write a function that adds two numbers. You should not use + or any arithmetic
operators.

ref:
  1. [Add two numbers without using arithmetic operators](https://www.geeksforgeeks.org/add-two-numbers-without-using-arithmetic-operators/)

  2. [How to sum two integers without using arithmetic operators in C/C++?]https://www.geeksforgeeks.org/how-to-sum-two-integers-without-using-arithmetic-operators-in-cc/(https://www.geeksforgeeks.org/how-to-sum-two-integers-without-using-arithmetic-operators-in-cc/)

  3. [371. Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/)

17.2 Shuffle: Write a method toshuffleadeckofcards.lt must be a perfect shuffle—in other words, each
of the 521 permutations of the deck has to be equally likely. Assume that you are given a random
number generator which is perfect.

ref:
  1. [Shuffle a deck of cards](https://www.geeksforgeeks.org/shuffle-a-deck-of-cards-3/)

  2. [Shuffle an Array](https://leetcode.com/problems/shuffle-an-array/solutions/127672/official-solution/)


17.3 Random Set: Write a method to randomly generate a set of m integers from an array of size n. Each
element must have equal probability of being chosen.

ref: 
  1. [Generate integer from 1 to 7 with equal probability](https://www.geeksforgeeks.org/generate-integer-from-1-to-7-with-equal-probability/)

  2. [Randomly generate a set of m integers from an array of size n](https://stackoverflow.com/questions/13755472/randomly-generate-a-set-of-m-integers-from-an-array-of-size-n)

  3. [Random Pick Index](https://leetcode.com/problems/random-pick-index/solutions/924150/official-solution/)

17.4 Missing Number: An array A contains all the integers from 0 to n, except for one number which
is missing. In this problem, we cannot access an entire integer in A with a single operation. The
elements of A are represented in binary, and the only operation we can use to access them is "fetch
the j t h bit of A[ i ] , " which takes constant time. Write code to find the missing integer. Can you do
it in 0( n) time?

ref: 
  1. [Find the missing element in an array of integers represented in binary format](https://www.geeksforgeeks.org/find-the-missing-element-in-an-array-of-integers-represented-in-binary-format/)
  
  2. [448. Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) 

  3. [question about missing element in array](https://stackoverflow.com/questions/2946056/question-about-missing-element-in-array)

17.5 Letters and Numbers: Given an array filled with letters and numbers, find the longest subarray with
an equal number of letters and numbers.

ref:
  1. [Longest sub-array with equal number of alphabets and numeric characters](https://www.geeksforgeeks.org/longest-sub-array-with-equal-number-of-alphabets-and-numeric-characters/)

  2. [Largest subarray with equal number of 0s and 1s](https://www.geeksforgeeks.org/largest-subarray-with-equal-number-of-0s-and-1s/)

  3. [525. Contiguous Array](https://leetcode.com/problems/contiguous-array/)


17.6 Count of 2s: Write a method to count the number of 2s that appear in all the numbers between 0
and n (inclusive).
EXAMPLE
Input: 25
Output: 9 (2,12,20, 21, 22, 23, 24 and 25. Note that 22 counts for two 2s.)

ref:
  1. [Number of occurrences of 2 as a digit in numbers from 0 to n](https://www.geeksforgeeks.org/number-of-occurrences-of-2-as-a-digit-in-numbers-from-0-to-n/)

  2. [Count the number of Ks between 0 and N](https://stackoverflow.com/questions/20945790/count-the-number-of-ks-between-0-and-n)

17.7 Baby Names; Each year, the government releases a list of the 10000 most common baby names
and their frequencies {the number of babies with that name). The only problem with this is that
some names have multiple spellings. For example, "John" and "Jon" are essentially the same name
but would be listed separately in the list. Given two lists, one of names/frequencies and the other
of pairs of equivalent names, write an atgorithm to print a new list of the true frequency of each
name. Note that if John and Jon are synonyms, and Jon and Johnny are synonyms, then John and
Johnny are synonyms, (it is both transitive and symmetric.) In the final list, any name can be used
as the "real" name,
EXAMPLE
Input:
Names: John (15), Jon (12), Chris (13), Kris (4), Christopher (19)
Synonyms: {Jon, John), (John, Johnny), (Chris, Kris), {Chris, Christopher)
Output: John (27), Kris (36)


17.8 Circus Tower: A circus is designing a tower routine consisting of people standing atop one another's
shoulders. For practical and aesthetic reasons, each person must be both shorter and lighter
than the person below him or her. Given the heights and weights of each person in the circus, write
a method to compute the largest possible number of people in such a tower.
EXAMPLE
Input (ht, wt): (65, 100) (70, 150) (56, 90) (75, 190) (60, 95) (68, 110)
Output: The longest tower is length 6 and includes from top to bottom:
( 5 6 , 90) (60,95) (65,100) (68,110) (70,150) (75,190)


17.9 Kth Multiple: Design an atgorithm to find the kth number such that the only prime factors are 3, 5,
and 7. Note that 3, 5, and 7 do not have to be factors, but it should not have any other prime factors.
For example, the first several multiples would be {in order) 1,3, 5, 7, 9,15,21.

ref:
  1. [Kth number from the set of multiples of numbers A, B and C](https://www.geeksforgeeks.org/kth-number-from-the-set-of-multiples-of-numbers-a-b-and-c/)

  2. [786. K-th Smallest Prime Fraction](https://leetcode.com/problems/k-th-smallest-prime-fraction/)

17.10 Majority Element: A majority element is an element that makes up more than half of the items in
an array. Given a positive integers array, find the majority element. If there is no majority element,
return -1. Do this in0(N) time and 0 ( 1 ) space.
EXAMPLE
Input: 1 2 5 9 5 9 5 5 5
Output: 5

ref:
  1. [Majority Element](https://www.geeksforgeeks.org/majority-element/)
  
  2. [169. Majority Element](https://leetcode.com/problems/majority-element/)

17.11 Word Distance: You have a large text file containing words. Given any two words, find the shortest
distance (in terms of number of words) between them in the file. If the operation will be repeated
many times for the same file (but different pairs of words), can you optimize your solution?

ref:
  1. [Word Wrap Problem | DP-19](https://www.geeksforgeeks.org/word-wrap-problem-dp-19/)

  2. [First non repeating word in a file? File size can be 100GB](https://leetcode.com/discuss/interview-question/124858/First-non-repeating-word-in-a-file-File-size-can-be-100GB)

17.12 BiNode: Consider a simple data structure called BiNode, which has pointers to two other nodes,
public class BiNode {
public SiNode nodel, node2;
public int data;
>
The data structure BiNode could be used to represent both a binary tree (where nodel is the left
node and node2 is the right node) or a doubly linked list (where nodel is the previous node and
node2 is the next node). Implement a method to convert a binary search tree (implemented with
BiNode) into a doubly linked list. The values should be kept in order and the operation should be
performed in place (that is, on the original data structure).


17.13 Re-Space: Oh, no! You have accidentally removed all spaces, punctuation, and capitalization in a
lengthy document, A sentence like " I reset t h e computer. It s t i l l d i d n ' t boot!"
became " i r e s e t t h e c o m p u t e r i t st i l l d i d n t b o o t " . You'll deal with the punctuation and capitalization
later; right now you need to re-insert the spaces. Most of the words are in a dictionary but
a few are not. Given a dictionary (a list of strings) and the document (a string), design an algorithm
to unconcatenate the document in a way that minimizes the number of unrecognized characters.
EXAMPLE;
Input: j e s s l o o k e d j u s t l i k e t i m h e r b r o t h er
Output: j e s s looked j u s t l i k e t u n her b r o t h e r (7 unrecognized characters)


17.14 Smallest K: Design an algorithm to find the smallest K numbers in an array.

ref:
  1. [k largest(or smallest) elements in an array](https://www.geeksforgeeks.org/k-largestor-smallest-elements-in-an-array/)

17.15 Longest Word: Given a list of words, write a program to find the longest word made of other words
in the list.
EXAMPLE
Input: c a t , banana, dog, nana, walk, walker, dogwalker
Output: dogwalker

ref: 
  1. [Program for length of the longest word in a sentence](https://www.geeksforgeeks.org/program-display-number-characters-longest-word-sentence/)

17.16 The Masseuse: A popular masseuse receives a sequence of back-to-back appointment requests
and is debating which ones to accept. She needs a 15-minute break between appointments and
therefore she cannot accept any adjacent requests. Given a sequence of back-to-back appointment
requests (all multiples of 15 minutes, none overlap, and none can be moved), find the optimal
(highest total booked minutes) set the masseuse can honor. Return the number of minutes.
EXAMPLE
Input; {30, 15, 60, 75, 45, 15, 15, 45}
Output: 180 minutes ({30, 60, 45, 4 5 } ) .


17.17 Multi Search: Given a string b and an array of smaller strings T, design a method to search b for
each small string inT,

ref:
  1. [Anagram Substring Search (Or Search for all permutations)](https://www.geeksforgeeks.org/anagram-substring-search-search-permutations/)
  
  2. [Given a string s and an array of smaller strings, T, how to design a method to search s for each small string in T](https://stackoverflow.com/questions/1490523/given-a-string-s-and-an-array-of-smaller-strings-t-how-to-design-a-method-to-s)

17.18 Shortest Supersequence: You are given two arrays, one shorter (with all distinct elements) and one
longer. Find the shortest subarray in the longer array that contains all the elements in the shorter
array. The items can appear in any order.
EXAMPLE
Input: { 1 , 5, 9} | {7, S, 9, 0, 2, 3, 5. 7. 9. 1. 1, 5, 8, 8, 9, 7}
Output: [ 7 , 10] (the underlined portion above)

ref:
  1. [Find smallest subarray that contains all elements in same order](https://www.geeksforgeeks.org/find-smallest-subarray-contains-elements-order/)

  2. [Maximum length of subarray such that all elements are equal in the subarray](https://www.geeksforgeeks.org/maximum-length-of-subarray-such-that-all-elements-are-equal-in-the-subarray/)

17.19 Missing Two: You are given an array with all the numbers from 1 to N appearing exactly once,
except for one number that is missing. How can you find the missing number in 0(N) time and
0 ( 1 ) space? What if there were two numbers missing?

ref:
  1. [Find the missing and repeating number](https://www.geeksforgeeks.org/find-a-repeating-and-a-missing-number/)

  2. [136. Single Number](https://leetcode.com/problems/single-number/)

  3. [2150. Find All Lonely Numbers in the Array](https://leetcode.com/problems/find-all-lonely-numbers-in-the-array/)

17.20 Continuous Median: Numbers are randomly generated and passed to a method. Write a program
to find and maintain the median value as new values are generated.

ref:
  1. [Median in a stream of integers (running integers)](https://www.geeksforgeeks.org/median-of-stream-of-integers-running-integers/)

  2. [Median of Stream of Running Integers using STL](https://www.geeksforgeeks.org/median-of-stream-of-running-integers-using-stl/)
  
  3. [295. Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/)

  4. [Find median of randomly generated numbers](https://stackoverflow.com/questions/25280679/find-median-of-randomly-generated-numbers)


17.21 Volume of Histogram: Imagine a histogram (bar graph). Design an algorithm to compute the
volume of water it could hold if someone poured water across the top. You can assume that each
histogram bar has width 1.
EXAMPLE (Black bars are the histogram. Gray is water.)
Input: {0., 0, 4j 0, 0, 6, 0, 0, 3, 0, 5, 0, 1, 0, 0, 0}
0 0 4 0 0 6 0 0 3 0 5 0 1 0 0 0
Output; 26

ref:
  1. [Largest Rectangular Area in a Histogram using Stack](https://www.geeksforgeeks.org/largest-rectangular-area-in-a-histogram-using-stack/)

  2. [Add water between in a bar chart](https://stackoverflow.com/questions/43398839/add-water-between-in-a-bar-chart)

  3. [84. Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/)

17.22 Word Transformer: Given two words of equal length that are in a dictionary, write a method to
transform one word into another word by changing only one letter at a time.The new word you get
in each step must be in the dictionary.
EXAMPLE
Input: DAMP, LIKE
Output: DAMP -> LAMP -> LIMP -> LIME -> LIKE


17.23 Max Black Square: Imagine you have a square matrix, where each cell (pixel) is either black or white
Design an algorithm to find the maximum subsquare such that all four borders are filled with black
pixels.


17.24 Max Submatrix: Given an NxN matrix of positive and negative integers, write code to find the
subrnatrix with the largest possible sum.

ref:
  1. [Maximum sum submatrix](https://www.geeksforgeeks.org/maximum-sum-submatrix/)

  2. [Given an n x n square matrix, find sum of all sub-squares of size k x k](https://www.geeksforgeeks.org/given-n-x-n-square-matrix-find-sum-sub-squares-size-k-x-k/)

  3. [1074. Number of Submatrices That Sum to Target](https://leetcode.com/problems/number-of-submatrices-that-sum-to-target/)


17.25 Word Rectangle: Given a list of millions of words, design an algorithm to create the largest possible
rectangle of letters such that every row forms a word (reading left to right) and every column forms
a word (reading top to bottom). The words need not be chosen consecutively from the list, but all
rows must be the same length and all columns must be the same height.


17.26 Sparse Similarity: The similarity of two documents (each with distinct words) is defined to be the
size of the intersection divided by the size of the union. For example, if the documents consist of
integers, the similarity of { I , 5, 3} and { 1 , 7, 2, 3} is 0.4, because the intersection has size
2 and the union has size 5.
We have a long list of documents (with distinct values and each with an associated ID) where the
similarity is believed to be "sparse."That is, any two arbitrarily selected documents are very likely to
have similarity 0. Design an algorithm that returns a list of pairs of document IDs and the associated
similarity.
Print only the pairs with similarity greater than 0, Empty documents should not be printed at all. For
simplicity, you may assume each document is represented as an array of distinct integers.
EXAMPLE
Input:
13: {14j 15, 100, 9, 3}
16: <32, 1, 9, 3, 5}
19: {15, 29, 2, 6, 8, 7}
24: {7, 10}
Output:
ID1, ID2 : SIMILARITY
13, 19 : 0.1
13, 16 : 0.25
19, 24 : 0.14285714285714285


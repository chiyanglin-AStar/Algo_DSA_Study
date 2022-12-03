#  Cracking Code interview

# Table of Contents

[0.General](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#General)

[1.Arrays and String](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Arrays-and-String)

   [MIT 2. Data Structures and Dynamic Arrays](https://www.youtube.com/watch?v=CHhwJjR0mZA&list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY&index=3&t=11s)

   [Hash Table in C/C++ - A Complete Implementation](https://www.digitalocean.com/community/tutorials/hash-table-in-c-plus-plus)

   [C++ program for hashing with chaining](https://www.geeksforgeeks.org/c-program-hashing-chaining/)
   
[2.Linked List](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Linked-List)

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
Hints: #44, #117, #132

ref: 
  1. [Determine if a string has all Unique Characters](https://www.geeksforgeeks.org/determine-string-unique-characters/)

1.2 Check Permutation: Given two strings, write a method to decide if one is a permutation of the other.
Hints: #84, #122, #131

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
Hints: #53,0118

ref: 

  1. [URLify a given string (Replace spaces with %20)](https://www.geeksforgeeks.org/urlify-a-given-string-replace-spaces-with-%20/)

  2. [Amazon | Phone screen | URLify a given string (replace spaces with %20)](https://leetcode.com/discuss/interview-question/124608/amazon-phone-screen-urlify-a-given-string-replace-spaces-with-20)

1.4 Palindrome Permutation: Given a string, write a function to check if it is a permutation of a palindrome.
A palindrome is a word or phrase that is the same forwards and backwards. A permutation is a rearrangement of letters. The palindrome does not need to be limited to just dictionary words.
EXAMPLE
Input: Tact Coa
Output: True (permutations: "taco cat", "atco e t a " , etc.)
Hints: #106, h 0134, § 136

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
Hints: #92, if 110

ref: 

  1. [String Compression](https://kodr.me/en/string-compression)
     
  2. [443. String Compression](https://leetcode.com/problems/string-compression/)

1.7 Rotate Matrix: Given an image represented by an NxN matrix, where each pixel in the image is 4
bytes, write a method to rotate the image by 90 degrees. Can you do this in place?
Hints: «51,0100

ref: 

  1. [Inplace rotate square matrix by 90 degrees | Set 1](https://www.geeksforgeeks.org/inplace-rotate-square-matrix-by-90-degrees/)

  2. [48. Rotate Image](https://leetcode.com/problems/rotate-image/)

1.8 Zero Matrix: Write an algorithm such that if an element in an MxN matrix is 0, its entire row and column are set to 0.
Hints: #17, #74, #102

ref: 
  1. [73. Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/)

1.9 String Rotation; Assume you have a method i s S u b s t r i n g which checks if one word is a substring
of another. Given two strings, si and s2, write code to check if s2 is a rotation of si using only one
call to i s S u b s t r i n g [e.g., "water b o t t l e " is a rotation o P ' e r b o t t l e w a t " ) ,
Hints: #34, #88,#W4

ref:
  1. [796. Rotate String](https://leetcode.com/problems/rotate-string/)
 
Additional Questions: Object-Oriented Design (#7.12), Recursion (#8.3), Sorting and Searching (#10.9), C++
(#12.11), Moderate Problems (#16.8, #16.17, #16,22), Hard Problems (#17.4, #17.7, #17.13, #17.22, #17,26).
Hints start on page 653.

# Linked List
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

2.1 Remove Dups: Write code to remove duplicates from an unsorted linked list.
FOLLOW UP
How would you solve this problem if a temporary buffer is not allowed?
Hints: #9, #40

2.2 Return Kth to Last: Implement an algorithm to find the kth to last element of a singly linked list.
Hints: #8, #25, #41, #67, #126

2.3 Delete Middle Node: Implement an algorithm to delete a node in the middle (i.e., any node but
the first and last node, not necessarily the exact middle) of a singly linked list, given only access to
that node.
EXAMPLE
Input: the node c from the linked list a - >b- >c - >d - >e- >f
Result: nothing is returned, but the new linked list looks like a - > b - > d - > e - > f
Hints: #72

2.4 Partition: Write code to partition a linked list around a value x, such that all nodes less than x come
before all nodes greater than or equal to x. Ifxis contained within the list, the values of x only need
to be after the elements less than x (see below). The partition element x can appear anywhere in the
"right partition"; it does not need to appear between the left and right partitions.
EXAMPLE
Input: 3 -> 5 -> 8 -> 5 -> 10 -> 2 -> 1 [partition = 5]
Output: 3 -> 1 -> 2 -> 10 -> 5 -> 5 -> 8
Hints: #3, #24

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
Hints: #7, #30, #71 #95, #109

2.6 Palindrome: Implement a function to check if a linked list is a palindrome.
Hints: #5, #13, #29, #61, #101
pg 216

2.7 Intersection; Given two (singly) linked lists, determine if the two lists intersect. Return the intersecting
node. Note that the intersection is defined based on reference, not value. That is, if the kth
node of the first linked list is the exact same node (by reference) as the j t h node of the second
linked list, then they are intersecting.
Hints: #20, #45, #55, #65, #76, #93, #1 1 1, #120, #129

2.8 Loop Detection: Given a circular linked list, implement an algorithm that returns the node at the
beginning of the loop.
DEFINITION
Circular linked list: A (corrupt) linked list in which a node's next pointer points to an earlier node, so
as to make a loop in the linked list.
EXAMPLE
Input: A - > 8 - > C - > D - > E - > C [the same C as earlier]
Output: C
Hints: #50, #69, #83, #90
Additional Questions: Trees and Graphs (#4,3), Object-Oriented Design (#7.12), System Design and Scalability
(#9.5), Moderate Problems (#16.25), Hard Problems (#17.12).
Hints start on page 653.

# Stack Queue
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions

3.1 Three in One: Describe how you could use a single array to implement three stacks.
Hints: #2, #12, #38, #58

3.2 Stack Min: How would you design a stack which, in addition to push and pop, has a function min
which returns the minimum eiement? Push, pop and min should ail operate in 0 ( 1 ) time.
Hints: #27, #59, #78

3.3 Stack of Plates: Imagine a (literal) stack of plates. If the stack gets too high, it might topple.
Therefore, in real life, we would likely start a new stack when the previous stack exceeds some
threshold. Implement a data structure SetOfStacks that mimics this. SetOfStacks should be
composed of several stacks and should create a new stack once the previous one exceeds capacity.
SetOfStacks . p u s h ( ) and SetOfStacks . p o p ( ) should behave identically to a single stack
(that is, pop( ) should return the same values as it would if there were just a single stack).
FOLLOW UP
Implement a function popAt( i n t index) which performsa pop operation on a specific sub-stack.
Hints: #64, #81

3.4 Queue via Stacks: Implement a MyQueue class which implements a queue using two stacks.
Hints: #98, #114
pg 236

3.5 Sort Stack: Write a program to sort a stack such that the smallest items are on the top. You can use
an additional temporary stack, but you may not copy the elements into any other data structure
(such as an array). The stack supports the following operations: push, pop, peek, and is Empty.
Hints: #15, »32,043

3.6 Animal SheltenAn animal shelter, which holds only dogs and cats, operates on a strictly "first in, first
out" basis. People must adopt either the "oldest" (based on arrival time) of all animals at the shelter,
or they can select whether they would prefer a dog or a cat (and will receive the oldest animal of
that type). They cannot select which specific animal they would like. Create the data structures to
maintain this system and implement operations such as enqueue, dequeueAny, dequeueDog,
and dequeueCat.You may use the built-in L i n k e d L i s t data structure.
Hints: #22, #56, #63
Additional Questions: Linked Lists (#2.6), Moderate Problems (#16.26), Hard Problems (#17.9).
Hints start on page 653.

# Tree Graphs
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

4,1 Route Between Nodes: Given a directed graph, design an algorithm to find out whether there is a
route between two nodes.
Hints:

4,2 Minimal Tree: Given a sorted (increasing order) array with unique integer elements, write an algorithm
to create a binary search tree with minimal height.
Hints: /* 19,473,0116

4.3 List of Depths: Given a binary tree, design an algorithm which creates a linked list of all the nodes
at each depth (e.g., if you have a tree with depth D, you'll have D linked lists).
Hints: #107, #123, #135

4.4 Check Balanced: Implement a function to check if a binary tree is balanced. For the purposes of
this question, a balanced tree is defined to be a tree such that the heights of the two subtrees of any
node never differ by more than one.
Hints: #21, #33, #49, #105, #124

4.5 Validate BST: Implement a function to check if a binary tree is a binary search tree.
Hints: #35, #57, #86, #113, #128

4.6 Successor: Write an algorithm to find the "next" node (i.e., in-order successor) of a given node in a
binary search tree. You may assume that each node has a link to its parent.
Hints: #79, #91

4.7 Build Order: You are given a list of projects and a list of dependencies (which is a list of pairs of
projects, where the second project is dependent on the first project). Ail of a project's dependencies
must be built before the project is. Find a build order that will allow the projects to be built. If there
is no valid build order, return an error.
EXAMPLE
Input:
p r o j e c t s : a, bj c, d, e, f
dependencies: (a, d), ( f , b ) , (b, d ) , ( f , a ) , (d, c)
Output: F, e, a, b, dj c
Hints: #26, #47, #60, #85, #125, #133

4.8 First Common Ancestor: Design an algorithm and write code to find the first common ancestor
of two nodes in a binary tree. Avoid storing additional nodes in a data structure. NOTE: This is not
necessarily a binary search tree.
Hints: #10, # 16, #28, #36, #46, #70, #80, #96

4.9 BST Sequences: A binary search tree was created by traversing through an array from left to right
and inserting each element. Given a binary search tree with distinct elements, print all possible
arrays that could have led to this tree.
EXAMPLE
Input:
Output: {2, 1, 3},{2t 3, 1}
Hints: #39, #48, #66, #82

4.10 Check Subtree: T1 and T2 are two very large binary trees, with T1 much bigger than T2. Create an
algorithm to determine if 12 is a subtree o f T l .
AtreeT2 is a subtree of T1 if there exists a node n in T1 such that the subtree of n is identical to 12,
That is, if you cut off the tree at node n, the two trees would be identical.
Hints: H »31,

4.11 Random Node: You are implementing a binary tree class from scratch which, in addition to
i n s e r t , f i n d , and d e l e t e , has a method getRandomNode() which returns a random node
from the tree. All nodes should be equally likely to be chosen. Design and implement an algorithm
for getRandomNode, and explain how you would implement the rest of the methods.
Hints: #42, #54, #62, #75, #89, #99, #112, #119

4.12 Paths with Sum: You are given a binary tree in which each node contains an integer value (which
might be positive or negative). Design an algorithm to count the number of paths that sum to a
given value. The path does not need to start or end at the root or a leaf, but it must go downwards
(traveling only from parent nodes to child nodes).
Hints: #6, # 14, #52, #68, #77, #87, #94, #103, #108, #115
pg272
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

5.2 Binary to String: Given a reai number between 0 and 1 (e.g., 0.72) that is passed in as a double, print
the binary representation. If the number cannot be represented accurately in binary with at most 32
characters, print "ERROR."
Hlnts:#143,#167,#173, #269, #297

5.3 Flip Bit to Win: You have an integer and you can flip exactly one bit from a 0 to a 1, Write code to
find the length of the longest sequence of Is you could create.
EXAMPLE
Input: 1775 (or: 11011101111)
Output: 8
Hints: #159, #226, #314, #352

5.4 Next Number: Given a positive integer, print the next smallest and the next largest number that
have the same number of 1 bits in their binary representation.
Hints: #147, #175, #242, #312, #339, #358, #375, #390
5.5 Debugger: Explain what thefollowing code does: ( (n & ( n - 1 ) ) == 0).
Hints: # 15 J, #202, #261, #302, #346, #372, #383, #398

5.6 Conversion: Write a function to determine the number of bits you would need to flip to convert
integer A to integer B.
EXAMPLE
Input: 29 ( o r : 11101), 15 ( o r : 01111)
Output: 2
Hints: #336, #369

5.7 PairwiseSwap: Write a program to swap odd and even bits in an integer with as few instructions as
possible (e.g., bit 9 and bit 1 are swapped, bit 2 and bit 3 are swapped, and so on).
Hints: #145, #248, #328, #355

5.8 Draw Line: A monochrome screen is stored as a single array of bytes, allowing eight consecutive
pixels to be stored in one byte. The screen has width w, where w is divisible by 8 (that is, no byte will
be split across rows). The height of the screen, of course, can be derived from the length of the array
and the width. Implement a function that draws a horizontal line from ( x l , y) to ( x 2 , y).
The method signature should look something like:
drawl ine(byte[ ] screen., int width, int x l , i n t X2, i n t y)
Hints: #366, #381, #384, #391
Additional Questions: Arrays and Strings (#1.1, #1.4, #1.8), Math and Logic Puzzles (#6.10), Recursion (#8.4,
#8.14), Sorting and Searching (#10.7, #10.8), C++(#12.10), Moderate Problems (#16.1, #16.7), Hard Problems
(#17.1).
Hints start on page 662.

# Math and Logic Puzzles
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Object-Oriented Design
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

7.1 Deck of Cards: Design the data structures for a generic deck of cards. Explain how you would
subclass the data structures to implement blackjack.
Hints: »153, »275


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
Hints: 0363
pg 307

7.3 Jukebox: Design a musical jukebox using object-oriented principles.
Hints; if 198

7.4 Parking Lot: Design a parking lot using object-oriented principles.
Hints: #258

7.5 Online Book Reader: Design the data structures for an online book reader system.
Hints: #344

7.6 Jigsaw: Implement an NxN jigsaw puzzle. Design the data structures and explain an algorithm to
solve the puzzle. You can assume that you have a f i t s W i t h method which, when passed two
puzzle edges, returns true if the two edges belong together.
Hints: #192, #238, #283

7.7 Chat Server: Explain how you would design a chat server. In particular, provide details about the
various backend components, classes, and methods. What wouid be the hardest problems to solve?
Hints: #213, #245, #271

7.8 Othello: Othello is played as follows: Each Othello piece is white on one side and black on the other.
When a piece is surrounded by its opponents on both the left and right sides, or both the top and
bottom, it is said to be captured and its color is flipped. On your turn, you must capture at least one
of your opponent's pieces. The game ends when either user has no more valid moves. The win is
assigned to the person with the most pieces. Implement the object-oriented design for Othello.
Hints: #179, #228

7.9 Circular Array: Implement a C i r c u l a r A r r a y class that supports an array-like data structure which
can be efficiently rotated. If possible, the class should use a generic type (also called a template), and
should support iteration via the standard f o r (Obj o : c i r c u l a r A r r a y ) notation.
Hints: #389
128

# Recursion and Dynamic Programming
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# System Design and Scalability
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Sorting and Searching
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Testing
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# C and Cplusplus
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions
12.1 Last K Lines: Write a method to print the last K lines of an input file using C++.
Hints: #449, #459

12.2 Reverse String: Implement a function v o i d reverse( c h a r * s t r ) in C or C++which reverses
a null-terminated string.
Hints: #410, #452

12.3 Hash Table vs. STL Map: Compare and contrast a hash table and an STL map. How is a hash table
implemented? If the number of inputs is small, which data structure options can be used instead of
a hash table?
Hints: #423

12.4 Virtual Functions: How do virtual functions work in C++?
Hints: #463

12.5 Shallow vs. Deep Copy: What is the difference between deep copy and shallow copy? Explain how
you would use each.
Hints: if 44 5

12.6 Volatile: What is the significance of the keyword "volatile" in C?
Hints: #456

12.7 Virtual Base Class: Why does a destructor in base class need to be declared v i r t u a l ?
Hints; #421, #460

12.8 Copy Node; Write a method that takes a pointer to a Node structure as a parameter and returns a
complete copy of the passed in data structure. The Node data structure contains two pointers to
other Nodes.
Hints: #427, #462

12.9 Smart Pointer: Write a smart pointer class. A smart pointer is a data type, usually implemented with
templates, that simulates a pointer while also providing automatic garbage collection. It automatically
counts the number of references to a Smart P o i n t er<T*> object and frees the object of type
T when the reference count hits zero.
Hints: #402, #438, #453

12.10 Malloc: Write an aligned malloc and free function that supports allocating memory such that the
memory address returned is divisible by a specific power of two.
EXAMPLE
a l i g n j n a l l o c (1000,128) will return a memory address that is a multiple of 128 and that points
to memory of size 1000 bytes.
a l i g n e d _ f r e e ( ) will free memory allocated by a l i g n j u a l l o c .
Hints: #413, if432, #440

12.11 2D Alloc: Write a function in C called riy2DAlloc which allocates a two-dimensional array. Minimize
the number of calls to m a l l o c and make sure that the memory is accessible by the notation
a r r [ i ] [ j ] .
Hints: #406, #418, #426
Additional Questions: Linked Lists (#2.6), Testing (#11.1), Java (#13.4), Threads and Locks (#15.3).
Hints start on page 676.

# Databases
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Threads and Locks
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Moderate
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Hard
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)



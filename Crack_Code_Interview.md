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

[Remove duplicates from an unsorted linked list](https://www.geeksforgeeks.org/remove-duplicates-from-an-unsorted-linked-list/)

[82. Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/)

2.2 Return Kth to Last: Implement an algorithm to find the kth to last element of a singly linked list.
Hints: #8, #25, #41, #67, #126

[Program for Nth node from the end of a Linked List](https://www.geeksforgeeks.org/nth-node-from-the-end-of-a-linked-list/)

[19. Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)

2.3 Delete Middle Node: Implement an algorithm to delete a node in the middle (i.e., any node but
the first and last node, not necessarily the exact middle) of a singly linked list, given only access to
that node.
EXAMPLE
Input: the node c from the linked list a - >b- >c - >d - >e- >f
Result: nothing is returned, but the new linked list looks like a - > b - > d - > e - > f
Hints: #72

[Delete middle of linked list](https://www.geeksforgeeks.org/delete-middle-of-linked-list/)

[2095. Delete the Middle Node of a Linked List](https://leetcode.com/problems/delete-the-middle-node-of-a-linked-list/)

2.4 Partition: Write code to partition a linked list around a value x, such that all nodes less than x come
before all nodes greater than or equal to x. Ifxis contained within the list, the values of x only need
to be after the elements less than x (see below). The partition element x can appear anywhere in the
"right partition"; it does not need to appear between the left and right partitions.
EXAMPLE
Input: 3 -> 5 -> 8 -> 5 -> 10 -> 2 -> 1 [partition = 5]
Output: 3 -> 1 -> 2 -> 10 -> 5 -> 5 -> 8
Hints: #3, #24

[Partitioning a linked list around a given value and keeping the original order](https://www.geeksforgeeks.org/partitioning-a-linked-list-around-a-given-value-and-keeping-the-original-order/)

[86. Partition List](https://leetcode.com/problems/partition-list/)

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

[Add two numbers represented by Linked List](https://www.geeksforgeeks.org/add-two-numbers-represented-by-linked-list/)

[2. Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)

2.6 Palindrome: Implement a function to check if a linked list is a palindrome.
Hints: #5, #13, #29, #61, #101
pg 216

[Function to check if a singly linked list is palindrome](https://www.geeksforgeeks.org/function-to-check-if-a-singly-linked-list-is-palindrome/)

[234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)

2.7 Intersection; Given two (singly) linked lists, determine if the two lists intersect. Return the intersecting
node. Note that the intersection is defined based on reference, not value. That is, if the kth
node of the first linked list is the exact same node (by reference) as the j t h node of the second
linked list, then they are intersecting.
Hints: #20, #45, #55, #65, #76, #93, #1 1 1, #120, #129

[Write a function to get the intersection point of two Linked Lists](https://www.geeksforgeeks.org/write-a-function-to-get-the-intersection-point-of-two-linked-lists/)

[160. Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)

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

[Detect loop in a linked list](https://www.geeksforgeeks.org/detect-loop-in-a-linked-list/)

[141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)

# Stack Queue
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions

3.1 Three in One: Describe how you could use a single array to implement three stacks.
Hints: #2, #12, #38, #58

[How to efficiently implement k stacks in a single array?](https://www.geeksforgeeks.org/efficiently-implement-k-stacks-single-array/)

[How to implement 3 stacks with one array?](https://stackoverflow.com/questions/4770627/how-to-implement-3-stacks-with-one-array)

3.2 Stack Min: How would you design a stack which, in addition to push and pop, has a function min
which returns the minimum eiement? Push, pop and min should ail operate in 0 ( 1 ) time.
Hints: #27, #59, #78

[Design a stack that supports getMin() in O(1) time and O(1) extra space](https://www.geeksforgeeks.org/design-a-stack-that-supports-getmin-in-o1-time-and-o1-extra-space/)

[155. Min Stack](https://leetcode.com/problems/min-stack/)

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

Interview Questions
6.1 The Heavy Pill: You have 20 bottles of pills. 19 bottles have 1.0 gram pills, but one has pills of weight
1.1 grams. Given a scale that provides an exact measurement, how would you find the heavy bottle?
You can only use the scale once.
Hints: # 186, #252, #319, #387

6.2 Basketball: You have a basketball hoop and someone says that you can play one of two games.
Game 1: You get one shot to make the hoop.
Game 2: You get three shots and you have to make two of three shots.
If p is the probability of making a particular shot, for which values of p should you pick one game
or the other?
Hints: #181, #239, #284, #323
pg 2C>()

6.3 Dominos: There is an 8x8 chessboard in which two diagonally opposite corners have been cut off.
You are given 31 dominos, and a single domino can cover exactly two squares. Can you use the 31
dominos to cover the entire board? Prove your answer (by providing an example or showing why
it's impossible).
Hints: #367, #397
pg 291

6.4 Ants on aTriangie: There are three ants on different vertices of a triangle. What is the probability of
coliision (between any two or all of them) if they start walking on the sides of the triangle? Assume
that each ant randomly picks a direction, with either direction being equally likely to be chosen, and
that they walk at the same speed.
Similarly, find the probability of collision with n ants on an n-vertex polygon.
Hints: #157, #195, #296
291

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
Hints: #218, #282, #34 7, #370

6.7 The Apocalypse: In the new post-apocalyptic world, the world queen is desperately concerned
about the birth rate. Therefore, she decrees that all families should ensure that they have one girl or
else they face massive fines. If all families abide by this policy—that is, they have continue to have
children until they have one girl, at which point they immediately stop—what will the gender ratio
of the new generation be? (Assume that the odds of someone having a boy or a girl on any given
pregnancy is equal.) Solve this out logically and then write a computer simulation of it.
Hints: #154, #160, #171, #188, #201

6.8 The Egg Drop Problem: There is a building of 100 floors. If an egg drops from the Nth floor or
above, it will break. If it's dropped from any floor below, it will not break. You're given two eggs. Find
N, while minimizing the number of drops for the worst case.
Hints; #156, #233, #294, #333, #357, #374, #395

6.9 100 Lockers: There are 100 closed lockers in a hallway. A man begins by opening all 100 lockers.
Next, he doses every second locker. Then, on his third pass, he toggles every third locker (closes it if
it is open or opens it if it is closed). This process continues for 100 passes, such that on each pass i,
the man toggles every i t h locker. After his 100th pass in the hallway, in which he toggles only locker
#100, how many lockers are open?
Hints:#139, #172, #264, #306

6.10 Poison: You have 1000 bottles of soda, and exactly one is poisoned. You have 10 test strips which
can be used to detect poison. A single drop of poison will turn the test strip positive permanently.
You can put any number of drops on a test strip at once and you can reuse a test strip as many times
as you'd like (as long as the results are negative). However, you can only run tests once per day and
it takes seven days to return a result. How would you figure out the poisoned bottle in as few days
as possible?
FOLLOW UP
Write code to simulate your approach.
Hints: #146, #163, #183, #191, #205, #221, #230, #241, #249
Additional Problems: Moderate Problems (#16.5), Hard Problems (#17.19)
Hints start on page 662

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

Interview Questions
8.1 Triple Step: A child is running up a staircase with n steps and can hop either 1 step, 2 steps, or 3
steps at a time, implement a method to count how many possible ways the child can run up the
stairs.
Hin ts: #152, #178, #2 7 7, #237, #262, #359

8.2 Robot in a Grid: Imagine a robot sitting on the upper left corner of grid with r rows and c columns.
The robot can only move in two directions, right and down, but certain cells are "off limits" such that
the robot cannot step on them. Design an algorithm to find a path for the robot from the top left to
the bottom right.
Hints: #331, #360, #388

8.3 Magic Index: A magic index in an array A [ 0 . . . n - 1 ] is defined to be an index such that A [ i ] =
i. Given a sorted array of distinct integers, write a method to find a magic index, if one exists, in
array A.
FOLLOW UP
What if the values are not distinct?
Hints: #170, #204, #240, #286, #340

8.4 Power Set: Write a method to return all subsets of a set.
Hints: #273, #290, #338, #354, #373

8.5 Recursive Multiply: Write a recursive function to multiply two positive integers without using the
* operator. You can use addition, subtraction, and bit shifting, but you should minimize the number
of those operations.

Hints: #166, #203, #227, #234, #246, #280

8.6 Towers of Hanoi: In the classic problem of the Towers of Hanoi, you have 3 towers and N disks of
different sizes which can slide onto any tower. The puzzle starts with disks sorted in ascending order
of size from top to bottom (i.e., each disk sits on top of an even larger one). You have the following
constraints:
(1) Only one disk can be moved at a time.
(2) A disk is slid off the top of one tower onto another tower.
(3) A disk cannot be placed on top of a smaller disk.
Write a program to move the disks from the first tower to the last using stacks.
Hints: #144, #224, #250, #272, #318

8.7 Permutations without Dups: Write a method to compute all permutations of a string of unique
characters.
Hints: #150, #185, #200, #267, #278, #309, #335, #356

8.8 Permutations with Dups: Write a method to compute all permutations of a string whose characters
are not necessarily unique. The list of permutations should not have duplicates.
Hints: #161, #190, #222, #255

8.9 Parens; implement an algorithm to print all valid (e.g., properly opened and closed) combinations
of n pairs of parentheses.
EXAMPLE
Input: 3
O u t p u t : ( ( ( ) ) ) , ( 0 0 : ) , ( ( » ( > , 0 ( 0 ) , 0 0 0
Hints: #138, #174, #187, #209, #243, #265, #295

8.10 Paint Fill: Implement the "paint fill"function that one might see on many image editing programs.
That is, given a screen (represented by a two-dimensional array of colors), a point, and a new color,
fill in the surrounding area until the color changes from the original cofor.
Hints: #364, #382

8.11 Coins: Given an infinite number of quarters (25 cents), dimes (10 cents), nickels (5 cents), and
pennies (1 cent), write code to calculate the number of ways of representing n cents.
Hints #300, #324, #343, #380, #394

8.12 Eight Queens: Write an algorithm to print all ways of arranging eight queens on an 8x8 chess board
so that none of them share the same row, column, or diagonal. In this case, "diagonal" means all
diagonals, not just the two that bisect the board.
Hints: #308, #350, #371

8.13 Stack of Boxes: You have a stack of n boxes, with widths w4, heights ht , and depths dr The boxes
cannot be rotated and can only be stacked on top of one another if each box in the stack is strictly
larger than the box above it in width, height, and depth. Implement a method to compute the
height of the tallest possible stack. The height of a stack is the sum of the heights of each box.
Hints: #155, #194, #214, #260, #322, #368, #378

8.14 Boolean Evaluation: Given a boolean expression consisting of the symbols 0 (false), 1 (true), &
(AND), | (OR), and A (XOR), and a desired boolean result value r e s u l t , implement a function to
count the number of ways of parenthesizing the expression such that it evaluates to r e s u l t ,
EXAMPLE
c o u n t E v a l ( " l A e | 0 j l M , f a l s e ) -> 2
c o u n t E v a l ( " 0 & 0 & 0 & l A l | 0 " , t r u e ) -> 10
Hints: #148, #168, #197, #305, #327
Additional Questions: Linked Lists (#2.2, #2.5, #2.6), Stacks and Queues (#3.3), Trees and Graphs (#4.2, #4,3,
#4.4, #4.5, #4,8, #4.10, #4.11, #4.12), Math and Logic Puzzles (#6,6), Sorting and Searching (#10.5, #10.9,
#10.10), C++ (#12.8), Moderate Problems (#16,11), Hard Problems (#17,4, #17.6, #17.8, #17.12, #17.13,
#17.15,#17.16,#17.24,#17.25).
Hints start on page 662

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
Hints: #385, #396

9.2 Social Network: How would you design the data structures for a very large social network like Facebook
or Linkedln? Describe how you would design an algorithm to show the shortest path between
two people (e.g.. Me -> Bob -> Susan -> Jason -> You).
Hints: #270, #285, #304, #321

9.3 Web Crawler: If you were designing a web crawler, how would you avoid getting into infinite loops?
Hints: #334, #353, #365

9.4 Duplicate URLs: You have 10 billion URLs. How do you detect the duplicate documents? In this
case, assume "duplicate" means that the URLs are identical.
Hints: #326, #347


9.5 Cache: Imagine a web server for a simplified search engine. This system has 100 machines to
respond to search queries, which may then call out using processSearch( s t r i n g query) to
another cluster of machines to actually get the result.The machine which responds to a given query
is chosen at random, so you cannot guarantee that the same machine will always respond to the
same request. The method processSearch is very expensive. Design a caching mechanism for
the most recent queries. Be sure to explain how you would update the cache when data changes.
Hints: #259, #274, #293, #311

9.6 Sales Rank: A large eCommerce company wishes to list the best-setling products, overall and by
category. For example, one product might be the #1056th best-selling product overall but the #13th
best-selling product under "Sports Equipment" and the #24th best-seiling product under "Safety."
Describe how you would design this system.
Hints: 0142, #158, #176, #189, #208, #223, #236, #244

9.7 Personal Financial Manager: Explain how you would design a personal financial manager (like
Mint.com). This system would connect to your bank accounts, analyze your spending habits, and
make recommendations.
Hints: #162, #180, #199, #212, #247, #276

9.8 Pastebin: Design a system like Pastebin, where a user can enter a piece of text and get a randomly
generated URL to access it.
Hints:#165, #184, #206, #232
Additional Questions: Object-Oriented Design (#7.7)
Hints start on page 662.



# Sorting and Searching
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions
10.1 Sorted Merge: You are given two sorted arrays, A and B, where A has a large enough buffer at the
end to hold B. Write a method to merge B into A in sorted order.
Hints: it332

10.2 Group Anagrams: Write a method to sort an array of strings so that all the anagrams are next to
each other.
Hints: #177, #182, #263, #342

10.3 Search in Rotated Array: Given a sorted array of n integers that has been rotated an unknown
number of times, write code to find an element in the array. You may assume that the array was
originally sorted in increasing order,
EXAMPLE
Input: find 5 in [15, 16, 19, 20, 25, 1, 3, 4, 5, 7, 10, 14}
Output: 8 (the index of 5 in the array)
Hints: #298, #310

10.4 Sorted Search, No Size: You are given an array-like data structure L i s t y which lacks a size
method. It does, however, have an elementAt ( i ) method that returns the element at index i in
0 ( 1 ) time, if i is beyond the bounds of the data structure, it returns -1. (For this reason, the data
structure only supports positive integers.) Given a L i s t y which contains sorted, positive integers,
find the index at which an element X occurs. If x occurs multiple times, you may return any index.
Hints: #320, #337, #348

10.5 Sparse Search: Given a sorted array of strings that is interspersed with empty strings, write a
method to find the location of a given string.
EXAMPLE
Input: b a l l , { " a t " , " " , " " , " " , " b a l l " , "", " c a r " , " " , " " , "dad", " " ,
any
Output: 4
Hints: #256

10.6 Sort Big File: Imagine you have a 20 GB file with one string per line. Explain how you would sort
the file.
Hints: #207

10.7 Missing Int: Given an input file with four billion non-negative integers, provide an algorithm to
generate an integer that is not contained in the file. Assume you have 1 GB of memory available for
this task.
FOLLOW UP
What if you have only 10 MB of memory? Assume that ail the values are distinct and we now have
no more than one billion non-negative integers.
Hints: #235, #254, #281

10.8 Find Duplicates: You have an array with all the numbers from 1 to N, where N is at most 32,000.The
array may have duplicate entries and you do not know what N is. With only 4 kilobytes of memory
available, how would you print alt duplicate elements in the array?
Hints; #289, #315

10.9 Sorted Matrix Search: Given an M x N matrix in which each row and each column is sorted in
ascending order, write a method to find an element.
Hints:#193, #211, #229, #251, #266, #279, #288, #291, #303, #317, #330

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
Hints: #301, #376, #392

10.11 Peaks and Valleys: In an array of integers, a "peak" is an element which is greater than or equal to
the adjacent integers and a "valley" is an element which is less than or equal to the adjacent integers.
For example, in the array [5, 8,6, 2, 3,4, 6), {8,6} are peaks and {5, 2} are valleys. Given an array
of integers, sort the array into an alternating sequence of peaks and valleys.
EXAMPLE
Input: IS, 3,1,2, 3)
Output: (5,1,3,2, 3}
Hints: #196, #219, #231, #253, #277, #292, #316
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
Hints: #257, #299, #362

11.2 Random Crashes: You are given the source to an application which crashes when it is run. After
running it ten times in a debugger, you find it never crashes in the same place. The application is
single threaded, and uses only the C standard library. What programming errors could be causing
this crash? How would you test each one?
Hints: #325

11.3 Chess Test: We have the following method used in a chess game: boolean canMoveTo(int x,
i n t y). This method is part of the Piece class and returns whether or not the piece can move to
position ( x , y). Explain how you would test this method.
Hints: #329, #401

11.4 No Test Tools: How would you load test a webpage without using any test tools?
Hints: #313, #345
pi j 419

11.5 Test a Pen; How would you test a pen?
Hints: #140, #164, #220

11.6 Test an ATM: How would you test an ATM in a distributed banking system?
Hints: #210, #225, #268, #349, #393
Hints start on page 662

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

Interview Questions
15.1 Thread vs. Process: What's the difference between a thread and a process?
Hints: #405

15.2 Context Switch: How would you measure the time spent in a context switch?
Hints: #403, #407, #415, #441

15.3 Dining Philosophers: In the famous dining philosophers problem, a bunch of philosophers are
sitting around a circular table with one chopstick between each of them. A philosopher needs
both chopsticks to eat, and always picks up the left chopstick before the right one. A deadlock
could potentially occur if all the philosophers reached for the left chopstick at the same time. Using
threads and locks, implement a simulation of the dining philosophers problem that prevents deadlocks.
Hints:#479,#437

15.4 Deadlock-Free Class: Design a class which provides a lock only if there are no possible deadlocks.
Hints: ft422, #434

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
Hints: #417, #433, #446

15.6 Synchronized Methods: You are given a class with synchronized method A and a normal method
B. If you have two threads in one instance of a program, can they both execute A at the same time?
Can they execute A and B at the same time?
Hints: #429

15.7 FizzBuzz: In the classic problem FizzBuzz, you are told to print the numbers from 1 to n. However,
when the number is divisible by B, print "Fizz". When it is divisible by 5, print "Buzz" When it is divisible
by 3 and 5, print "FizzBuzz". In this problem, you are asked to do this in a multithreaded way.
Implement a multithreaded version of FizzBuzz with four threads. One thread checks for divisibility
of 3 and prints"Fizz". Another thread is responsible for divisibility of 5 and prints "Buzz" A third thread
is responsible for divisibility of 3 and 5 and prints "FizzBuzz". A fourth thread does the numbers.
Hints: #414, #439, #447, #458

# Moderate
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

16.1 Number Swapper: Write a function to swap a number in place (that is, without temporary variables).
Hints: #492,0716, 0737

16.2 Word Frequencies: Design a method to find the frequency of occurrences of any given word in a
book. What if we were running this algorithm multiple times?
Hints: 0489,053$

16.3 Intersection: Given two straight line segments (represented as a start point and an end point),
compute the point of intersection, if any.
Hints: #465, #472, #497, #517, #527

16.4 TicTac Win: Design an algorithm to figure out if someone has won a game of tic-tac-toe.
Hints: #710, #732

16.5 Factorial Zeros: Write an algorithm which computes the number of trailing zeros in n factorial.
Hints: #585, #711, #729, #733, #745

16.6 Smallest Difference: Given two arrays of integers, compute the pair of values (one value in each
array) with the smallest (non-negative) difference. Return the difference.
EXAMPLE
Input: {1, 3,1S, 11, 2}, (23,127, 235,19, 8)
Output: 3. That is, the pair (11,8).
Hints: #632, #670, #679

16.7 Number Max: Write a method that finds the maximum of two numbers. You should not use if-else
or any other comparison operator.
Hints: #473, #513, #707,0728

16.8 English Int: Given any integer, print an English phrase that describes the integer (e.g., "OneThousand,
Two Hundred Thirty Four").
Hints; #502, #588, #688

16.9 Operations: Write methods to implement the multiply, subtract, and divide operations for integers.
The results of all of these are integers. Use only the add operator.
Hints: #572, #600, #613, #648

16.10 Living People: Given a list of people with their birth and death years, implement a method to
compute the year with the most number of people alive. You may assume that all people were born
between 1900 and 2000 (inclusive). If a person was alive during any portion of that year, they should
be included in that year's count. For example. Person (birth = 1908, death = 1909) is included in the
counts for both 1908 and 1909.
Hints: #476, #490, #507, #514, #523, #532, #541, #549, #576

16.11 Diving Board: You are building a diving board by placing a bunch of planks of wood end-to-end.
There are two types of planks, one of length s h o r t e r and one of length longer. You must use
exactly K planks of wood. Write a method to generate all possible lengths for the diving board.
Hints: #690, #700, #715, #722, #740, #747

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
Hints: #466

16.13 Bisect Squares: Given two squares on a two-dimensional plane, find a line that would cut these two
squares in half. Assume that the top and the bottom sides of the square run parallel to the x-axis.
Hints: #468, #479, #528, #560

16.14 Best Line: Given a two-dimensional graph with points on it, find a line which passes the most
number of points.
Hints: #49], #520, #529, #563

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
Hints: #639, #730

16.16 Sub Sort: Given an array of integers, write a method to find indices m and n such that if you sorted
elements m through n, the entire array would be sorted. Minimize n - m (that is, find the smallest
such sequence).
EXAMPLE
Input: lj 2, 4j 7, 10, 11, 1, 12, 6, 7, 16, 18, 19
Output: ( 3 , 9)
Hints: #482, #553, #667, #708, #735, #746

16.17 Contiguous Sequence: You are given an array of integers (both positive and negative). Find the
contiguous sequence with the largest sum. Return the sum.
EXAMPLE
Input:2, -8, 3, -2, 4, -10
Output: 5 ( i . e . , {3, -2, 4})
Hints: #53#551, #567, #594, #614

16.18 Pattern Matching: You are given two strings, p a t t e r n and value.The p a t t e r n string consists of
just the letters a and b, describing a pattern within a string. For example, the string c a t c a t g o c a t g o
matches the pattern aabab (where cat is a and go is b). It also matches patterns like a, ab, and b.
Write a method to determine if v a l u e matches p a t t e r n .
Hints: #63 1, #643, #653, #663, #685, #718, #727

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
Hints: #674, §687, #706, 

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
Hints: #471, #487, #654, #703, #726, #744

16.21 Sum Swap: Given two arrays of integers, find a pair of values (one value from each array) that you
can swap to give the two arrays the same sum.
EXAMPLE
Input:{4,1,2,1,1, 2}and [3,6, 3,3}
Output: {1, 3}
Hints: #545, #557, #564, #571, #583, #592, #602, #606, #635
1 8

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
Hints: It474, #481, #533, #540, #559, #570, #599, #616, #627

16.23 Rand? from Rand5: Implement a method rand7() given rand5( ).That is, given a method that
generates a random number between 0 and 4 (inclusive), write a method that generates a random
number between 0 and 6 (inclusive).
Hints; #505, #574, #637, #668, #697, #720

16.24 Pairs with Sum: Design an algorithm to find all pairs of integers within an array which sum to a
specified value.
Hints: #548, #597, #644, #673

16.25 LRU Cache: Design and build a "least recently used" cache, which evicts the least recently used
item. The cache should map from keys to values (allowing you to insert and retrieve a value associated
with a particular key) and be initialized with a max size. When it is full, it should evict the least
recently used item.
Hints: #524, #630, #694

16.26 Calculator: Given an arithmetic equation consisting of positive integers, +, -, * and / (no parentheses),
compute the result.
EXAMPLE
Input; 2*3+5/6*3+15
Output: 23.5
Hints: #521, #624, #665, #698

# Hard
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

17.1 Add Without Plus: Write a function that adds two numbers. You should not use + or any arithmetic
operators.
Hints: #467, #544, #601, #628, #642, #664, #692, #712, #724

17.2 Shuffle: Write a method toshuffleadeckofcards.lt must be a perfect shuffle—in other words, each
of the 521 permutations of the deck has to be equally likely. Assume that you are given a random
number generator which is perfect.
Hints: #483, #579, #634

17.3 Random Set: Write a method to randomly generate a set of m integers from an array of size n. Each
element must have equal probability of being chosen.
Hints: #494, #596

17.4 Missing Number: An array A contains all the integers from 0 to n, except for one number which
is missing. In this problem, we cannot access an entire integer in A with a single operation. The
elements of A are represented in binary, and the only operation we can use to access them is "fetch
the j t h bit of A[ i ] , " which takes constant time. Write code to find the missing integer. Can you do
it in 0( n) time?
Hints: #610, #659, #683

17.5 Letters and Numbers: Given an array filled with letters and numbers, find the longest subarray with
an equal number of letters and numbers.
Hints: #485, #515, #619, #671, #713

17.6 Count of 2s: Write a method to count the number of 2s that appear in all the numbers between 0
and n (inclusive).
EXAMPLE
Input: 25
Output: 9 (2,12,20, 21, 22, 23, 24 and 25. Note that 22 counts for two 2s.)
Hints: #573, #612, #641

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
Hints: #478, #493, #512, #537, #586, #605, #655, #675, #704

17.8 Circus Tower: A circus is designing a tower routine consisting of people standing atop one another's
shoulders. For practical and aesthetic reasons, each person must be both shorter and lighter
than the person below him or her. Given the heights and weights of each person in the circus, write
a method to compute the largest possible number of people in such a tower.
EXAMPLE
Input (ht, wt): (65, 100) (70, 150) (56, 90) (75, 190) (60, 95) (68, 110)
Output: The longest tower is length 6 and includes from top to bottom:
( 5 6 , 90) (60,95) (65,100) (68,110) (70,150) (75,190)
Hints: #638, #657, #666, #682, #699
pg 546

17.9 Kth Multiple: Design an atgorithm to find the kth number such that the only prime factors are 3, 5,
and 7. Note that 3, 5, and 7 do not have to be factors, but it should not have any other prime factors.
For example, the first several multiples would be {in order) 1,3, 5, 7, 9,15,21.
Hints: #488, #508, #550, #591, #622, #660, #686

17.10 Majority Element: A majority element is an element that makes up more than half of the items in
an array. Given a positive integers array, find the majority element. If there is no majority element,
return -1. Do this in0(N) time and 0 ( 1 ) space.
EXAMPLE
Input: 1 2 5 9 5 9 5 5 5
Output: 5
Hints: #522, #566, #604, #620, #650

17.11 Word Distance: You have a large text file containing words. Given any two words, find the shortest
distance (in terms of number of words) between them in the file. If the operation will be repeated
many times for the same file (but different pairs of words), can you optimize your solution?
Hints: #486, #501, #538, #558, #633

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
Hints: #509, #608, #646, #680, #701 #719

17.13 Re-Space: Oh, no! You have accidentally removed all spaces, punctuation, and capitalization in a
lengthy document, A sentence like " I reset t h e computer. It s t i l l d i d n ' t boot!"
became " i r e s e t t h e c o m p u t e r i t st i l l d i d n t b o o t " . You'll deal with the punctuation and capitalization
later; right now you need to re-insert the spaces. Most of the words are in a dictionary but
a few are not. Given a dictionary (a list of strings) and the document (a string), design an algorithm
to unconcatenate the document in a way that minimizes the number of unrecognized characters.
EXAMPLE;
Input: j e s s l o o k e d j u s t l i k e t i m h e r b r o t h er
Output: j e s s looked j u s t l i k e t u n her b r o t h e r (7 unrecognized characters)
Hints: #496, #623, #656, #677, #739, #749

17.14 Smallest K: Design an algorithm to find the smallest K numbers in an array.
Hints: #470, #530, #552, #593, #625, #647, #661, #678

17.15 Longest Word: Given a list of words, write a program to find the longest word made of other words
in the list.
EXAMPLE
Input: c a t , banana, dog, nana, walk, walker, dogwalker
Output: dogwalker
Hints: #475, #499, #543, #589

17.16 The Masseuse: A popular masseuse receives a sequence of back-to-back appointment requests
and is debating which ones to accept. She needs a 15-minute break between appointments and
therefore she cannot accept any adjacent requests. Given a sequence of back-to-back appointment
requests (all multiples of 15 minutes, none overlap, and none can be moved), find the optimal
(highest total booked minutes) set the masseuse can honor. Return the number of minutes.
EXAMPLE
Input; {30, 15, 60, 75, 45, 15, 15, 45}
Output: 180 minutes ({30, 60, 45, 4 5 } ) .
Hints: #495, #504, #516, #526, #542, #554, #562, #568, #578, #587, #607

17.17 Multi Search: Given a string b and an array of smaller strings T, design a method to search b for
each small string inT,
Hints: #480, #582, #617, #743

17.18 Shortest Supersequence: You are given two arrays, one shorter (with all distinct elements) and one
longer. Find the shortest subarray in the longer array that contains all the elements in the shorter
array. The items can appear in any order.
EXAMPLE
Input: { 1 , 5, 9} | {7, S, 9, 0, 2, 3, 5. 7. 9. 1. 1, 5, 8, 8, 9, 7}
Output: [ 7 , 10] (the underlined portion above)
Hints: #645, #652, #669, #681, #691, #725, #731, #741

17.19 Missing Two: You are given an array with all the numbers from 1 to N appearing exactly once,
except for one number that is missing. How can you find the missing number in 0(N) time and
0 ( 1 ) space? What if there were two numbers missing?
Hints: #503, #590, #609, #626, #649, #672, #689, #696, #702, #717


17.20 Continuous Median: Numbers are randomly generated and passed to a method. Write a program
to find and maintain the median value as new values are generated.
Hints: #519, #546, #575, #709

17.21 Volume of Histogram: Imagine a histogram (bar graph). Design an algorithm to compute the
volume of water it could hold if someone poured water across the top. You can assume that each
histogram bar has width 1.
EXAMPLE (Black bars are the histogram. Gray is water.)
Input: {0., 0, 4j 0, 0, 6, 0, 0, 3, 0, 5, 0, 1, 0, 0, 0}
0 0 4 0 0 6 0 0 3 0 5 0 1 0 0 0
Output; 26
Hints: #629, #640, #651, #658, #662, #676, #693, #734, #742

17.22 Word Transformer: Given two words of equal length that are in a dictionary, write a method to
transform one word into another word by changing only one letter at a time.The new word you get
in each step must be in the dictionary.
EXAMPLE
Input: DAMP, LIKE
Output: DAMP -> LAMP -> LIMP -> LIME -> LIKE
Hints: #506, #535, #556, #580, #598, #618, #738

17.23 Max Black Square: Imagine you have a square matrix, where each cell (pixel) is either black or white
Design an algorithm to find the maximum subsquare such that all four borders are filled with black
pixels.
Hints: #684, #695, #705, #714, #721, #736

17.24 Max Submatrix: Given an NxN matrix of positive and negative integers, write code to find the
subrnatrix with the largest possible sum.
Hints: #469, #S11, #525, #539, #565, #581, #595, #615, #621

17.25 Word Rectangle: Given a list of millions of words, design an algorithm to create the largest possible
rectangle of letters such that every row forms a word (reading left to right) and every column forms
a word (reading top to bottom). The words need not be chosen consecutively from the list, but all
rows must be the same length and all columns must be the same height.
Hints; #477, #500, #748

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
Hints: #484, #498, #510, #518, #534, #547, #555, #561, #569, #577, #584, #603, #611, #636

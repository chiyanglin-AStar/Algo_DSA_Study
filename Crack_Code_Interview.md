#  Cracking Code interview

# Table of Contents

[General](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#General)

[Arrays and String](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Array-And-String)

[Linked Lists](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Linked-Lists)

[Stack Queue](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Stack-Queue)

[Tree Graphs](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Tree-Graphs)

[Bit Manipulation](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Bit-Manipulation)

[Math and Logic Puzzles](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Math-and-Logic-Puzzles)

[Object-Oriented Design](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Object-Oriented-Design)

[Recursion and Dynamic Programming](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Recursion-and-Dynamic-Programming)

[System Design and Scalability](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#System-Design-and-Scalability)

[Sorting and Searching](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Sorting-and-Searching)

[Testing](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Testing)

[C and C++](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#C-and-C++)

[Databases](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Databases)

[Threads and Locks](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Threads-and-Locks)

[Moderate](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Moderate)

[Hard](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#Hard)

# Arrays and String
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

Interview Questions

1.1 Is Unique: Implement an algorithm to determine if a string has all unique characters. What if you
cannot use additional data structures?
Hints: #44, #117, #132

ref: [Determine if a string has all Unique Characters](https://www.geeksforgeeks.org/determine-string-unique-characters/)

1.2 Check Permutation: Given two strings, write a method to decide if one is a permutation of the
other.
Hints: f t , #84, #122, #131

ref: [Check if two strings are permutation of each other](https://www.geeksforgeeks.org/check-if-two-strings-are-permutation-of-each-other/)

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

  2. 

1.8 Zero Matrix: Write an algorithm such that if an element in an MxN matrix is 0, its entire row and column are set to 0.
Hints: #17, #74, #102

ref: []()

1.9 String Rotation; Assume you have a method i s S u b s t r i n g which checks if one word is a substring
of another. Given two strings, si and s2, write code to check if s2 is a rotation of si using only one
call to i s S u b s t r i n g [e.g., "water b o t t l e " is a rotation o P ' e r b o t t l e w a t " ) ,
Hints: #34, #88,#W4

Additional Questions: Object-Oriented Design (#7.12), Recursion (#8.3), Sorting and Searching (#10.9), C++
(#12.11), Moderate Problems (#16.8, #16.17, #16,22), Hard Problems (#17.4, #17.7, #17.13, #17.22, #17,26).
Hints start on page 653.

# Linked List
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Stack Queue
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Tree Graphs
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Bit Manipulation
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Math and Logic Puzzles
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Object-Oriented Design
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Recursion and Dynamic Programming
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# System Design and Scalability
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Sorting and Searching
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Testing
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# C and C++
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Databases
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Threads and Locks
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Moderate
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)

# Hard
[Back to the Top](https://github.com/chiyanglin-AStar/Algo_study/blob/main/Crack_Code_Interview.md#table-of-contents)



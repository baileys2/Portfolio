Author
==========
"Bailey, Sam", baileys2
Portfolio
=========

Document completion of the course's learning outcomes.

Instructions
====
The goal of this is to make it very easy for me (or an employer, or a teaching assistant) to see whether or not you have mastered the material of the class. The hope is that I would be able to grade your work without downloading and compiling your code. If you have recorded proper video demonstrations of your programs, that should be sufficient. You will also want to write a paragraph or so making your case for why you deserve full credit for particular learning outcome (or if you don't, then you should say so).

Important
=========
If you prefer, you may turn this in to me via email, instead of hosting it on GitHub. Please talk to me about it during office hours or before or after class.

Body of portfolio
====

7 - Create an implementation of a Queue
----
Source of Evidence:

Below is a link to my branch of the 03_Queue_Lab in MiamiOH-CSE274 (specifically the file ArrayQueue.ipp), where I successfully implemented a queue:

https://github.com/MiamiOH-CSE274/03_Queue_Lab/blob/baileys2/ArrayQueue.ipp

References used: the online text

7 - Create an implementation of a List
----
Source of Evidence:

Below is a link to my branch of the 04_Linked_List_Lab in MiamiOH-CSE274 (specifically the file LinkedList.ipp), where I successfully implemented a Doubly-Linked List:

https://github.com/MiamiOH-CSE274/04_Linked_List_Lab/blob/baileys2/LinkedList.ipp

References used: the online text

7 - Create an implementation of a Binary Search Tree
----
Source of Evidence:

Below is a link to my branch of the 06_BST_Lab in MiamiOH-CSE274 (specifically the file BST.ipp), where I successfully implemented a binary search tree:

https://github.com/MiamiOH-CSE274/06_BST_Lab/blob/baileys2/BST.ipp

References used: the online text

7 - Create an implementaiton of a Hash Table
----
Source of Evidence:

Below is a link to my branch of the 05_Hashing_Lab in MiamiOH-CSE274 (specifically the file HashTable.ipp), where I successfully implemented a hash table:

https://github.com/MiamiOH-CSE274/05_Hashing_Lab/blob/baileys2/HashTable.ipp

References used: the online text

7 - Create an implementation of a Heap
----
Source of Evidence:

Below is a link to my branch of the 07_Heap_Lab in MiamiOH-CSE274 (specifically the file Heap.ipp), where I successfully implemented a heap priority queue:

https://github.com/MiamiOH-CSE274/07_Heap_Lab/blob/baileys2/Heap.ipp

References used: the online text

7 - Create an implementation of either Adjanency Lists or Adjacency Matrices
----
Possible sources of evidence (do any one of these):

* Graph lab
* Graph Algorithms lab
* Graph project
* Consult with Dr. Brinkman on an alternative project

7 - Implement graph algorithms
----
Possible sources of evidence (do any one of these):

* Graph lab
* Graph Algorithms lab
* Graph project
* Consult with Dr. Brinkman on an alternative project

21 - Determine space and time requirements of common data structure methods
-----
Possible sources of evidence (do up to 3 of these, up to 7 points for each):

* Select any of the following labs, and analyze the running times for each of your methods of your data structure: Queue, Linked List, Binary Search Tree, Heap, Hash Table, Graph (Adjacency List or Adjacency Matrix, you don't have to do both, but you can if you want)


5 - Describe memory management in C++, and correctly use dynamic variables, including destructors
----
Possible sources of evidence (do one):

* Select any of your labs or projects that uses dynamic memory, and explain how memory is managed. In particular, you must show that your program does not leak memory, and does not suffer from dangling pointers or out of bounds array access. This will probably require referring to your code, providing links.


5 - Create collection classes using templates in C++
----

Below is a link to my 03_Queue_Lab, where I successfully implemented templates: 

https://github.com/MiamiOH-CSE274/03_Queue_Lab/blob/baileys2/ArrayQueue.ipp

The purpose of "templates" in C++ is to essentially make code more reusable, as they are extremely useful when you have to perform tasks that are pretty much identical, but must be done with multiple types of variables. For example, in the queue that I implemented in the link above, a template class "T" was used. Obviously there is no acutal variable type "T", but rather this is simply used as a placeholder that tells the program that the type "T" will eventually be filled with an actual variable type. This type is determined when the data structure is constructed, and also when variables are passed back and forth between the various methods in the program. Using template classes simply allowed for more flexibility with what can be done with the code (as the queue could hold ints, doubles, chars, etc.) and makes it easier for the code to be adapted to a wider variety of possible use cases without having to write a whole new method for each desired variable type that performs the same exact action as the original. In the end, using template classes is a more efficient way to write code that makes things more streamlined and can be used in a much wider range of possibilities without haveing to rewrite anything.

30 - Using time and space analysis, justify the selection of a data structure for a given application
----

Possible sources of evidence (do up to 2 of these, up to 15 points for each):

* Select a project for which there are multiple reasonable data structure designs. Describe two reasonable options, and explain the trade-offs between them. For each, describe an application where the data structure would be better. For example, if comparing KD-Trees to a Grid in the Starbucks problem, which one is better really depends on the input data set. Explain what the data would have to look like for the Grid to be a clear winner, and also what type of data would lead you to use a KD-Tree instead.


Extra Credit
----
This is just a reminder that I attended the CSE Research Fair this fall semester and listened to talks about several different research topics, including augmented reality and computer security.
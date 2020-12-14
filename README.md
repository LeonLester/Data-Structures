# Data Structures
 CEID Upatras Project for Data Structures 2019

This projects implements a number of sorting and searching algorithms, as well as a binary search tree with automatic leaf weighing with some functions to extract data from it. Thirdly, there is an implementation of the latter, using hash chains instead of a BST. More details below.

**Sorting_Searching_Algorithms.cpp**

The main() function opens a .txt file that contains one integer per line. The name of the file is declared in main().

**Sorting
1. Bubble Sort
2. Insertion Sort
3.  Selection Sort
4. Quick Sort
5. Merge Sort
6. Heap Sort
***
**Searching**
1.	Linear Search
2.	Binary Search
3.	Interpolation Search
4.	Binary/Interpolation Search
***

1. Give the filename to open in main
2. A menu appears in terminal where you choose sorting method. Upon completion, you get the time elapsed in milliseconds. 
3. A prompt appears to ask if the user wants to search for a number in the vector created.
4. If a search is chosen, upon completion, the time elapsed is also displayed.


***
**Binary Search Tree.cpp**

This part of the project is a C++ implementation of a storing system for class students.

There is a Student class, a BST class and a struct for tree_node.

The Student class has the students info as private characteristics (AcademicID, first name, last name, grade) and set/get functions as public.  

The BST class has the tree_node struct as private characteristic.

The tree_node struct contains pointers for left and right, corresponding to left and right children in the tree, as well as a root. 

The public functions do the following: 

1. Checking if the tree is empty
2. Choosing traversal (in/pre/post order)
3. Print functions for the corresponding traversals that are being called from the root. 
4. Node insertion based on AcademinID or grade.
5. Node removal
6. Node info alteration.

For the grade-wise tree option, there also are the following functions: 

7. Find smallest/largest grade
8. Find the students with those grades.
9. Corresponding print functions that call the above from the tree root. 

Each tree node, is a Student instance.
Each hash chain input is also a Student instance.

Use instructions: 

1. THe file the name of which is declared in main() opens. 
2. A menu appers that asks the user to choose between: 
2.1 Load BST menu sorted by Academic ID
2.2 Load BST menu sorted by grade
2.3 Load hash chains

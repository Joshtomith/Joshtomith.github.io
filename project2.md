[Back to Portfolio](https://joshtomith.github.io/)

Scripting Project Compilation
===============

-   **Class: CSCI-315** 
-   **Grade: 75% (Fixed Errors Based on Feedback)**
-   **Language(s): C++**
-   **Source Code Repository:** [Data Structures Portfolio Project](https://github.com/Joshtomith/Data-Structures-Portfolio-)  
    (Please [email me](mailto:JTSmith3@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This projects contains two different implementations of a balanced binary search tree data structure. The purpose of the project was to experiment with different techniques of this task, and how the differ in efficiency. This project choose to focus on the AVL tree and Splay tree implementations in particular. This is a full scale implementation, with the ability to add to, delete, find the height of the tree and etc. For in depth examination of the differences read Implementation Differnces.txt. This program does not output anything into the terminal, but there is a timing program inlcuded to track the speed of actions on the data structures. However, you would need to pipe the results into a plotting program (such as gnuplot, that was used for the figure below).

## How to compiles / run the programs

How to compile (if applicable) and run the project.

Shell Program:
```bash
1) Go into any normal linux terminal and cd into the directory with the file
2) Give permissions chmod 755 lab02.sh
3) Then run it with ./lab02.sh
4) Requires a file named words.txt, but can be filed with anything the user wants in terms of content (1 word per line).
```

## Image Examples

This is a timing chart of the time it takes to add to a tree, and rebalance to maintain order in the tree. In this example both trees preformed about the same in terms of speed before 4500 add operations. However, after this point AVL began to outpreform Splay overall. Especially near the end, Splay spiked to high levels. Meanwhile AVL maintained its constant stable rise with the increasing data sizes.

![screenshot](images/AVLandSplay.png)
<br>Fig 1. Chart of the Timing for the different implementations. AVL Tree vs. Splay Tree


## 3. Additional Considerations

Sometimes we have to consider not only the speed of operations with different implementations, but the time it takes to setup the data structure. AVL may have preformed better in speed with larger data sets, but Splay was much easier to implement. In a bussiness setting where a speed of implementation is a priority, Splay would be a serious contender.


For more details see [README.md file](https://github.com/Joshtomith/Data-Structures-Portfolio-/blob/main/README.md).

[Back to Portfolio](https://joshtomith.github.io/)

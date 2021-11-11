[Back to Portfolio](https://joshtomith.github.io/)

Scripting Project Compilation
===============

-   **Class: CSCI-315** 
-   **Grade: 75% (Fixed Errors Based on Feedback)**
-   **Language(s): C++**
-   **Source Code Repository:** [Data Structures Portfolio Project](https://github.com/Joshtomith/Data-Structures-Portfolio-)  
    (Please [email me](mailto:JTSmith3@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This projects contains two different implementations of a balanced binary search tree data structure. The purpose of the project was to experiment with different techniques of this task, and how the differ in efficiency. This project choose to focus on the AVL tree and Splay tree implementations in particular. This is a full scale implementation, with the ability to add to, delete, find the height of the tree and etc. For in depth examination of the differences read Implementation Differnces.txt. There is a timing program inlcuded to track the speed of actions on the data structures in the src folder. However, you would need to pipe the results into a plotting program (such as gnuplot, that was used for the figure below).

## How to compiles / run the programs

Note: There is not executable, but there are obj files if you want to run this off linux. However, for ease of use you can use visual studio or an online compiler to run the source code. Below I will explain the online compiler, since its very easy to use.

```
1) Go to this website https://www.onlinegdb.com/online_c++_compiler# 
2) import the files that you want to run. For AVL you'd import main, AVLbinarytree.hpp and AVLbinarytree.cpp
3) Change main to include the correct tree your running. For example, instead of #include "AVLbinarytree.hpp" it'd be #include "SplaybinaryTree.hpp"  
4) Click execute, and the main included will run a couple of basic functions to test the implementations.
```

## Image Examples

This is a timing chart of the time it takes to add to a tree, and rebalance to maintain order in the tree. In this example both trees preformed about the same in terms of speed before 4500 add operations. However, after this point AVL began to outpreform Splay overall. Especially near the end, Splay spiked to high levels. Meanwhile AVL maintained its constant stable rise with the increasing data sizes.

![screenshot](images/AVLandSplay.png)
<br>Fig 1. Chart of the Timing for the different implementations. AVL Tree vs. Splay Tree


## 3. Additional Considerations

Sometimes we have to consider not only the speed of operations with different implementations, but the time it takes to setup the data structure. AVL may have preformed better in speed with larger data sets, but Splay was much easier to implement. In a bussiness setting where a speed of implementation is a priority, Splay would be a serious contender.

For more in depth comparsion see [README.md file](Implementations Differences.md).
For more technical details see [README.md file](https://github.com/Joshtomith/Data-Structures-Portfolio-/blob/main/README.md).

[Back to Portfolio](https://joshtomith.github.io/)

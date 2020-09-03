# Binary Tree Creation from the data from the file
Creating a binary tree from the Given Data from the file

Open and read a file of integer pairs into an array that is created with the first integer telling you how many to read.  

So  4 9  11  4  5    would mean create an integer array size 4 and read into data[].  

Write a routine that places these values into a binary tree structure. Then walk the tree “inorder” and print these values to the screen.

Solution is in the main file -->main.c

For run the code from the git the below steps are given . i used the Linux based system with git already installed.

git clone https://github.com/jishang1602/binarytree.git

cd binarytree/

gcc main.c

./a.out

File open sucessfully
 
Element 0: 9

9

Element 1: 11

11

Element 2: 5

5

Element 3: 4

4

1- Inorder

Given inorder traversal as input

9->11->5->4->

preorder traversal of tree

11->9->5->4->

inorder traversal of tree

9->11->5->4->

postorder traversal of tree

9->5->4->11->



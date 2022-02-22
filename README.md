# bst_traversals

You are given N values to be inserted into a binary search tree. Every value in the left subtree fo a node x must be less than or equal to x and every value in the right subtree of a node x must be greater than x. You are to insert the N values into a binary search tree in the order that they are given. Print the resultant binary search tree's pre-order, in-order and post-order traversal on three different lines.

Input Format

First line contains a number N. Next line contains N integers.

Constraints

1 <= N <= 1000

Output Format

Output 3 lines. First line denoting the preorder traversal, second line denoting the inorder traversal and the last line denoting the postorder traversal.

Sample Input 0

10
12 3 5 11 15 5 4 4 8 15 
Sample Output 0

12 3 5 5 4 4 11 8 15 15 
3 4 4 5 5 8 11 12 15 15 
4 4 5 8 11 5 3 15 15 12 

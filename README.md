# Triplet-Min-Sum
Triplet Min Sum
描述
You are given a tree with 
N
N nodes. Answer 
Q
Q queries of the type:

Given three distinct nodes 
A
A, 
B
B, and 
C
C, find the node 
D
D such that the sum of distances from 
D
D to 
A
A, 
B
B and 
C
C is minimum. 
输入
The first line contains two integers N and Q.

Each of the following N-1 lines contain two integers, representing two nodes that share an edge.

Each of the following Q lines contains three integers A, B and C.

3≤N≤10^5
1≤Q≤10^5
Node D can be equal to one of A, B or C 
It can be proved the answer is unique
输出
For each query print two numbers on a distinct line: the node D and the sum of distances from D to A, B and C.
样例输入
10 3
1 7
4 7
6 2
8 3
9 8
5 8
2 4
3 4
10 7
1 7 8
8 3 10
6 10 3
样例输出
7 4
3 4
4 5

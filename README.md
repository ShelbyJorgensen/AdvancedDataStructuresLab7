# AdvancedDataStructuresLab7
The lab was part of my CS302 Advanced Data Structures class at Central Washington University. In this lab we were required to learn how to sort and traverse a graph, all problems should be solved in O(|V| + |E|) time. Below is the provided project outline:

**Problem 1**
You are given an undirected graph G which is represented as adjacency list. Its n nodes are labelled
from 0 to n − 1. For each node, its list of neighbours is out of order. Implement an algorithm that
sorts all these lists in total linear time. Note that linear-time for graphs means in O|V | + |E| time.
Using counting sort on each list of neighbours requires a total of O|V |2 + |E| time. Feel free to
change the given graph as needed. However, do not change the IDs of vertices.
**Problem 2**
You are given a weighted directed acyclic graph G and a vertex s. Implement an algorithm that
determines in linear time the distance from s to all other vertices. Note that edge weights can be
a negative. The output should be an int- array containing the distances from s to all vertices ordered
by their IDs, i. e., the output should be d(s, v0), d(s, v1), . . . . If there is no path from s to some
vertex vi, set d(s, vi) := Integer.MAX_VALUE.

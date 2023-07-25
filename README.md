# DSA_Assement

# 1st Problem Apporach
1. Created the Trie to Store the all Words available.
2. Trie use to perform All operations on an array of strings (Insertion, Search, Deletion);
3. Perform DFS traversal to Each Character available inside the board.
4. check, from corresponding starting characters is there any Word Available in Trie.
5. if we reach the terminal node of words, it ensures that the corresponding word is possible.
6. we store that in an Array of type String;
7. return The Array.

8. # 2nd Problem Apporach
9.  I used the concept of Topological Sorting
10.  Topological sorting for Directed Acyclic Graph (DAG) is a linear ordering of vertices such that for every directed edge u v, vertex u comes before v in the ordering.
11.  Created the Adjacency List
12. stored the value in adjacency List in reverse order given Input Array
13. created the Indegree Array, to calculate the Incoming Edges for Each Node.
14. then checked if is There Any Node whose Indegree is 0.
15. push That in Queue
16. Creted the Result array to store the Value
17. Perform The BFS Operation
18. Check the condition, if the Result array size is equal to numCourses, Then return Result Array
19. else Return Empty Array

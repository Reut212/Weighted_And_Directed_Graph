![OOP_EX3 Python](https://user-images.githubusercontent.com/66211258/104647912-37cd3300-56bb-11eb-93e0-e2366ed2b654.jpeg)


This project represents a weighted and directed graph

This project based on Classes that we created such as:

NodeData - represents vertices on the graph.
EdgeData - represents graph's edges.
DiGraph - represents our graph that contains all the Vertex and Edges.
GraphAlgo- represents our graph which we operate our algorithms on.
Comp - represents a comperession against NetworkX.

Each class offers us multiple functions to get information about the object.
we have several algorithms that we can operate on our graph such as:

shortest_path(self, id1: int, id2: int) -> (float, list) - return the *shortest* path from Vertex 1 to Vertex 2,
by using Dijkstra's Algorithm.
connected_components(self) -> List[list] - Finds all the Strongly Connected Component(SCC) in the graph,
using BFS Algorithm and transpose.
connected_component(self, id1: int) -> list - return a list with the Strongly Connected Component(SCC) that node id1 is a part of,
using BFS Algorithm.

we made tests for each class and the graph we created for checking the methods is:



 

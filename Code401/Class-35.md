# Graphs

[Home](../index.md)

## Definition

Graphs are non linear data structures of vertices (nodes) that are linked by edges. Some common graph terminology is.

> Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
> Edge - An edge is a connection between two nodes.
> Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
> Degree - The degree of a vertex is the number of edges connected to that vertex.

## Types of Graphs

- Undirected vs directed (Digraph). This has to do with where the edges (pointers) are bidirectional or not.
- Completed, Connected, vs Disconnected. In Complete graphs all nodes are linked to every other node. In Connected graphs all nodes have at least one edge. In Disconnected graphs some vertices have no edges.
- Acyclic vs Cyclic: Cyclic graphs have at least one cycle in it. Acyclic graphs mean you can never get stuck in a circle.

## Adjacency Matrix

Instead of assigning pointers to every node you may keep track of edges with an adjacency matrix or linked list.

## Weigthed Graphs

When edges are a value assigned to them (for example distance between nodes), then it is considered a weighted graph.

## Traversals

Just like with trees, there are breadth first and depth first traversals. The only main real difference is you have to keep track of which vertices you have visited.

## Things I Want to Know More About

I want to see graphs in action to do some super swoopty high tech coding hack-a-thon-amania! HACK THE MAINFRAME!

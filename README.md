Aviation Route Optimization using Graph Algorithms

Overview

This project models an airport network as a graph and implements a shortest path algorithm to compute optimal flight routes between airports.

Each airport is represented as a node, and each flight route between airports is represented as a weighted edge. The goal is to determine the most efficient route between two airports based on the given dataset.

This project was originally developed as part of a Data Structures and Algorithms course and demonstrates practical application of graph theory concepts.

⸻

Concepts Implemented
	•	Graph representation using adjacency lists
	•	Nodes and weighted edges
	•	Shortest path algorithm (Dijkstra or similar approach)
	•	Real dataset processing
	•	Algorithmic problem solving applied to transportation networks

⸻

Dataset

The dataset contains flight route information between airports.

Each record represents:
	•	Origin airport
	•	Destination airport
	•	Route connection (edge)

The dataset is stored in the data/ directory.

⸻

How It Works
	1.	The dataset is loaded and parsed.
	2.	Airports are modeled as nodes in a graph.
	3.	Flight routes are modeled as edges connecting nodes.
	4.	A shortest path algorithm is applied to determine the optimal route between two selected airports.

The algorithm evaluates connections and computes the most efficient path based on the graph structure.

⸻

Example Use Case

Given two airports:
	•	Origin: Bogotá (BOG)
	•	Destination: Atlanta (ATL)

The algorithm computes the optimal route based on available flight connections in the dataset.

⸻

Algorithm

This project implements a shortest path strategy to compute routes between nodes.

If Dijkstra’s algorithm is used:

Time Complexity:
O((V + E) log V)

Where:
V = number of airports (nodes)
E = number of flight routes (edges)

⸻

Why This Project Matters

This project demonstrates:
	•	Application of graph theory to real-world systems
	•	Modeling complex networks using data structures
	•	Implementation of classic algorithms
	•	Understanding of shortest path computation

It reflects practical problem-solving skills and foundational knowledge in algorithms and data structures.

⸻

Future Improvements
	•	Convert the notebook logic into modular Python scripts
	•	Add unit testing for algorithm validation
	•	Improve dataset validation and error handling
	•	Create a simple API to expose route calculations

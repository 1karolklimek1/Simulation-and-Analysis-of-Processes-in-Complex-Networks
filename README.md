## Air Traffic Resilience & Cascade Delay Simulation
A discrete-event simulation (DES) and complex network analysis framework modeling air traffic dynamics, capacity bottlenecks, and cascading delay propagation across Polish airspace.

The project evaluates network fault tolerance under crisis scenarios—such as hub shutdowns, ground-stop protocols, and real-time in-flight diversions to backup airports.

Key Features:
* Discrete-Event Simulation (SimPy): Models flight lifecycles (boarding, taxiing, cruising, landing) with constrained airport gate resources and queue dynamics.

* Cascading Congestion Multipliers: Dynamic turnaround delays driven by real-time airport gate utilization.

* Disruption Handling: Simulates ground-stop holds and autonomous nearest-open backup routing for airborne traffic.

* Topological Centrality (igraph & NetworkX): Evaluates single points of failure using Weighted Betweenness Centrality and PageRank on a Hub-and-Spoke topology.

* Spatiotemporal Visuals: Renders animated 2D operational maps (matplotlib.animation / GIF) tracking active flights, tarmac queues, and node statuses.

# Zacharys-Karate-Club-Analyis
Exploring Zachary's Karate Club dataset to analyze social dynamics, identify influential members, and uncover community structures using network metrics and visualization techniques.

### Objectives
- Extracting properties and insights from the dataset.
- Computing various centrality measures and visualizing network structures.
- Analyzing communities and user roles within the network.
- Deriving insights into user behavior and the influential nodes in the network.

## Dataset
- The Zachary's Karate Club dataset features an undirected social network with 34 nodes and 78 edges, illustrating social dynamics and interactions within the club.
- Each member is represented as a node, and an edge exists between two nodes if they are friends, illustrating relationships and interactions among members of the club.

## Graph Creation
- Loaded the Zachary's Karate Club dataset via NetworkX, creating a clean undirected graph for precise analysis, using Python libraries like Matplotlib, NumPy, and Seaborn.
- Applied community detection algorithms (Girvan-Newman, Louvain, Label Propagation) and centrality measures to understand user interactions and reveal insights into network structure and influential nodes.

## Initial Findings
- A graph density of 0.1390 indicates well-connectedness in the network, with a diameter of 5 and an average path length of 2.41, facilitating efficient flow of information and quick reachability.
- A radius of 3 demonstrates that most users connect within three steps, exemplifying small-world properties that enhance communication and collaboration.

## Visualizations
### Shortest Path Length Distribution
- Illustrates connectivity within the network and ease of information flow. Lower values indicate closely linked users, while higher values signify more isolated individuals.

### Degree Centrality
- Reveals the number of direct links each node has, highlighting influential nodes within the network who can quickly disseminate information.

### Closeness Centrality
- Measures a node's speed in reaching others within the network, indicating effectiveness in communication.

### Betweenness Centrality
- Indicates nodes that act as bridges within the network, facilitating communication between different groups.

### Eigenvector Centrality
- Assesses node influence based on the quality of its connections, identifying key nodes connected to other influential nodes.

### PageRank
- Evaluates node importance by analyzing connections, identifying key members essential for sustaining network connectivity.

### Community Visualizations
#### Girvan-Newman
- Identifies communities by systematically removing edges with high betweenness, uncovering natural clustering.

#### Louvain Method
- Detects groups by optimizing modularity, revealing hierarchical relationships within communities.

#### Label Propagation
- Identifies communities by assigning labels based on neighboring nodes, facilitating natural community formation.

### Clustering Coefficient Distribution
- Reveals the extent of connectivity among groups in the network. The average clustering coefficient of 0.5706 indicates tightly-knit groups.

### K-Core Decomposition (User Input k)
- Breaks down the network into layers, each node having at least k connections, identifying the most connected members and offering insights into community structure.

### Broker Nodes
- Key individuals linking separate communities, enabling interactions and information exchange. Identifying these nodes helps understand influence within the network.

## Conclusion
- Understanding connections within the network can help improve relationships and resolve conflicts within groups.
- Identifying influential nodes amplifies communication strategies and enhances information dissemination.
- Clustering indicates tightly-knit communities, facilitating effective information sharing among members.

---
#Thank You

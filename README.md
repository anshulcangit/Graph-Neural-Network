# Graph Representation Learning
## Graph Neural Networks for Node Classification and Link Prediction
This repository contains the implementation of my M.Sc research Thesis on Graph Representation Learning, under the supervision of Dr. B. S. Panda, IIT Delhi. The project explores GNNs for node classification and link prediction, with a focus on citation networks, drug interaction datasets, and dynamic/online learning for evolving graphs.

# Introduction
Graph Neural Networks (GNNs) are powerful tools for learning on graph-structured data. This project focuses on:
* Node Classification: Predicting the label of a node using its features and graph structure.
* Link Prediction: Predicting the likelihood of an edge between two nodes.
* Dynamic Link Prediction: Adapting to changes in graph structures over time using online learning mechanisms.

Key datasets used:
* Cora Dataset: A citation network dataset for node classification.
* OGB-DDI Dataset: An Open Graph Benchmark dataset for predicting drug-drug interactions.

# Key Features
* Graph Convolutional Networks (GCNs): Implemented to improve node classification accuracy copared to MLP like .
* Graph Attention Networks (GATs): Enhanced classification accuracy with attention mechanisms.
* GraphSAGE: Neighborhood sampling for large-scale node classification.
* Link Prediction on OGB-DDI: Achieved high Hits@K scores for predicting drug interactions.

# Graph Representation Learning
## Graph Neural Networks for Node Classification and Link Prediction
This repository contains the implementation of my M.Sc research Thesis on Graph Representation Learning, conducted from August 2023 to December 2023 under the supervision of Dr. B. S. Panda, IIT Delhi. The project explores GNNs for node classification and link prediction, with a focus on citation networks, drug interaction datasets, and dynamic/online learning for evolving graphs.

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
* Dynamic Link Prediction: Implemented online learning to handle evolving graph structures for real-time link prediction tasks.
* Custom Training Pipelines: Optimized pipelines for data processing, training, and evaluation.

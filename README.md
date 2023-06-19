# GraphDTA: Exploring Drug-Target Interaction with Graph Neural Networks

This repository contains the code and resources for a project focused on understanding Graph Neural Networks (GNNs) and their application to drug-target interaction (DTI) prediction. The main objective of this project was to gain hands-on experience with GNNs and the PyTorch library while exploring and improving the performance of the GraphDTA algorithm.

## About GraphDTA

GraphDTA is one of the most popular algorithms developed for the drug-target interaction problem. It leverages graph neural networks to model the complex relationships between drugs and their protein targets. The algorithm aims to predict the binding affinity between a given drug molecule and a target protein, which is a crucial step in drug discovery and development.

The original implementation of GraphDTA can be found in the GitHub repository of its author, Thin Nguyen. We have used this repository as our main resource for this project, studying the code and understanding its inner workings.

## Project Overview

In this project, we followed these main steps:

1. Familiarized ourselves with GNNs and the GraphDTA algorithm by studying the code and related resources.
2. Explored the GraphDTA codebase, understanding the model architecture, data preprocessing, and training procedures.
3. Conducted a hyperparameter search to improve the model's performance. We experimented with various parameters, such as learning rate, epoch numbers, and dropout rates.
4. Used the PyTorch library for implementing the GNN model and conducting the hyperparameter search. PyTorch provides a flexible and intuitive framework for building and training neural networks.

## Repository Structure

- `data/`: This directory contains the necessary data files for the GraphDTA algorithm. 
- `model/`: Here, you will find the implementation of the GraphDTA model using PyTorch. The GCNN model architecture processes the graph-structured SMILES data and protein sequence data separately using graph convolutional layers and 1D convolutional layers, respectively. The features from both branches are then combined and passed through a series of dense layers to produce the final output, which represents the predicted drug-target binding affinity.
- `utils/`: This directory contains utility functions and helper scripts used in the project.
- `hyperparameter_search.ipynb`: Jupyter Notebook showcasing the code to perform the hyperparameter search experiments.


## Acknowledgments

We would like to express our gratitude to Thin Nguyen for developing the GraphDTA algorithm and providing the codebase as a valuable resource for our project. Their contribution has been instrumental in our learning and exploration of GNNs and drug-target interaction prediction.

## Resources

https://github.com/thinng/GraphDTA


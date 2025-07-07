# Graph Classification with GCN on PROTEINS Dataset
**Objective:** This notebook demonstrates how to build and train a Graph Convolutional Network (GCN) using the DGL library for graph classification on the PROTEINS dataset. The task is to classify each protein (graph) into one of 2 classes based on its structural characteristics.

**Why PROTEINS Dataset?** PROTEINS is a dataset where graphs represent protein structures. Nodes are amino acids, and edges represent connections between them. The task is binary classification (2 classes). This dataset serves as a benchmark for evaluating graph neural networks on biological data, requiring the model to capture relevant structural patterns for classification.  

**Dataset:** PROTEINS from TUDataset (1113 graphs, 2 classes)  

**Model:** Graph Convolutional Network (GCN) with multiple convolution layers, global mean pooling, and a linear classification head. We explored a 3-layer GCN with dropout.

**Implementation:** Based on the DGL library, utilizing PyTorch for model definition and training.

**Result:** Achieved an average test accuracy of approximately 70% using 5-fold cross-validation.

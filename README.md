# Final-Project

## Overview
This project addresses the challenge of semi-supervised node classification on molecular graphs.

## Implementation Steps
### 1. Data Preprocessing
- Tox21 and QM9 datasests are used
- Data split into training, validation, and test sets.

### 2. GNN Architecture Design
- GNN architecture captures hierarchical and spatial relationships within molecular graphs.
- Utilized Graph Convolutional Networks (GCNs) and GraphSAGE layers for effective learning.

### 3. Graph Adversarial Training (GAT)
- Train the GNN without GAT.
- Initialize the discriminator.
- Adversarially train the generator and discriminator to improve robustness.

### 4. Dependencies
```bash
!pip install torch_geometric
!pip install rdkit
```

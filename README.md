# Edge-GAT Molecular 🧬

Graph Attention Network with edge-feature awareness for 
molecular bond-type classification.

## What it does
- Implements **Graph Attention Network (GAT)** extended with 
  edge-feature integration
- Classifies molecular bond types using graph-structured data
- Trained and evaluated on molecular graph datasets

## Architecture

Molecular Graph Input
        ↓
Node Feature Extraction
        ↓
Edge-Feature Aware GAT Layers
(attention weights conditioned on both node AND bond features)
        ↓
Graph-level Pooling
        ↓
Bond-Type Classification Output

## Tech Stack
`PyTorch` `PyTorch Geometric` `Google Colab` `Python`

## Context
Built as part of Advanced Deep Learning Architectures (ADLA) 
coursework — exploring GNNs for cheminformatics applications.

## Author
[skrbht](https://github.com/skrbht127)

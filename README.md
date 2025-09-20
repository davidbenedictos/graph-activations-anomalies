# Anomaly Detection in Neural Networks through Activations and Graphs

This repository contains the code, experiments, and documentation for my Bachelor's Thesis (TFG) at **Universitat Politècnica de Catalunya (UPC)**.  
The project focuses on analyzing **internal activations** of deep neural networks and representing them as **graphs** to detect and characterize anomalies, including **adversarial attacks**.

---

## 📖 Project Overview
Deep learning models achieve excellent performance in tasks such as computer vision and classification.  
However, they are vulnerable to unexpected behaviors and adversarial attacks.  
This project explores the transformation of internal activations into **graph structures**, leveraging **topological and relational information** for anomaly detection.

### Objectives
- Train a baseline CNN on MNIST.  
- Generate adversarial examples (FGSM, PGD).  
- Extract internal activations from selected layers.  
- Construct graphs at different granularities (layer, channel, neuron).  
- Apply anomaly detection methods (statistical, embeddings, GNNs).  
- Visualize and analyze results.

---


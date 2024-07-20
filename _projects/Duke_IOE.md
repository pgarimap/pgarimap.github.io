---
title: "Application of a Multi-Layer Perceptron in Early Earthquake Warning Systems"
#date: 2024-01-01
skills: ["Pytorch", "Pandas", "Numpy"]
excerpt: "Identification of the most effective interpolation technique for filling gaps in temperature and precipitation data"
permalink: /projects/project1/
layout: project
---
## Project Overview
**Title**: Application of a Multi-Layer Perceptron in Early Earthquake Warning Systems

## Objective
Develop an early earthquake warning system for Kathmandu Valley using a Multi-Layer Perceptron (MLP) to predict Peak Ground Velocity (PGV) and Peak Ground Acceleration (PGA) based on features from Japanese earthquake records. This project is under collaboration with Duke University and IOE, Pulchowk Campus.

## Methodology
**Network Architecture:**
- Input Layer: Features include peak velocity (Pgv), peak acceleration (Pga), change in peak acceleration (dPGA), duration of peak velocity (dPgv), rise time of peak displacement (td), and sensor network stations.
- Hidden Layers: 64 neurons in the first layer, 32 in the second.
- Output Layer: Predicts PGV and PGA.
- Training: Various optimizations, including depth of hidden layers, batch sizes, and learning parameters.

## Results
Optimization: Achieved a Mean Absolute Error of 26.975.
Analysis: Reasonable prediction accuracy, though variability due to limited training data and regional differences.

## Conclusions
The model shows potential but needs more training data and further optimization to address variability and inconsistency.


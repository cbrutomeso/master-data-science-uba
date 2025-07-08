# Graph Analysis - TP1

This project contains the code and analysis for TP1 of the Data Mining course (Ciencia y Tecnología). The main focus is on the structural analysis and modeling of real-world networks using Python and NetworkX.

## Overview

The analysis explores the structural properties, robustness, and community structure of three real-world networks:
- **C. elegans** (neural network of the worm)
- **Facebook** (social network)
- **Airports** (air transportation network)

The project compares these real networks with classical random graph models (Erdős-Rényi, Watts-Strogatz, Barabási-Albert, Holme-Kim), analyzes node centrality, robustness to failures and attacks, and detects communities using Louvain and Girvan-Newman algorithms.

## Files
- `analisis_de_grafos_tp1.ipynb`: Main Jupyter notebook with all code and analysis.
- `airport.txt`, `facebook.txt`, `celegans.txt`: Edge lists for each network (downloaded automatically by the notebook).
- `airportStronglyConn_pos.pkl`, `fb_pos.pkl`: Precomputed node positions for visualization (downloaded automatically).

## Requirements
- The notebook is designed to run on **Google Colab Pro**.
- All required Python packages are either pre-installed or installed automatically in the notebook.
- No local setup is necessary; simply open the notebook in Google Colab and run all cells.

## How to Run
1. Open `analisis_de_grafos_tp1.ipynb` in Google Colab (Pro version recommended for performance).
2. Run all cells in order. The notebook will automatically download the datasets and position files if they are not present.

## Main Analyses
- **Adjacency Matrices:** Visualization and binarization of adjacency matrices for each network.
- **Degree Distributions:** Comparison of degree distributions with random graph models.
- **Centrality Analysis:** Degree, betweenness, closeness, eigenvector, and PageRank centralities.
- **Robustness:** Simulation of random failures and targeted attacks, measuring the size of the largest connected component and global efficiency.
- **Community Detection:** Louvain and Girvan-Newman algorithms applied to each network, with modularity evaluation and visualization.

## Authors
- Carlos Brutomeso
- Ramiro Santamaria

## License
This project is for academic purposes only.

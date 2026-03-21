# Routing and Wavelength Assignment – NSFNET

This repository contains a simulation-based comparison between ILP and Heuristic solutions for the Routing and Wavelength Assignment (RWA) problem in optical networks.  

## Overview

- **Topology**: NSFNET backbone (14 nodes, realistic U.S. network)
- **Goal**: Compare the success rate of ILP vs Heuristic for routing demands while minimizing wavelength usage
- **Approach**:
  - Load network graph from JSON
  - Generate multiple traffic matrices
  - Run both ILP and Heuristic RWA algorithms
  - Compare results per matrix

## Files

| File                    | Description                                                 |
|-------------------------|-------------------------------------------------------------|
| `Task3_CND.ipynb`       | Jupyter notebook with full implementation and visualization |
| `10869960_11041528_CND_TASK_3.pdf` | Official report with input descriptions and analysis            |
| `nsfnet_topology.json`  | (Assumed) input file with node/edge structure of NSFNET     |

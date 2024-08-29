# [SHARP] Metaheuristic Optimization - P Median Problem
[![GitHub license](https://img.shields.io/github/license/Jungstershark/P-Median-Problem)](https://github.com/Jungstershark/P-Median-Problem/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Jungstershark/P-Median-Problem?style=social)](https://github.com/Jungstershark/P-Median-Problem/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Jungstershark/P-Median-Problem?style=social)](https://github.com/Jungstershark/P-Median-Problem/network/members)

This repository contains the Jupyter notebooks, text files, and supporting documentation for the project activity on the p-median location problem. The objective of this project is to determine the optimal selection of facilities from a set of potential locations, minimizing the total distance for serving all demand points while ensuring that each demand point is assigned to its nearest selected facility.

## Contents

- `Ipyb Files`: Contains Jupyter notebooks.
  - `Random Sampling - Instance 1.ipynb`: Implementing the random sampling algorithm for instance 1.
  - `Random Sampling - Instance 2.ipynb`: Implementing the random sampling algorithm for instance 2.
  - `Local Search - Instance 1.ipynb`: Implementing the local search algorithm for instance 1.
  - `Local Search - Instance 2.ipynb`: Implementing the local search algorithm for instance 2.

- `Text Files`: Supplementary text files corresponding to the Jupyter notebooks.
  - `Random Sampling - Instance 1.txt`: Text file for implementing of random sampling algorithm
  - `Random Sampling - Instance 2.txt`: Text file for implementing of random sampling algorithm
  - `Local Search - Instance 1.ipynb`: Text file for implementing of local search algorithm
  - `Local Search - Instance 2.ipynb`: Text file for implementing of local search algorithm

- `requirements.txt`: List of Python packages required to run the notebooks.

- `SHARP_MHO_1.pdf`: A comprehensive report detailing solution encoding representation, search procedure explanation, and results obtained for each exercise.

## Problem Overview

Given a set of `n` locations representing demand points and a set of `m` potential facility locations, the p-median problem aims to determine the optimal selection of `p` facilities from the set of potential locations.

### Instances
- Instance 1: 100 locations, requiring 15 facilities to be open.
- Instance 2: 1000 locations, requiring 30 facilities to be open.

## Setup & Execution

Setup & Execution
1. Ensure you have Jupyter Notebook and required Python packages installed.
2. Clone the repository:
```bash
git clone https://github.com/<your_username>/P-Median-Problem.git
```
3. Navigate to the cloned directory.
4. Install required packages:
```bash
pip install -r requirements.txt
```
5. Run Jupyter Notebook:
```bash
jupyter notebook
```
6. Open each notebook and execute the cells sequentially.

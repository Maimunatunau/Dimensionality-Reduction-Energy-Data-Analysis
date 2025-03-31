# Dimensionality Reduction: Energy Data Analysis

## Overview

This project applies dimensionality reduction techniques to analyze and visualize a dataset containing approximately 20,000 data points related to environmental conditions and appliance energy consumption. The goal is to reduce the dataset’s dimensionality while preserving important information.

## Dataset

- **Filename:** energydata_complete.csv
- **Size:** ~20,000 data points
- **Features:** Multiple environmental and energy-related numerical variables

## Objective

- Use a dimensionality reduction technique to project the data into three dimensions for visualization.
- Evaluate whether the 3D projection sufficiently preserves the original dataset’s structure.
- If necessary, determine the optimal number of dimensions for accurate data representation.

## Methodology

1. **Preprocessing:**
   - Load and inspect the dataset for missing values and inconsistencies.
   - Normalize or standardize features if required.
2. **Dimensionality Reduction Techniques:**
   - Principal Component Analysis (PCA) for linear feature extraction.
   - t-Distributed Stochastic Neighbor Embedding (t-SNE) or UMAP for non-linear reduction.
3. **3D Visualization:**
   - Scatter plots to visualize clusters and relationships in 3D space.
4. **Evaluation:**
   - **Explained Variance Ratio (for PCA):** To determine retained information.
   - **Reconstruction Error:** To assess data loss in lower dimensions.
   - **Silhouette Score:** To measure clustering consistency post-reduction.
5. **Determining Optimal Dimensionality:**
   - Use Scree Plots and cumulative explained variance to find the minimum dimensions preserving data structure.

## Results

- The 3D visualization was generated using [insert method used].
- The evaluation showed that [explain success/failure].
- The optimal dimensionality for preservation was found to be [number].

## Technologies Used

- Python
- Scikit-learn
- Matplotlib & Seaborn
- Pandas & NumPy
- Plotly (for interactive 3D visualizations)

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the dimensionality reduction script:
   ```bash
   python src/dimensionality_reduction.py
   ```
3. View the visualization output in `results/`.

## Requirements



## Future Improvements

- Explore autoencoders for non-linear dimensionality reduction.
- Apply clustering techniques on the reduced dataset to identify patterns.
- Experiment with hybrid techniques combining PCA and t-SNE/UMAP.


This project is part of my portfolio as a Machine Learning Engineer. Contributions and suggestions are welcome!


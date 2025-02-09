# K-Means Clustering

## Project Overview
This project implements the K-Means clustering algorithm from scratch using Python. The algorithm groups data points into clusters based on their similarity, optimizing cluster centroids iteratively. The dataset used is provided in `kmeans.csv`.

## Features
- Implements K-Means clustering without using built-in machine learning libraries.
- Normalizes the dataset before training.
- Runs K-Means for `k=2` and `k=3`.
- Visualizes the clusters with properly labeled plots.

## Requirements
Ensure you have the following libraries installed before running the script:
```bash
pip install numpy pandas matplotlib
```

## Usage
1. Place the `kmeans.csv` file in the same directory as the script.
2. Run the script using:
   ```bash
   python kmeans.py
   ```
3. The script will generate cluster visualizations for `k=2` and `k=3`.

## Code Explanation
- **Data Normalization:** The dataset is normalized to ensure consistent scaling.
- **Centroid Initialization:** Randomly selects `k` points as initial centroids.
- **Cluster Assignment:** Each point is assigned to the nearest centroid.
- **Centroid Update:** Centroids are recalculated as the mean of assigned points.
- **Convergence Check:** Stops iterating when centroid movements are minimal.
- **Plotting:** Uses `matplotlib` to visualize clusters with different colors.

## Output
The script will output two scatter plots:
1. **K=2**: Data points are grouped into 2 clusters.
2. **K=3**: Data points are grouped into 3 clusters.

Each plot labels the centroids distinctly and colors the clusters for clarity.

## License
This project is for educational purposes. Feel free to modify and extend the implementation.


# Customer Segmentation Using K-Means Clustering

## Introduction

This project demonstrates customer segmentation using the K-Means clustering algorithm.

## Installation

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Preprocessing:**
   ```python
   from src.data_preprocessing import preprocess_data
   data = preprocess_data('data/customer_data.csv')
   ```

2. **Build and Train Model:**
   ```python
   from src.kmeans_model import build_kmeans_model
   kmeans_model = build_kmeans_model(data, n_clusters=5)
   ```

3. **Visualization:**
   ```python
   from src.visualization import plot_clusters
   plot_clusters(data, kmeans_model)
   ```

4. **Run Jupyter Notebook:**
   ```bash
   jupyter notebook notebooks/Customer_Segmentation.ipynb
   ```

## Results

Visualize customer segments with scatter plots.

## License

This project is licensed under the MIT License.

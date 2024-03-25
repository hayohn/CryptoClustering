# Cryptocurrency Clustering Project

This project aims to analyze and cluster different cryptocurrencies based on their market data and principal component analysis (PCA) techniques. The analysis involves the following steps:

1. **Data Preprocessing**: Load and preprocess the cryptocurrency market data, handling missing values and scaling the features.

2. **Dimensionality Reduction with PCA**: Apply PCA to reduce the dimensionality of the data by identifying the most important principal components.

3. **Clustering with K-Means**: Perform clustering on both the original data and the PCA-transformed data using the K-Means algorithm to group similar cryptocurrencies together.

4. **Elbow Curve Analysis**: Analyze the elbow curves to determine the optimal number of clusters for the original data and the PCA data.

5. **Visualization**: Create scatter plots to visualize the clustering results and compare the original data clusters with the PCA-based clusters.

6. **Analysis and Interpretation**: Analyze the impact of using fewer features (principal components) for clustering and interpret the results.

## Usage

1. Clone the repository.
2. Install the required dependencies. All listed in Jupyter Notebook.
3. Run the Jupyter Notebook or Python script containing the analysis code.
4. Follow the instructions and code comments within the notebook/script to execute the analysis steps.
5. Explore the generated visualizations and interpret the results based on the analysis.

## Dependencies

- Python 3.x
- pandas
- scikit-learn
- hvplot
- holoviews

## Contributing

Contributions to this project are welcome.

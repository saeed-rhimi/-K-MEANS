
# K-Means Clustering on Mall Customer Data

## Project Description
This project involves applying K-Means clustering algorithm to a dataset of mall customers to identify different customer segments based on their annual income and spending score. The dataset includes customer information like gender, age, annual income, and spending score.

## Installation and Setup
To run this project, ensure you have the following libraries installed:
- Pandas
- NumPy
- Matplotlib
- scikit-learn

You can install these libraries using pip:
```bash
pip install pandas numpy matplotlib scikit-learn
```

## How to Run the Project
1. Clone the repository to your local machine.
2. Open the Jupyter Notebook (`main.ipynb`).
3. Run each cell in the notebook sequentially to see the results.

## Libraries Used
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Matplotlib: For data visualization.
- scikit-learn: For implementing K-Means clustering.

## Data Description
The dataset (`Mall_Customers.csv`) consists of the following columns:
- CustomerID
- Genre
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Methodology Overview
The project follows these steps:
1. Data loading and preprocessing, including one-hot encoding of categorical data.
2. Application of the Elbow Method to determine the optimal number of clusters.
3. Implementation of K-Means clustering with the determined number of clusters.
4. Visualization of the clusters.

## Results and Visualization
The final output is a scatter plot showing the clusters of customers with their respective centroids. Each cluster is represented in a different color.

## Future Scope or Improvements
- Explore the impact of different features on clustering.
- Experiment with different numbers of clusters and clustering algorithms.
- Analyze the characteristics of each customer segment for targeted marketing strategies.

---

*Note: This project is part of an educational exercise and is meant for demonstration purposes only.*

# Customer-Segmentation-using-K-Means-Clustering
This project focuses on applying K-Means clustering to perform customer segmentation. Customer segmentation involves categorizing a customer base into distinct groups based on certain characteristics. In this case, we use annual income and spending score as features to identify different customer segments.


## Table of Contents
### Introduction
### Dependencies
### Data Collection & Analysis
### Choosing Features
### Choosing the Number of Clusters
### Training the Model
### Visualizing Clusters
### Usage
### Contributing
### License
## Introduction
Understanding customer behavior is essential for businesses to tailor their strategies effectively. Customer segmentation allows businesses to identify groups with similar characteristics and preferences. In this project, we leverage the power of K-Means clustering to automatically categorize customers based on their spending patterns and annual income.

## Dependencies
To run this project, ensure you have the required dependencies installed. These include:

NumPy: A library for numerical operations in Python.
Pandas: A data manipulation and analysis library.
Matplotlib: A plotting library for creating visualizations.
Seaborn: A statistical data visualization library.
Scikit-Learn: A machine learning library containing the K-Means clustering algorithm.
You can install these dependencies using the following command:
pip install numpy pandas matplotlib seaborn scikit-learn
## Data Collection & Analysis
The dataset used in this project is sourced from a CSV file named Mall_Customers.csv. It contains information about customers, including their gender, age, annual income, and spending score. The first step involves loading the data into a Pandas DataFrame and analyzing its structure.

## Choosing Features
For customer segmentation, we focus on two key features: "Annual Income (k$)" and "Spending Score (1-100)." These features provide valuable insights into customer behavior and are crucial for effective segmentation.

## Choosing the Number of Clusters
Determining the optimal number of clusters is a crucial step in K-Means clustering. The Elbow Method is employed, where the Within Clusters Sum of Squares (WCSS) is plotted against different cluster numbers. The point where the rate of decrease slows down (the "elbow") indicates the optimal number of clusters.

## Training the Model
The K-Means clustering model is trained using the selected number of clusters. This step involves assigning each data point to a cluster based on its similarity to the cluster centroids.

## Visualizing Clusters
To gain a deeper understanding, the clusters and their centroids are visualized using a scatter plot. Different clusters are represented by distinct colors, providing a clear view of the segmentation.

## Usage
To use this project, follow these steps:

Clone the repository:

git clone https://github.com/your-username/customer-segmentation.git

Navigate to the project directory:

cd customer-segmentation

Run the Jupyter Notebook:
jupyter notebook Project_Customer_Segmentation.ipynb

### Follow the instructions in the notebook to execute code cells and visualize the results.


# Customer Segmentation Project

## Table of Contents
1. [Description](#description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Project Structure](#project-structure)
5. [Contributing](#contributing)
6. [License](#license)
7. [Authors](#authors)

## Description
This project explores customer segmentation through clustering and dimensionality reduction, leveraging machine learning techniques to identify unique customer groups. Customer segmentation is critical for businesses to understand their customer base and tailor their marketing and product strategies accordingly.

# Clustering
Clustering is an unsupervised learning technique used to group data points based on similarity. In this project, we apply clustering algorithms to group customers with similar purchasing behaviors, preferences, or demographics. Each cluster represents a distinct customer profile, which can then be used to drive targeted actions. Common clustering algorithms include K-means, which seeks to minimize within-cluster variance, and DBSCAN, which focuses on density-based clusters to identify groups and outliers.

# Dimensionality Reduction
Dimensionality reduction simplifies high-dimensional datasets by reducing the number of features while preserving as much meaningful information as possible. This process is essential for enhancing data interpretability, reducing computation time, and improving model performance in some cases. We use techniques like Principal Component Analysis (PCA) to condense data into principal components, capturing the variance of the original features. Dimensionality reduction also aids in visualizing clusters, allowing us to see the natural groupings of customers more clearly.

Through this project, we aim to demonstrate the application of these methods to create insightful customer segments, ultimately supporting data-driven business decisions.

## Installation
To set up the environment, you can use the requirements file:
``bash
pip install -r requirements.txt

## Project Structure

Customer-Segmentation/                                                             
├── README.md                                                             
├── notebook/                                                             
│   └── customer_segmentation.ipynb                                                             
├── data/                                                             
│   ├── train.csv                                                             
│   └── test.csv                                                             
└── requirements.txt

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Authors
Oscar Tibaduiza (oscartibaduiza@hotmail.com)
       

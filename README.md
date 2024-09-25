# Principal Component Analysis (PCA) Assignment
This repository implements Principal Component Analysis (PCA) for dimensionality reduction on two datasets: a synthetic Given Matrix and the real-world Fuel Economy Dataset (fuel-econ.csv). PCA transforms high-dimensional data into a lower-dimensional space while retaining essential variability, aiding in data visualization and improving machine learning efficiency.

## Datasets
1. **Given Matrix**: A synthetic dataset used to test the PCA implementation.
2. **Fuel Economy Dataset**: Contains features such as engine size and weight, demonstrating PCA's practical application.

## Installation
To run the code, install the required libraries with:
bash
pip install pandas numpy scikit-learn

## Usage
Clone the repository and navigate to the project directory. Execute the PCA script to see the results.

## Steps Involved
1. Load datasets.
2. Preprocess data (handle missing values and encode categorical variables).
3. Standardize the data.
4. Calculate the covariance matrix.
5. Perform eigendecomposition to obtain eigenvalues and eigenvectors.
6.  Sort eigenvalues and eigenvectors.
7.  Project data onto the top k principal components.

## Results
The analysis yields a reduced dataset and explained variance for each principal component, enhancing data structure understanding.

## Conclusion
PCA effectively reduces dimensionality while preserving variance, making it a valuable tool for data analysis and visualization.

## References
1. Jolliffe, I. T. (2002). Principal Component Analysis.
2. Bishop, C. M. (2006). Pattern Recognition and Machine Learning.

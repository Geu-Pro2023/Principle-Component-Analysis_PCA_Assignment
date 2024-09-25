Project Overview
This project implements Principal Component Analysis (PCA) to reduce the dimensionality of datasets, improving data visualization and interpretation. The PCA method allows for efficient data compression while preserving the most significant features.

Dataset
The assignment utilizes two datasets:

Given Matrix: This is a synthetic dataset provided for practice with PCA. The initial exploration and calculations were conducted on this matrix.
Fuel Economy Dataset (fuel-econ.csv): This dataset contains various features related to fuel economy, including make, model, year, and MPG (miles per gallon). The analysis focuses on the application of PCA to understand the underlying structure of the data.
Installation
To run this project, ensure you have the following libraries installed:

numpy
pandas
scikit-learn
You can install them using pip:

bash
Copy code
pip install numpy pandas scikit-learn
Usage
Clone the repository or download the files.
Open the Jupyter Notebook or Python script.
Ensure that the dataset (fuel-econ.csv) is in the correct directory.
Run the cells sequentially to perform PCA and view the results.
Steps Involved
The PCA implementation is structured as follows:

Standardization: The datasets are standardized to have a mean of zero and a standard deviation of one.
Covariance Matrix Calculation: The covariance matrix of the standardized data is computed to understand the relationships between different features.
Eigendecomposition: Eigenvalues and eigenvectors are derived from the covariance matrix.
Sorting Eigenvalues and Eigenvectors: The eigenvalues and corresponding eigenvectors are sorted in descending order.
Matrix Multiplication: The standardized data is projected onto the top k principal components to obtain the reduced data.
Results
The output includes:

The standardized data.
Covariance matrix.
Eigenvalues and eigenvectors.
Reduced dataset projected onto the principal components.
The explained variance for each principal component.
Conclusion
PCA successfully reduced the dimensionality of the fuel economy dataset, allowing for more straightforward data analysis and visualization. This method provides insight into the most significant features affecting fuel economy, facilitating better decision-making.

References
Principal Component Analysis - Wikipedia
Scikit-learn Documentation

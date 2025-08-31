# Resistivity-Data-Correction
Geoelectric Resistivity Analysis with Geometric Deep Learning
This repository contains a Jupyter Notebook (Resistivity_v1(2).ipynb) for processing, analyzing, and modeling geoelectric resistivity data. The primary goal of this project is to leverage machine learning, particularly geometric deep learning techniques, to interpret subsurface structures from resistivity measurements.

📖 Overview
Electrical Resistivity Tomography (ERT) is a geophysical method used to image the subsurface. This notebook provides a complete workflow for handling this type of data, including:

Data Loading and Preprocessing: Importing raw data and preparing it for analysis.

Outlier Detection: Identifying and handling anomalous data points that could skew the results using methods like Local Outlier Factor.

Data Interpolation and Visualization: Creating 2D contour maps and visualizations from sparse measurement points using interpolation techniques.

Geometric Deep Learning: Utilizing the torch_geometric library to apply Graph Neural Network (GNN) models, which are well-suited for analyzing the spatially irregular data typical of resistivity surveys.

This project is ideal for geophysicists, data scientists, and researchers interested in applying modern machine learning techniques to geophysical data.

✨ Key Features
Data Cleaning: Implements scikit-learn's StandardScaler for normalization and LocalOutlierFactor for robust anomaly detection.

Scientific Computing: Uses SciPy for powerful data interpolation (griddata) and smoothing (ndimage).

Powerful Visualization: Generates clear and informative plots and contour maps with Matplotlib.

Advanced Modeling: Employs PyTorch Geometric to build and train graph-based deep learning models for sophisticated analysis.

🛠️ Technologies & Libraries Used
The notebook relies on the following core Python libraries:

pandas & numpy: For data manipulation and numerical operations.

scipy: For scientific and technical computing, especially interpolation.

matplotlib: For data visualization.

scikit-learn: For data preprocessing and outlier detection.

torch_geometric: For implementing Graph Neural Networks.

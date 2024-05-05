# Supervised Classification of Astronomical Objects using SDSS Data

## Overview
This repository contains the code and dataset for the supervised classification of stars, galaxies, and quasars using photometric and spectroscopic measurements from the Sloan Digital Sky Survey (SDSS). The project compares the performance of Support Vector Machine (SVM) and Random Forest (RF) algorithms in classifying these astronomical objects.

## Data Source
The dataset includes 100,000 data points from the SDSS database, encompassing detailed photometric and spectroscopic properties. The SDSS is a major astronomical survey that has cataloged hundreds of millions of objects. Data used in this project can be accessed on Kaggle at this link: [Stellar Classification Dataset SDSS17](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17).

## Additional Resources
- **Video Explanation**: A detailed explanation of the project is available on YouTube. Watch it [here](https://www.youtube.com/watch?v=y8Xs6q6gVVs&lc=UgyEM7Kg4kQQ2PyMFOd4AaABAg).

## Data Source
The dataset includes 100,000 data points from the SDSS database, encompassing detailed photometric and spectroscopic properties. The SDSS is a major astronomical survey that has cataloged hundreds of millions of objects.

## Methodology
- **Feature Selection**: Utilizes a Pearson correlation matrix to reduce dimensionality by removing highly correlated features.
- **Handling Unbalanced Data**: Employs the Synthetic Minority Over-sampling Technique (SMOTE) to address class imbalance in the dataset.
- **Model Optimization**: Conducts a grid search in combination with 3-fold cross-validation to find the optimal model parameters.

## Results
- **Performance**: The SVM model achieved a superior test accuracy of 0.940, significantly outperforming the RF model, which had an accuracy of 0.823.
- **Feature Importance**: Spectroscopic data, particularly redshift measurements, were identified as the most significant features for classification.
- **Noise Sensitivity**: Analysis of the model's performance under varying noise conditions revealed the importance of maintaining a high signal-to-noise ratio.

## Usage
Details on how to run the models and reproduce the results are provided in the `SDSS_classification.ipynb` file.


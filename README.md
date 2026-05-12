# Penguin Species Clustering

## Overview

This project explores whether penguin species can be identified using unsupervised machine learning based on morphological measurements.
Using the Palmer Penguins dataset, the analysis examines how physical features such as bill dimensions, flipper length, and body mass relate to biological differences between species.
The goal is to determine whether clustering algorithms can discover natural groupings in the data without using species labels.

## Dataset

The project uses the Palmer Penguins dataset, a well-known dataset for ecological and biological data analysis.

Dataset summary:

- 344 observations
- 3 penguin species: Adelie, Chinstrap, Gentoo
- Multiple morphological measurements

Main features used:

- bill_length_mm
- bill_depth_mm
- flipper_length_mm
- body_mass_g

## Technologies

- Python
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

## Project Workflow

The analysis follows these main steps:

1. **Data Loading and Inspection**  
   Understanding dataset structure and checking for missing values.

2. **Exploratory Data Analysis (EDA)**  
   Visualizing relationships between penguin features and species.  
   The analysis also explores how penguin species are distributed across islands
   and how morphological features vary by location.

4. **Feature Scaling**  
   Standardizing numerical features before clustering.

5. **KMeans Clustering**  
   Applying KMeans to identify natural groupings in the data.  
   The Elbow Method is used to determine the optimal number of clusters.

6. **PCA Visualization**  
   Using Principal Component Analysis to project the data into two dimensions for cluster interpretation.

## Results

The clustering results reveal three distinct groups, which closely correspond to the three penguin species.

Key observations:

- Gentoo penguins tend to have larger body mass and longer flippers
- Adelie penguins are generally smaller in size
- Chinstrap penguins show distinct bill morphology

These differences enable the clustering algorithm to separate species effectively.

## Conclusion

This project demonstrates how unsupervised learning can uncover meaningful structure in biological data.

Using only morphological measurements, the clustering model successfully identifies patterns that align closely with real penguin species.

## References

- Seaborn Penguins Dataset  
  https://seaborn.pydata.org

- Scikit-learn Documentation  
  https://scikit-learn.org

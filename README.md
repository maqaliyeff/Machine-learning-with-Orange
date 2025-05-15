# Dry Bean Classification Project

## Overview
This project implements machine learning algorithms to classify seven different types of dry beans using morphological features extracted from bean images. The project utilizes the Orange data mining tool to analyze and visualize data, implement hierarchical clustering, K-means clustering, and supervised classification algorithms.

## Dataset
The Dry Bean Dataset from UCI Machine Learning Repository contains 13,611 instances of seven different types of dry beans with 16 morphological features extracted from bean images.

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/602/dry+bean+dataset)
- **Creators**: M. Koklu and A. Ozkan (Konya Food and Agriculture University, Turkey)
- **Bean Classes**: BARBUNYA, BOMBAY, CALI, DERMASON, HOROZ, SEKER, SIRA

## Features
The dataset includes morphological features such as:
- Area
- Perimeter
- Major/Minor Axis Length
- Aspect Ratio
- Eccentricity
- Convex Area
- Roundness
- Compactness
- Various Shape Factors

## Project Structure

### Part I: Data Analysis and Visualization
- Statistical representation of the dataset
- Visual analysis using scatter plots, histograms, and feature distributions
- Class balance assessment
- Data grouping identification
- Feature selection

### Part II: Unsupervised Learning
- Hierarchical clustering with various cut-off heights
- K-means clustering with different k values
- Silhouette coefficient analysis
- Assessment of class separability

### Part III: Supervised Learning
- Implementation of Decision Trees
- Implementation of k-Nearest Neighbors (kNN)
- Hyperparameter tuning
- Model comparison and evaluation

## Key Findings
- The dataset is moderately well-separable using both supervised and unsupervised learning methods
- The best performing models achieved approximately 90% classification accuracy
- Certain bean classes (e.g., SEKER and SIRA) exhibit feature similarities that challenge perfect separation

## Tools and Technologies
- **Orange Data Mining Tool**: Used for all data processing, visualization, and model implementation
- **Machine Learning Algorithms**: Hierarchical Clustering, K-means, Decision Trees, k-Nearest Neighbors

## Team
- Sachi Kothari (221ADB212)
- Mahammad Aliyev (231ADB137)
- Muhammed Sinan (231ADB008)

## Academic Context
This project was completed as part of the "Fundamentals of Artificial Intelligence" course at Riga Technical University, Faculty of Computer Science, Information Technology and Energy, for the 2024/2025 academic year.

## License
This project uses the Dry Bean Dataset which is made available for academic and research purposes under the terms of use of the UCI Machine Learning Repository.

## Acknowledgments
- UCI Machine Learning Repository for providing the dataset
- Prof. Alla Anohina-Naumeca for guidance throughout the project

## References
- Koklu, M., & Ozkan, I. A. (2020). Multi-class classification of dry bean seeds based on morphological features. *Computers and Electronics in Agriculture*, 180, 105753.
- Orange Data Mining Tool - [Official Documentation](https://orangedatamining.com)

---
*© 2025 Team 05 - Riga Technical University*

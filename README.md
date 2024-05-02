# Decision Tree classifier on differnet dataset

## Contents

- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Dataset Description](#dataset-description)
- [Result](#result)

## Introduction

The decision tree is a supervised learning algorithm that organizes information in a tree-like structure, representing a set of discrete rules for better understanding. It follows a top-down, or greedy, approach in which the dataset is divided into distinct and non-overlapping regions based on specific criteria.

The algorithm continuously divides the data into smaller parts until reaching a class, using terms such as nodes, edges, and leaf nodes. In the Decision Tree classifier the entropy of the dataset is calculated to measure the uncertainty present. Lower uncertainty indicates better classification results. Information gain for each feature is then computed to determine the reduction in uncertainty after splitting the dataset. The database with the highest information gain is chosen for further splitting, and this process iterates until all nodes are processed, and the tree is constructed.

## Dependencies

To run the code, you need to have the following dependencies installed:
- Python 3.x
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

## Dataset Description

The seed dataset consists of 210 instances of 7 attributes of various kinds of seeds. The task of the seed dataset is to classify the seeds into three different categories: Kama, Rosa, and Canadian. The dataset includes 7 attributes that are used to classify the seeds: area, perimeter, compactness, length, width, asymmetry coefficient, and groove length. Each attribute is a continuous numeric value that can be used to differentiate the seeds.

## Result

The precision values for the three classes are 0.92, 0.96, and 0.95. The recall values of the three classes are 0.92, 0.93, and 1.00. The F1-score values for the three classes are 0.92, 0.95, and 0.97. The accuracy value is 0.94, indicating that the model correctly predicts the class for 94% of the instances in the test dataset.
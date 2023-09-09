# CSEN1022: Assignment 3 - K-Means Clustering

## Team Members

- **Member 1**: Mohamed Ahmed Abdelhamid
  - GUC-ID: 46-16738
  - Elective Tutorial No.: T-3

- **Member 2**: Marwan Khalid Farag
  - GUC-ID: 46-14780
  - Elective Tutorial No.: T-2

## Introduction

This repository contains the code and documentation for the CSEN1022 Assignment 3, which involves performing K-means clustering on a dataset of images. The project was completed as part of the Winter 2022 course.

## Project Overview

In this assignment, we implemented K-means clustering on a dataset of images. The code is organized into the following sections:

### Read Data

The data is read from files using OpenCV and processed into numpy arrays for further analysis.

### K-Means Clustering

The K-means clustering algorithm is implemented, including a function that performs K-means clustering for all three classes in the training data.

### Repeat the Process

The K-means clustering process is repeated 10 times to find the best clustering result based on the Davies-Bouldin Index (DBI).

### Predictions

The centroids from the best clustering result are used to make predictions on the test data, and a confusion matrix is generated to evaluate the performance.

### Visualization

The results are visualized using matplotlib to show the best counts and the confusion matrix.


### Results
The results of the K-means clustering, including the best counts for each class and the confusion matrix, are displayed in the notebook and visualized using matplotlib.

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### Acknowledgments
We would like to thank our instructors and the course staff for their guidance and support during the completion of this assignment.

Feel free to reach out to us if you have any questions or feedback!

Happy coding!

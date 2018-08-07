# Intro To Classifcation - K Nearest Neighbors 

## Using Wisconsin Breast Cancer Data Set

Introducing classification algorithms in Scikit-Learn, used to predict categories or classes by splitting data into groups and placing new data into those groups
 

* The dataset utilized digitized images of breast mass classified as malignant or benign, in addition to other attribute information describing characteristics of the cell nuclei present in the image*
our) h) concave points (number of concave portions of the contour) i) symmetry j) fractal dimension ("coastline approximation" - 1)

## Overview 

### Exploratory Data Analysis
- Leveraging the Pandas library to reassign/drop column names

### Preparing for Model Building
- Encoding Target to Binary Variable
- Creating Target Vector and Predictor Matrix
- Standardizing Predictor Matrix
- Calculating Baseline Accuracy 

### Building KNN Models 
- Building various KNN Models that predict malignant cells using cross-validated scores and standard deviations (changing n_numbers argument to alter amount)
  - 1 Neighbor
  - 3 Neighbors
  - 5 Neighbors
- Comparing and explaining performances of various models

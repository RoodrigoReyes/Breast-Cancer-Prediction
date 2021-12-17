# Breast-Cancer-Prediction
![alt text](https://www.mdanderson.org/cancerwise/2019/12/6-advances-in-breast-cancer-diagnosis-and-treatment/jcr:content/blog/adaptiveimage.resize.648.0.medium.dir.jpg/1575576924970.jpg)

What is sought is to be able to generate a predictive classification model to determine with the patient's data whether or not she may have breast cancer. The data is provided by Kaggle: [Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/

Also can be found on UCI Machine Learning Repository: [https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)

Ten real-valued features are computed for each cell nucleus:

3) Radius (mean of distances from center to points on the perimeter)
4) Texture (standard deviation of gray-scale values)
5) Perimeter
6) Area
7) Smoothness (local variation in radius lengths)
8) Compactness (perimeter^2 / area - 1.0)
9) Concavity (severity of concave portions of the contour)
10) Concave points (number of concave portions of the contour)
11) Symmetry
12) Fractal dimension ("coastline approximation" - 1)

## Dependencies

* Pandas
* Numpy
* Seaborn
* Matplotlib
* Sklearn
* XGBoost
* Warnings
* Graphviz
* Plotly_express

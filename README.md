# AIDI_2004_01
 The contents of this notebook will follow the outline below:

The Data - Exploratory Data Analysis
The Variables - Feature Selection
The Model - Building a Logistic Regression Model
The Prediction - Making Predictions with the Model
Throughout the notebook, I will try to aid your understanding with some visualizations where necessary. I hope you enjoy reading through this notebook, and please leave comments below if you have any questions or feedbacks. I am a total beginner to the field of Data Science, so any feedback is welcome since it helps me realize my mistakes and also allows me to pick up new insights.

Let's dive right into the data now!

1. The Data
Extracted from the UCI ML repository

Attribute Information:
id
diagnosis: M = malignant, B = benign
Columns 3 to 32

Ten real-valued features are computed for each cell nucleus:

radius: distances from center to points on the perimeter
texture: standard deviation of gray-scale values
perimeter
area
smoothness: local variation in radius lengths
compactness: perimeter^2 / area - 1.0
concavity: severity of concave portions of the contour
concave points: number of concave portions of the contour
symmetry
fractal dimension: "coastline approximation" - 1
The mean, standard error, and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

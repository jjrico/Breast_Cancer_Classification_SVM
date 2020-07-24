Breast Cancer Prediction Using Support Vector Machine (SVM) Binary Classifcation
By: Jeremy Rico
Timestamp: 23 Jul, 2020 11:13
Background Information

Introduction:

Breast cancer is the most common type of cancer in women worldwide. With massive amounts of research being done in this area, it is well knows that early detection is one of the most important factors when it comes to saving the life of the patient. Modern Machine Learning techniques can play a large role in identifying whether a tumor is malignant (cancerous) or benign (not cancerous). This projects aims to identify a tumor as malignant or benign based on its physical charactieristics. By recognizing the danger of the tumor early, the patient has a much greater chance of surviving.

Desctiption:

The code works by using a Support Vector Machine (SVM) to classify the input as either one of two options (0 or 1, hence the binary classification). By feeding the network multiple samples of tumors which have already been classified has malignant or benign, it will be able to identify new cases with a high accuracy.

Attribute information:

The network will be fed digitized images of a fine needle aspirate (FNA) of breast mass. Each image will be labeled with an ID number and an M (malignant) or a B (benign). Then, we will calculate 10 features of the cells in the images as seen below.

Attributes:

    ID Number
    Diagnosis (M = malgnant, B = benign)

Features to be computed for each cell nucleus:

    Radius (mean of distance from center to points on the perimeter)
    Texture (std deviation of gray scale values)
    Perimeter
    Area
    Smoothness (local variation in radius lengths)
    Compactness (perimeter^2 / area - 1.0)
    Concavity (severity of concave portions of the contour)
    Concave points (number of concave portions of the contour)
    Symmetry
    Fractal dimension ("coastline approximation" - 1)

Data

Cancer data will be imported from Sklearn library, but it can also be found here for download:

http://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28diagnostic%29

The data was obtained from cancer research performed at the University of Wisoncsin.

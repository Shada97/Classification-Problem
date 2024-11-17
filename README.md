# **Summary**
The goal of this project is to classify diabetes presence using features from a dataset, while exploring the effectiveness of PCA as a dimensionality reduction technique. By reducing the number of features, PCA aims to enhance the computational efficiency of the model while retaining most of the essential information. Both approaches—classification with and without PCA—are compared using metrics such as accuracy, confusion matrices, and classification reports

# **Methodology**
The dataset was preprocessed by removing irrelevant columns and encoding categorical features. Features were then standardized to ensure uniform scaling before applying PCA. For dimensionality reduction, PCA was employed to extract principal components that captured the maximum variance in the data, while minimizing redundancy. Classification was performed using a Support Vector Machine (SVM) model, with the data split into training and testing sets to ensure robust evaluation. Two approaches were implemented for comparison: one without PCA using all features, and another with PCA-reduced features. Model performance was assessed using accuracy, confusion matrices, and classification reports to quantify the impact of dimensionality reduction.

# **Results**
The results highlight the effectiveness of PCA in reducing dimensionality without significant loss of classification accuracy. While the approach without PCA utilized all features, the PCA-based approach significantly reduced the feature set while maintaining comparable model performance. Confusion matrices and classification reports indicate similar precision, recall, and F1-scores for both approaches, validating PCA as a computationally efficient alternative for high-dimensional data.

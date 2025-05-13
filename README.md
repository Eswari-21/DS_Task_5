# DS_Task_5
# Classification Models using SVM and XGBoost
This project demonstrates the application of two classification models: Support Vector Machine (SVM) and XGBoost, using two widely known datasets: the Iris Dataset and the Breast Cancer Dataset. The main objective of this project is to compare the performance of both models and visually examine how accurately they classify data by comparing predicted class distributions with the actual class distributions.

# Datasets
1. Iris Dataset
The Iris dataset is a classical dataset in machine learning used for classification tasks. It contains measurements of four features—sepal length, sepal width, petal length, and petal width—from three species of iris flowers: Setosa, Versicolor, and Virginica.

Features: Sepal length, sepal width, petal length, petal width.

Target: Species (3 classes: Setosa, Versicolor, Virginica).

2. Breast Cancer Dataset
The Breast Cancer dataset is used for binary classification tasks. It contains features computed from breast cancer cell images to classify tumors as either malignant or benign. This dataset is often used in medical applications for detecting cancer.

Features: Measurements related to the properties of cell nuclei (e.g., radius, texture, smoothness).

Target: Tumor type (2 classes: Malignant, Benign).

# Models Used
1. Support Vector Machine (SVM)
SVM is a supervised learning algorithm that is particularly effective for classification tasks. In this project, we use a linear kernel SVM to classify the datasets. The algorithm works by finding the optimal hyperplane that best separates different classes.

2. XGBoost
XGBoost (Extreme Gradient Boosting) is an efficient, scalable, and high-performance machine learning algorithm that is widely used for classification tasks. It leverages gradient boosting techniques and is known for its performance in competitions and real-world applications.

# Methodology
Data Loading: The Iris and Breast Cancer datasets are loaded using scikit-learn's built-in functions.

Data Splitting: The datasets are split into training and testing sets. The models are trained on the training set and tested on the test set to evaluate their performance.

Model Training: Both SVM and XGBoost models are trained on each dataset. SVM uses a linear kernel, while XGBoost is trained using the default settings.

Prediction and Evaluation: After training, both models make predictions on the test set. These predictions are then compared to the true labels of the test set to assess the models' accuracy.

Visualization: The class distribution of the true labels and predicted labels are visualized using bar charts. This helps compare how well the models perform at classifying the data.

# Visualizations
The project generates four bar charts comparing the true class distribution with the predicted class distribution for each model and dataset:

SVM - Iris Dataset: A bar chart that compares the true vs. predicted class counts for the Iris dataset using the SVM model.

SVM - Breast Cancer Dataset: A bar chart comparing the true vs. predicted class counts for the Breast Cancer dataset using the SVM model.

XGBoost - Iris Dataset: A bar chart comparing the true vs. predicted class counts for the Iris dataset using the XGBoost model.

XGBoost - Breast Cancer Dataset: A bar chart comparing the true vs. predicted class counts for the Breast Cancer dataset using the XGBoost model.

These visualizations help assess how well each model is performing on both classification tasks.

# Expected Results
After running the models, you will get four charts that show the comparison of true and predicted class distributions:

The SVM model’s performance on the Iris dataset.

The SVM model’s performance on the Breast Cancer dataset.

The XGBoost model’s performance on the Iris dataset.

The XGBoost model’s performance on the Breast Cancer dataset.

These results allow you to visually compare the accuracy of each model in classifying the datasets.

# Conclusion
By running this project, you will be able to:

Compare the performance of SVM and XGBoost models on two different classification tasks.

Visualize the class distribution of true vs. predicted values to evaluate model performance.

Gain insights into which model works better for each dataset and understand their strengths and weaknesses in classification tasks.

This project showcases how different machine learning models can be applied to solve real-world classification problems and provides a clear way to compare their performance visually.

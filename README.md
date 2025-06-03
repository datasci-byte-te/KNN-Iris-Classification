📘 K-Nearest Neighbors (KNN) Classification – Iris Dataset

🔍 Objective
This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm for a classification problem using the Iris dataset. The goal is to classify iris flowers based on their sepal and petal measurements and visualize decision boundaries.

📁 Dataset
Source: UCI Machine Learning Repository / CSV version of the Iris dataset.

Features:

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

Target: Species (Iris-setosa, Iris-versicolor, Iris-virginica)

Samples: 150 flower records across 3 classes (50 each)

🛠️ Tools & Libraries Used

Python 3 (Google Colab)

pandas – for data handling

numpy – for numerical operations

matplotlib – for visualization

scikit-learn – for preprocessing, modeling, and evaluation

🔄 Workflow
1. Data Loading and Preprocessing
Uploaded and read the Iris CSV dataset.

Dropped the Id column.

Encoded categorical labels into numeric format.

Standardized features using StandardScaler.

2. Train-Test Split
Split the data into 80% training and 20% testing sets using train_test_split.

3. Model Training
Used KNeighborsClassifier from sklearn.

Trained models with k values ranging from 1 to 10.

Evaluated each model using accuracy on the test set.

4. Evaluation
Printed accuracy for each k.

Plotted Accuracy vs K graph.

Displayed confusion matrix for the best-performing model.

5. Visualization
Visualized decision boundaries using only two features:

PetalLengthCm and PetalWidthCm

Plotted classification zones and correctly labeled data points.

📊 Results
Achieved highest accuracy with an optimal value of K = 2 (varies slightly per run).

Plotted decision regions show clear separation between species based on petal size.


📈 Sample Visuals

Accuracy vs K Plot

Confusion Matrix

Decision Boundary (Petal Length vs Petal Width)


🧠 Concepts Practiced

Data preprocessing & normalization

KNN algorithm for classification

Model evaluation using confusion matrix & accuracy

Data visualization techniques


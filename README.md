# School Project
## Dataset
- **iris_reduced.csv**: A reduced version of the Iris dataset used in the project.
- **banana.csv**: The Banana dataset used for additional classification tasks.
## 1. **Data Visualization**
- **Technologies**:
  - **Pandas**: Used for reading and processing the Iris dataset (`iris_reduced.csv`).
  - **Matplotlib**: Visualized the feature distributions and relationships between features in the dataset.
  - **Seaborn**: Set the color scheme for better visual representation.
  - **NumPy**: Utilized for numerical operations during data analysis.

## 2. **Perceptron Algorithm for Classification**
- **Technologies**:
  - **Scikit-learn**:
    - **Perceptron**: Implemented the Perceptron algorithm to classify the Iris dataset.
    - **Train-test split**: Divided the dataset into training and testing sets for model evaluation.
    - **Accuracy Score**: Used to evaluate the model's performance.
  - **Matplotlib**: Plotted the decision boundary of the trained Perceptron model on the Iris dataset to visualize the learning process.

## 3. **Binary Classification**
- **Technologies**:
  - **Pandas**: Used to handle and read the Banana dataset (`banana.csv`), performing data cleaning and preprocessing.
  - **Scikit-learn**:
    - **Perceptron**: The Perceptron algorithm was applied to the Banana dataset for binary classification.
    - **Train-test split**: Split the Banana dataset into training and testing sets to evaluate the model's generalization ability.
    - **Accuracy Score**: Assessed the classification accuracy of the Perceptron model.
  - **Matplotlib**: Plotted the distribution of the classes and the feature space to better understand the dataset's structure.

## 4. **K-Nearest Neighbors (KNN)**
- **Technologies**:
  - **Scikit-learn**:
    - **KNeighborsClassifier**: Implemented the K-Nearest Neighbors algorithm on the Banana dataset.
    - **Train-test split**: Split the Banana dataset into training and testing sets to evaluate the model's performance.
    - **Accuracy Score**: Calculated the accuracy of the KNN model for various values of k (the number of neighbors).
  - **Matplotlib**: Plotted the evolution of accuracy scores as the number of neighbors (k) varied, helping to identify the optimal value of k for the best performance.

## Installation

To run the projects, you can install the necessary dependencies by running the following command:

```bash
pip install -r requirements.txt

# Logistic Regression - Breast Cancer Diagnostic

This project utilizes logistic regression to predict whether breast cancer is benign or malignant. Leveraging mathematical concepts and Python libraries such as numpy, matplotlib, seaborn, and math, this project dives into the realm of machine learning with a focus on cancer diagnostics.

## Project Overview

The primary goal of this project is to develop a robust logistic regression model capable of accurately classifying breast cancer. The process involves several steps:

1. **Loading and Exploring the Data**: Understanding the dataset is crucial. This step involves loading the data and gaining insights through exploratory data analysis.

2. **Data Cleaning and Transformation**: Cleaning the data from nulls and irrelevant features is essential for building a reliable model. Additionally, transforming categorical target values into numerical representations is necessary for logistic regression.

3. **Feature Extraction**: Extracting relevant predictors from the dataset is crucial. This project extracted around 31 features along with the target values.

4. **Train-Test Split**: Implementing a custom train-test split function ensures that the model's performance can be accurately evaluated. This project implemented a random split to ensure the robustness of the model.

5. **Prediction and Evaluation**: Implementing key functions such as the sigmoid function, prediction function, and gradient descent algorithm from scratch ensures a deep understanding of logistic regression. These functions are vital for making predictions, computing costs, and optimizing the model through gradient descent.

6. **Model Training and Evaluation**: Training the logistic regression model on the training data and evaluating its performance using custom-built evaluation metrics, including accuracy, provides insights into its effectiveness in diagnosing breast cancer.

## Libraries Used

- `numpy`: For numerical operations and array manipulations.
- `matplotlib`: For data visualization and plotting.
- `seaborn`: For enhancing the visual aesthetics of plots.
- `math`: For mathematical operations.

## Getting Started

To get started with the project, follow these steps:

1. [Open in colab]()
2. Explore the generated plots and visualizations to analyze the data and model performance.
3. Experiment with different parameters and features to further enhance the model's accuracy.

## Acknowledgments

Special thanks to the creators and contributors of the libraries used in this project for their invaluable work and contributions to the open-source community.

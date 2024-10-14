# Softmax and Gaussian Discriminant Analysis (GDA)

## Overview
This project implements Softmax regression and Gaussian Discriminant Analysis (GDA) on a dataset with 178 samples and 6 features. The aim is to analyze the performance of multinomial logistic regression using the softmax function and to evaluate training and testing accuracy under various configurations.

## Goals
- To implement multinomial logistic regression using softmax.
- To preprocess the input data effectively for model training.
- To evaluate model performance by analyzing accuracy for different batch sizes and learning rates.
- To visualize the results of the implemented methods.

## Approach
1. **Data Preprocessing**: 
   - Load the dataset and handle missing values, if any.
   - Normalize the feature values to enhance model performance.

2. **Softmax Implementation**:
   - Develop a function for the softmax activation.
   - Implement the multinomial logistic regression model.

3. **Gaussian Discriminant Analysis (GDA)**:
   - Apply GDA to understand the distribution of features across classes.
   - Analyze the decision boundaries formed by the GDA.

4. **Performance Evaluation**:
   - Train the model using various configurations of batch sizes and learning rates.
   - Compute training and testing accuracy for each configuration.
   - Create visualizations to represent model performance.

## Results
- The accuracy metrics for each configuration are recorded.
- Visualizations illustrate the impact of different hyperparameters on model performance.

## Conclusion
This assignment provides valuable insights into the effectiveness of softmax regression and GDA in classification tasks, emphasizing the importance of proper data preprocessing and hyperparameter tuning.

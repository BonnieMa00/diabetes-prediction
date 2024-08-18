# Diabetes Prediction Using Machine Learning

## Project Overview

This project focuses on developing predictive models for early diabetes detection, addressing a critical need in healthcare to improve patient outcomes and reduce associated costs. By leveraging various machine learning techniques, the goal is to identify individuals at high risk of developing diabetes, enabling timely interventions.

## Key Features

- **Data Preprocessing**: Cleaned and preprocessed the dataset to handle missing values and remove duplicates, ensuring the integrity of the training data.
- **Model Development**:
  - **Logistic Regression**: Built and evaluated a logistic regression model to predict diabetes risk, balancing precision and recall.
  - **Classification Tree (CART)**: Developed a CART model that achieved the highest accuracy and perfect precision, making it ideal for minimizing false positives.
  - **Lasso Regression**: Implemented a Lasso regression model to handle feature selection, providing a balanced approach between detecting positive cases and minimizing false positives.
- **Model Evaluation**: Assessed the models based on accuracy, precision, recall, and F1-score to determine the best approach for early diabetes detection.

## Results

- **CART**: Highest accuracy and perfect precision but with lower recall, ideal for scenarios where avoiding false positives is critical.
- **Logistic and Lasso Regression**: Provided balanced precision and recall, making them reliable for detecting positive cases while minimizing false positives.

## Future Work

- **Explore Additional Models**: Investigate other machine learning models, such as Random Forests or Gradient Boosting, for potential performance improvements.
- **Real-World Testing**: Implement the model in clinical settings and refine it based on real-world feedback.
- **Continuous Monitoring**: Regularly monitor the model's performance to ensure its accuracy and relevance over time.

## Other Related Projects

- **Tuberculosis Detection in Chest X-Rays**: Developed a convolutional neural network using PyTorch to detect tuberculosis in chest X-ray images, achieving a 99.17% accuracy. This model significantly improves early TB detection, aiding healthcare professionals in resource allocation.
- **Audit Report Analysis using LLM**: Created a large language model for audit report analysis, with potential applications in healthcare for enhancing decision-making processes.

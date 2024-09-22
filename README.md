# Student Performance Prediction

This project aims to predict student performance by analyzing various factors like **attendance, parental support, parental education, study hours, tutoring, extracurricular activities**, and more. I explore the relationships between these factors and student performance through **data visualizations**, allowing insights into which activities most impact academic outcomes.

## Project Workflow:
1. **Data Exploration & Visualization**:  
   Graphs and visualizations are used to understand the effect of different features on student performance, identifying key patterns and trends.
   
2. **Feature Engineering**:  
   - **Dropped irrelevant columns** that had minimal or no effect on the target variable (performance score).  
   - **Created new features** to enhance prediction capabilities.

3. **Model Building & Evaluation**:  
   I applied various machine learning algorithms to predict the target variable and compared the accuracy of each model to determine the best-performing one.

### Model Accuracy Comparison:
| Model | Accuracy (%) |
|-------|--------------|
| **Multinomial Naive Bayes** | 61.8 |
| **Naive Bayes** | 77.04 |
| **KNN** | 77.45 |
| **Neural Networks** | 79.12 |
| **Logistic Regression** | 80.17 |
| **SVM** | 84.13 |
| **Decision Tree** | 85.8 |
| **Extra Tree Classifier** | 87.27 |
| **Random Forest** | 92.69 |
| **AdaBoost** | 92.69 |
| **Gradient Boosting** | 93.11 |

## Conclusion:
Through this project, **Gradient Boosting** emerged as the most accurate model with an accuracy of **93.11%**, outperforming others. The results indicate that a combination of proper data preprocessing, feature selection, and robust algorithms can significantly enhance prediction capabilities.

https://github.com/user-attachments/assets/57fc4bf5-c03c-4ae6-ac65-cc49fa8d22b7


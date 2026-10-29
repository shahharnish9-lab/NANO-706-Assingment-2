Assignment-2 NANO-706
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/ff2c6cdb-b536-4b2b-97d7-ec168f1e851c" />
<img width="554" height="455" alt="image" src="https://github.com/user-attachments/assets/3f5d5a70-779b-468a-a9e6-0b419fe62ac3" />
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/1befb1b4-1579-4de2-830b-0c3869522131" />
# Wine Dataset Visualization and Machine Learning Classification

## 1. Introduction

The objective of this assignment was to visualize the wine dataset and apply machine learning algorithms to classify wine samples based on their chemical properties. Python libraries including Pandas, Matplotlib, and Scikit-learn were used for data analysis and visualization. Three classification models were evaluated: Support Vector Machine (SVM), Decision Tree, and Logistic Regression.

## 2. Results and Discussion

### Figure 1: Wine Dataset Visualization

**[Insert Alcohol vs. Malic Acid Scatter Plot Here]**

*Figure 1. Scatter plot showing the distribution of three wine classes based on alcohol concentration and malic acid content.*

The scatter plot shows differences in alcohol and malic acid concentrations among the three wine classes. Some clusters are visible, although overlapping data points suggest that these two features alone may not completely distinguish the wine classes.

### Figure 2: Decision Tree Feature Importance

**[Insert Decision Tree Feature Importance Bar Graph Here]**

*Figure 2. Relative importance of chemical features used by the Decision Tree model for wine classification.*

The Decision Tree model achieved **96% accuracy**. Flavanoids and color intensity were identified as the most important features, each contributing approximately 41%, followed by proline at approximately 13%. These results suggest that these chemical properties strongly influence the model's classification decisions.

### Figure 3: Logistic Regression Classification

**[Insert Logistic Regression Scatter Plot Here]**

*Figure 3. Visualization of predicted wine classes using Logistic Regression based on alcohol and malic acid features.*

The Logistic Regression model achieved **74% accuracy**. The visualization shows that some wine classes overlap, making classification more challenging when using only two features.

## 3. Model Performance Comparison

| Model | Accuracy |
|---|---|
| Support Vector Machine (SVM) | 98% |
| Decision Tree | 96% |
| Logistic Regression | 74% |

SVM achieved the highest accuracy, followed closely by Decision Tree. Logistic Regression showed lower accuracy, potentially because it was trained using only two features rather than the complete feature set.

## 4. Conclusion

This assignment demonstrated how data visualization and machine learning can be used to explore and classify wine samples. SVM achieved the highest classification accuracy of 98%, while Decision Tree helped identify the most influential chemical features. Overall, the analysis highlighted the importance of selecting relevant features and evaluating different machine learning models for accurate classification.

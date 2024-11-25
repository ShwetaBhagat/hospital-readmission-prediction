# Predictive Analytics Project: Hospital Readmission Prediction

## Project Overview
This project aims to leverage predictive analytics techniques to predict early hospital readmissions within 30 days of discharge. It combines classification and clustering methodologies to uncover patterns and insights, providing a robust framework for understanding and addressing readmission risks.

## Objectives
- **Predict Hospital Readmissions**: Build and evaluate models to predict the likelihood of patients being readmitted within 30 days.
- **Address Data Imbalances**: Utilize techniques like SMOTE to balance the dataset for improved model performance.
- **Cluster Patient Profiles**: Apply clustering algorithms (e.g., K-Means) to identify patient groups with similar readmission characteristics.
- **Enhance Predictive Accuracy**: Explore the benefits of local classifiers based on clusters compared to a global model.

## Key Features
- **Data Preprocessing**:
  - Removed irrelevant columns and handled missing values.
  - Converted categorical variables to numerical formats.
  - Scaled features using Min-Max scaling.
  - Visualized data distributions and relationships using scatter plots, histograms, and correlation matrices.
- **Model Development**:
  - Implemented a logistic regression model as the baseline.
  - Balanced the dataset using under-sampling and SMOTE.
  - Evaluated models using metrics such as accuracy, precision, recall, and F1 score.
- **Clustering**:
  - Applied K-Means clustering to segment data.
  - Visualized clusters using PCA and analyzed their relation to readmission rates.
  - Built local classifiers for clusters to improve predictive performance.

## Tools and Technologies
- **Programming Language**: Python (Jupyter Notebook)
- **Libraries**: Pandas, NumPy, Matplotlib, Scikit-learn
- **Dataset**: Diabetic hospital dataset (de-identified patient data)

## Results
- **Data Visualization**:
  - Uncovered imbalances in readmission rates and identified trends across age groups and medication counts.
- **Model Performance**:
  - Logistic regression showed improved recall and F1 scores after balancing the dataset.
  - Local classifiers for clusters provided nuanced insights but did not outperform the global model.
- **Clustering Insights**:
  - Clusters revealed distinct patient profiles with varying readmission risks.

## Conclusion
This project demonstrates the importance of feature engineering, data balancing, and clustering in predictive analytics for healthcare. By addressing imbalances and tailoring models to specific patient groups, the framework offers actionable insights for reducing hospital readmissions.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

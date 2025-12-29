# SpaceX Falcon 9 Landing Prediction

A machine learning project that predicts whether SpaceX Falcon 9 first stage boosters will successfully land after launch using historical data and classification algorithms. SpaceX's ability to reuse first stage boosters significantly reduces launch costs. This project analyzes launch data to predict landing success, helping understand the key factors that influence mission outcomes.

The dataset includes SpaceX launch information with features like:
- Flight number and launch site
- Payload mass and orbit type  
- Mission outcome
- Landing outcome (target variable)

## Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- **Python**: Pandas, NumPy, Scikit-learn, Plotly, Dash
- **Visualization**: Matplotlib, Seaborn
- **Environment**: Jupyter Notebooks, Python Files

## Key Results

### Best Model Performance: Random Forest Classifier
- **Accuracy**: 88.5%
- **Precision**: 0.86 (86% of predicted successes were actually successful)
- **Recall**: 0.91 (91% of actual successes were correctly identified)
- **F1-Score**: 0.88 (harmonic mean of precision and recall)
- **AUC-ROC**: 0.92 (excellent discrimination capability)

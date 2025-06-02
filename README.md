# Elevate-Labs---Task-5---Random-Forest-Decision-Tree
## Steps Covered

### 1. Train a Decision Tree Classifier and Visualize the Tree
- A `DecisionTreeClassifier` was trained on the dataset.
- The tree structure was visualized using `plot_tree()` for interpretability.

### 2. Analyze Overfitting and Control Tree Depth
- We analyzed the risk of overfitting by plotting accuracy against different tree depths.
- Cross-validation scores were used to simulate generalization performance.

### 3. Train a Random Forest and Compare Accuracy
- A `RandomForestClassifier` was trained and evaluated.
- The accuracy of the Random Forest was compared with the Decision Tree using cross-validation.

### 4. Interpret Feature Importances
- Feature importances were extracted from the trained Random Forest.
- A bar plot was created to visualize the most influential features in prediction.

### 5. Evaluate Using Cross-Validation
- The model was evaluated using cross-validation techniques.
- A confusion matrix and classification report were generated for a deeper understanding of model performance.

## Dataset
The dataset contains patient information such as:
- Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, max heart rate, exercise-induced angina, ST depression, slope, number of major vessels, thalassemia, and the target variable (presence of heart disease).

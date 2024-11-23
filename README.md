
# Mushroom Classification Using Decision Trees

The goal of this project is to develop a machine learning model that can accurately classify mushrooms into edible vs poisonous based on their features. The model is built using Decision Tree classifier.

## Dataset

- **Source**: The dataset used is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/mushroom)
- **Description**: The dataset contains details about mushroom characteristics, such as cap shape, odor, gill color, etc.
- **Target Variable**: `class` - Whether the mushroom is `edible (e)` or `poisonous (p)`.

## Features

The dataset includes the following key features:

- **Cap Shape**: bell, conical, convex, flat, etc.
- **Odor**: almond, anise, foul, none, etc.
- **Gill Spacing**: close, crowded, distant.
- **Stalk Shape**: enlarging,tapering
- **Other Features**: Cap surface, stalk root, population, habitat, etc.

## Requirements

The following Python libraries are required to run the notebook:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Steps in the Notebook

1. **Data Loading**:
   - Load the dataset and inspect the structure.
   
2. **Exploratory Data Analysis (EDA)**:
   - Check for missing values (if any) and perform feature selection.
   
3. **Data Preprocessing**:
   - Encode categorical variables using one-hot encoding.
   - Split the data into training and testing sets.
   
4. **Model Building**:
   - Train a Decision Tree Classifier on the training set using Decision Tree, Random Forest and XGBoost.
   - Visualize the accuracy score for a range of various hyperparameters like min_samples_split, max_depth, n_estimators.
   
5. **Model Evaluation**:
   - Evaluate the model's accuracy on the test set.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

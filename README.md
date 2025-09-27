# Heart Disease Prediction and Feature Analysis

## 📌 Overview

This project analyzes a heart disease dataset (`heart.csv`) and builds an Artificial Neural Network (ANN) to predict the presence of heart disease. The notebook explores feature relevance, statistical tests, and model performance with different activation functions and dropout rates.

## 🔍 Project Workflow

1. **Data Loading & Preprocessing**

   * Load dataset using `pandas`.
   * Encode categorical variables with `LabelEncoder`.
   * Normalize features using `StandardScaler`.

2. **Feature Analysis**

   * **Mutual Information** to measure feature importance.
   * **Statistical Tests**:

     * *T-test* for numerical features.
     * *Chi-square test* for categorical features.
   * **Visualization**:

     * Correlation heatmaps.
     * Contour plots for feature interactions.

3. **Modeling: Artificial Neural Network (ANN)**

   * Implement ANN using **TensorFlow/Keras**.
   * Experiment with different activation functions (ReLU, Sigmoid, Tanh, etc.).
   * Apply dropout regularization to prevent overfitting.

4. **Evaluation**

   * Compare accuracy across different models.
   * Analyze the effect of activation functions and dropout rates.

5. **Conclusion**

   * Identify the most important features.
   * Summarize how activation functions and dropout influence ANN performance.

## 🛠️ Requirements

Make sure the following libraries are installed:

```bash
pip install pandas numpy scikit-learn scipy matplotlib seaborn tensorflow
```

## ▶️ Usage

1. Upload the `heart.csv` dataset into the notebook environment (e.g., Google Colab).
2. Run all cells sequentially.
3. Review the feature analysis, model training results, and conclusions.

## 📊 Output

* Feature importance rankings.
* Statistical significance of features.
* Accuracy comparison of ANN models.
* Visualizations (heatmaps, contour plots).

## 📁 Dataset

The dataset (`heart.csv`) contains patient health attributes and a target column (`target`) indicating the presence of heart disease (1 = disease, 0 = no disease).

## 🚀 Future Improvements

* Perform hyperparameter tuning for deeper ANN architectures.
* Try ensemble models (Random Forest, XGBoost) for comparison.
* Apply cross-validation for more robust performance metrics.

---

✍️ **Author:** Souvik Biswas
📌 **Project:** Heart Disease Feature Analysis & ANN Modeling

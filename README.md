# 🧠 Breast Cancer Prediction Using SVM

📊 A machine learning project focused on predicting whether a breast tumor is malignant or benign using Support Vector Machine (SVM). The dataset contains key medical attributes of breast cancer cases, making it ideal for binary classification tasks.

**Dataset Source**: [Breast Cancer Wisconsin Data (Kaggle)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

---

## 📁 Project Structure

* `breast_cancer_svm.ipynb`: Main script containing data exploration, visualization, and SVM implementation.
* `data.csv`: Dataset with 33 features, including tumor radius, perimeter, texture, and diagnosis labels.
* `requirements.txt`: Python dependencies required to run the project.

---

## 📈 Key Insights

* **Predictive Model**: Built an SVM model with RBF kernel for classifying tumors as malignant or benign.
* **Exploratory Insights**:
  - Utilized visualizations like count plots, bar plots, and histograms to analyze features like `radius_mean` and their relationships to tumor diagnosis.
  - High correlation observed amongst `radius_mean`, `perimeter_mean`, and `area_mean`.
* **Hyperparameter Tuning**: Performed Grid Search with cross-validation to optimize the C and gamma hyperparameters for the RBF kernel.
* **Model Performance**:
  - **Baseline Model (Default Parameters)**: Achieved 98% accuracy with well-suited initial hyperparameters.
  - **Tuned Model**: Found optimal parameters (`C=10`, `gamma=0.001`) achieving 96% accuracy.

---

## 🛠️ Tools Used

* Python (Pandas, Seaborn, Matplotlib, Scikit-Learn)
* Confusion Matrix Visualization
* Jupyter Notebook (optional, for data exploration)
* SVM Hyperparameter Tuning (GridSearchCV)

---

## 📋 Model Evaluation Results

* **Baseline Model Performance**:
  - Accuracy: **98%**
  - Misclassifications: **3**
* **Optimized Model Performance (Grid Search)**:
  - Accuracy: **96%**
  - Misclassifications: **6**
* Confusion matrices and classification reports generated for comprehensive evaluation.
* Performance analysis:
  - Baseline model demonstrated strong performance; tuning did not yield significant improvement as default parameters were well-suited to this dataset.

---

## 🔬 Conclusion

- **Effectiveness**: Support Vector Machines demonstrated excellent performance in predicting breast cancer outcomes.
- **High-dimensional Data**: SVM's strength with high-dimensional datasets (31 numerical features) was evident in achieving high accuracy (>96%).
- **Application**: This approach showcases the potential for reliable automated cancer diagnostic systems using machine learning.

---

📫 **Contact**: [www.linkedin.com/in/kanishkayadvv](https://www.linkedin.com/in/kanishkayadvv)

**Author**: Kanishka Yadav

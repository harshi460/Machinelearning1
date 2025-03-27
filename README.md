#  Decision Trees vs. Random Forests: Breast Cancer Classification

This project is a machine learning tutorial focused on comparing **Decision Trees** and **Random Forests** using the **Breast Cancer Wisconsin** dataset. The goal is to explore how both models perform, analyze their strengths and weaknesses, and understand the impact of model tuning and feature importance in a real-world classification task.

##  Project Contents

- `notebook.ipynb` – Jupyter Notebook containing the code, visualizations, and evaluation.
- `tutorial.pdf` – Final report explaining the approach, results, and analysis.
- `assets/` – Contains plots like confusion matrices and feature importance charts.
- `README.md` – Project overview and instructions.
- `LICENSE` – Open-source license (MIT by default).

##  Dataset

- **Name:** Breast Cancer Wisconsin (Diagnostic)
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Features:** 30 numerical attributes related to tumor characteristics
- **Target:** Binary classification – malignant (0) or benign (1)

##  Models Used

- **Decision Tree Classifier**
- **Random Forest Classifier**

Evaluation metrics include:
- Accuracy
- Confusion Matrix
- Classification Report
- Feature Importance

##  Tools & Libraries

- Python 3
- Scikit-learn
- Matplotlib
- Seaborn
- NumPy
- Pandas

##  Results Summary

| Model           | Test Accuracy |
|----------------|----------------|
| Decision Tree  | 94.7%          |
| Random Forest  | 96.5%          |

Random Forest outperformed the Decision Tree in terms of generalization and consistency, making it a better choice for medical classification tasks.

##  License

This project is licensed under the MIT License. See the `LICENSE` file for details.

##  Author

- **Your Name**
- University of Hertfordshire  
- Module: Machine Learning & Neural Computation  
- Individual Assignment Tutorial  

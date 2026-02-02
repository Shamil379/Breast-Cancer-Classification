# Breast-Cancer-Classification

📊 Dataset

Source: sklearn.datasets.load_breast_cancer()

Features: 30 numerical features

Target: Binary classification (0 = Malignant, 1 = Benign)

⚙️ Workflow

Load and inspect dataset (features & label distribution)

Apply StandardScaler for feature normalization

Split data into training and testing sets

Train baseline Linear SVM

Train RBF SVM and compare performance

Tune hyperparameters (C, gamma) using GridSearchCV

Evaluate best model using:

Confusion Matrix

Classification Report

Plot ROC Curve and compute AUC score

Save the tuned Pipeline (Scaler + SVM) for reuse

📈 Results

RBF SVM outperforms linear SVM

Optimized model achieves high accuracy and strong AUC score

ROC curve visualizes model’s classification capability

📁 Files Included

Breast_Cancer_SVM.ipynb – Complete Jupyter Notebook

roc_curve.png – ROC curve visualization

breast_cancer_svm_model.joblib – Saved trained model pipeline

🛠 Libraries Used

NumPy, Pandas, Matplotlib

Scikit-learn

Joblib

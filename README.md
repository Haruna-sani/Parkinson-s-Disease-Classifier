🧠 **Parkinson's Disease Classification using Random Forest and Support Vector Machine (SVC)**

This project presents a machine learning approach to classify Parkinson's disease using a publicly available dataset. The goal was to build robust classification models and evaluate their performance using Random Forest (RF) and Support Vector Machine (SVC) classifiers.

🔍 Project Highlights

🌳 **Random Forest Classifier**

The Random Forest model was trained using different tree sizes by varying the number of estimators from 100 to 400. The model achieved its highest accuracy of 91.38% with 100 trees. Interestingly, increasing the number of trees beyond this point did not significantly improve the model's performance. In fact, slight drops in accuracy were observed as the number of trees increased, highlighting that a smaller, well-tuned RF model can sometimes outperform more complex configurations.

🤖 **Support Vector Machine (SVC) Classifier**

SVC models were trained using both RBF and linear kernels, while adjusting the regularization parameter C with values ranging from 0.0001 to 0.1. The best performance was recorded at 85.25% accuracy using a linear kernel with C = 0.1. The lowest performance (72.80%) occurred with the RBF kernel and C = 0.0001, suggesting the model was underfitting at this configuration. This indicates that the SVC classifier benefits significantly from kernel and hyperparameter tuning, and that a linear decision boundary performed better for this dataset.

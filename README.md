# NSL-Kdd-benchmark
📚 Dataset: NSL-KDD
The NSL-KDD dataset is a refined version of the original KDD'99 dataset. It improves upon the original by:

Removing redundant records

Offering a more balanced train/test split

Being more realistic for evaluating IDS models

Classification Objective:
Classify network traffic as either normal or an attack type (e.g., DoS, Probe, R2L, U2R).

🧪 Models Evaluated
The following models were benchmarked:

- Logistic Regression
- Decision Tree( Cart , C4.5 , id3)
- Random Forest
- XGBoost , LightGbm , Catboost
- Support Vector Machine (Linear , Rbf kernel) 
- k-Nearest Neighbors 
- Deep neural network
- Multi-Layer Perceptron (MLP)
- Tabnet

⚙️ Preprocessing
Handled missing or inconsistent values

One-hot encoded categorical features

Normalized numerical features

Converted labels to binary (Normal vs. Attack) and multi-class (4 attack types + normal)

📊 Metrics
Each model was evaluated using:

Accuracy

Precision, Recall, F1-Score

ROC-AUC

Confusion Matrix

#  Customer Churn Prediction with DataRobot

This project uses **DataRobot AutoML** to build and deploy a machine learning model that predicts customer churn. The model selected is the **Elastic-Net Classifier**, which achieved a strong AUC performance and was recommended for deployment by DataRobot.

---


##  Objective

The goal is to identify customers likely to **churn** (stop using a service) based on historical data. This helps businesses retain valuable customers by proactively offering support or incentives.

---

##  Dataset

- **File**: `customer_churn.csv`
- **Features**: Customer behavior, demographics, and usage
- **Target**: `Churn` (1 = churned, 0 = retained)

---

##  Model Used

- **Algorithm**: Elastic-Net Classifier (α=0.5)
- **Features Used**: 100% informative features selected by DataRobot
- **Validation Metric**: AUC (Area Under Curve)
- **Cross-validation score**: ~0.8956

---

##  Evaluation Metrics

| Metric          | Value     |
|-----------------|-----------|
| AUC (Validation)| 0.8993    |
| AUC (Cross Val) | 0.8956    |
| AUC (Holdout)   | 0.9378    |

The model showed strong generalization performance across all folds.

---

##  How to Run the Notebook

 Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-churn-datarobot.git
   cd customer-churn-datarobot

pip install -r requirements.txt

jupyter notebook churn file.ipynb

pip install -r requirements.txt

pandas
numpy
matplotlib
seaborn
scikit-learn
datarobot

## Contact
Author: Karthik Boya

Email: karthikb7255@gmail.com

Tool Used: DataRobot




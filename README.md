# Feature Engineering: Standardization on Social Network Ads Dataset

This project demonstrates **feature transformation** using **standardization** on the Social Network Ads dataset from Kaggle.

## Dataset

- **Features Used:**  
  - `Age`  
  - `EstimatedSalary`  
- **Target:**  
  - `Purchased` (binary classification: 0 or 1)

## Steps Performed

1. **Data Loading & Preprocessing**
   - Imported dataset using `pandas`.
   - Separated features (`X`) and target (`y`).

2. **Train-Test Split**
   - Split dataset into train and test sets (70%-30%) using `train_test_split`.

3. **Standardization**
   - Applied `StandardScaler` to scale features (`Age` and `EstimatedSalary`).
   - Compared **before and after scaling** with scatter plots to visualize impact.

4. **Model Training**
   - Trained a simple **Logistic Regression** model on both raw and scaled features.
   - Observed **accuracy score** for comparison.

5. **Key Observations**
   - Scaling features improves **interpretability** and **visualization**.
   - Logistic Regression scores remained similar, but scaled features are crucial for **gradient-based models**.

## Next Steps

- Explore **Normalization** as another feature transformation technique.
- Understand the impact on model convergence and performance.

## Libraries Used

- `numpy`  
- `pandas`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`

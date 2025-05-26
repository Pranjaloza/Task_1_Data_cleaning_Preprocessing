# Heart Disease Data Cleaning and Preprocessing
This repository contains a Jupyter Notebook that performs data cleaning, preprocessing, and visualization on the UCI Heart Disease dataset.

#  What I have done
- Loaded and inspected the dataset using `pandas`.
- Handled missing values:
  - Used **median imputation** for numerical columns.
  - Used **most frequent value imputation** for categorical columns.
- Performed **one-hot encoding** for categorical variables.
- Scaled numerical features using **StandardScaler**.
- Detected and removed outliers using **IQR (Interquartile Range)** method.
- Visualized numerical features before and after outlier removal using **Seaborn boxplots**.

  ## Dataset

- UCI Heart Disease dataset (`heart_disease_uci.csv`).

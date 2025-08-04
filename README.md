
---

## 📌 Project Overview

- **Dataset:** Titanic survival dataset (CSV format)
- **Goal:** Clean and preprocess the data to make it ready for analysis or modeling
- **Libraries used:**
  - `pandas`
  - `numpy`
  - `sklearn` (for imputing, encoding, and scaling)

---

## 🧼 Key Cleaning Steps

1. **Loading the dataset**
2. **Handling missing values**
   - `Age` and `Fare`: Imputed using **median**
   - `Embarked`: Imputed using **most frequent**
3. **Encoding categorical variables**
   - `Sex` and `Embarked`: Encoded using **LabelEncoder**
4. **Feature scaling**
   - Standardized `Age`, `Fare`, `SibSp`, and `Parch` using **StandardScaler**
5. **Exporting the cleaned dataset** to `data/titanic_cleaned.csv`

---

## 📷 Snapshots Included

Found in the `/screenshots` folder:

| Snapshot Name | Description |
|---------------|-------------|
| `Initial dataset preview.png` | Raw dataset preview |
| `Initial dataset info.png` | Initial dataset info (missing values and dtypes) |
| `Initial statistical summary.png` | Stats before cleaning |
| `Age & Fare before Imputation.png` | Distribution before imputing |
| `Age & Fare after Imputation.png` | Distribution after imputing |
| `Final cleaned Dataset preview.png` | Final cleaned dataset preview |

---

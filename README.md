# Gender Classification using Dental Measurements

## 📌 Project Overview
This project applies machine learning techniques to classify gender based on dental measurements. The dataset contains various numerical dental attributes, which are analyzed and used to train multiple classification models.

## 📂 Dataset
**File:** `Dentistry Dataset.csv`

**Key Columns:**
- `Gender` (Target variable: Male/Female)
- Various dental measurements (Independent features)
- `Sl No`, `Sample ID` (Dropped during preprocessing)

## 🛠️ Steps Followed
1. **Data Preprocessing**
   - Removed unnecessary columns
   - Encoded categorical variable (`Gender`)
   - Normalized feature values
   - Split dataset into training (80%) and testing (20%)

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap to understand relationships

3. **Model Selection & Training**
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - XGBoost Classifier

4. **Model Evaluation**
   - Accuracy & AUC
   - Confusion Matrices
   - Classification Reports
   - Feature Importance for tree-based models

## 📊 Results
| Model                | Accuracy | AUC  |
|----------------------|----------|------|
| Logistic Regression | 68.2%    | 68.0% |
| Decision Tree       | 70.5%    | 70.3% |
| Random Forest       | 76.4%    | 76.2% |
| XGBoost            | 78.2%    | 78.0% |

**Best Model:** XGBoost 🏆

## 📌 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gender-classification-dentistry.git
   ```
2. Navigate to the project directory:
   ```bash
   cd gender-classification-dentistry
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python script.

## 🔥 Future Improvements
- Hyperparameter tuning for better accuracy
- Additional feature engineering
- Use of deep learning models

## 👥 Contributors
- Your Name
- Collaborators (if any)

## 📝 License
This project is licensed under the MIT License.


---

# 🩺 Diabetes Risk Prediction

This project is a **machine learning pipeline** to predict diabetes risk based on health-related attributes from a dataset.  
The workflow includes **data preprocessing, visualization, feature engineering, model training, and evaluation**.

---

## 📂 Project Structure

- **Data Exploration & Cleaning**
  - Load dataset and handle missing values
  - Remove unnecessary columns
  - Check for duplicated data
  - Data visualization (count plots, histograms, KDE, heatmaps)
- **Feature Engineering**
  - Create new target variable (`Diabetes`) based on fasting blood glucose level
  - Generate `BMI_Range` category based on BMI values
- **Data Preprocessing**
  - Standard scaling for numeric features
  - One-hot encoding for nominal categorical features
  - Ordinal encoding for ordered categorical features
- **Model Training**
  - Split dataset into Train, Validation, and Test sets
  - Apply:
    - Logistic Regression
    - Random Forest Classifier
- **Model Evaluation**
  - Classification report (accuracy, precision, recall, F1-score)
  - Confusion matrix visualization

---

## 📊 Dataset Details

The dataset includes:
- Demographic information (Age, Sex, Ethnicity)
- Health metrics (BMI, Waist Circumference, Blood Pressure, Cholesterol, etc.)
- Lifestyle choices (Smoking Status, Alcohol Consumption, Physical Activity Level)
- Medical history (Family history of diabetes, Previous gestational diabetes)

✅ Target variable: **Diabetes** (0: Non-diabetic, 1: Diabetic)

---

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (for preprocessing, modeling, evaluation)

---

## 🛠 How to Run

1. Clone the repository or download the `.ipynb` file.
2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook using Jupyter:
   ```bash
   jupyter notebook diabetes_prediction.ipynb
   ```
4. Run all cells sequentially.

---

## 📈 Results

Both **Logistic Regression** and **Random Forest** models are evaluated.  
Metrics such as **precision, recall, F1-score**, and the **confusion matrix** are used to assess model performance.

---

## ✍️ Author

**ABHILASHA**  
[[LinkedIn Profile](https://www.linkedin.com/in/abhilasha-bhatt3/)] 

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---


# 🏡 Airbnb Price Prediction – Random Forest Regression

This project was developed as part of **Lab 8: Define and Solve an ML Problem** in the Break Through Tech AI / eCornell Machine Learning Certificate. It follows the full ML lifecycle, from problem definition and data preparation to modeling, evaluation, and hyperparameter tuning using the **Airbnb NYC Listings** dataset to predict Airbnb listing prices.

---

## 📊 Problem Statement

**Objective**: Predict the `price` of an Airbnb listing based on host and listing features.  
**ML Task**: Supervised Regression  
**Target Variable**: `price`  
**Impact**: Helping Airbnb hosts set fair, competitive prices that maximize revenue while improving user satisfaction and booking conversion rates.

---

## 📁 Dataset

- Dataset: `airbnbListingsData.csv` (NYC listings with host and listing metadata)
- Size: 28,000+ rows × 50 columns
- Features include:
  - Host responsiveness and verification
  - Room type and accommodation details
  - Review scores and availability
  - Categorical fields like room type and borough

---

## 🛠️ Technologies Used

- **Language**: Python  
- **Libraries**: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`  
- **Model**: `RandomForestRegressor`  
- **Workflow**:
  - Data Cleaning & EDA  
  - Feature Engineering (one-hot encoding, removing high-cardinality text)  
  - Train/Test split + Cross-validation  
  - Model tuning with `GridSearchCV`  

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/your-username/airbnb-price-predictor.git
cd airbnb-price-predictor
pip install -r requirements.txt
Launch the notebook:

```
Copy
Edit
```bash
jupyter notebook Lab8_AirbnbPricePrediction.ipynb
```
Make sure the file airbnbListingsData.csv is located in a data/ folder within your project directory.


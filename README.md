
# 🏡 House Price Prediction using Machine Learning

Predicting house prices based on various housing features using regression models, ensemble learning techniques, and meta-modeling strategies. This project was developed in two phases during the final year of B.Tech in AI & ML and aims to help beginners learn end-to-end machine learning workflows with real-world data.

## 📌 Table of Contents
- [About the Project](https://github.com/yashwantpandey/House-Price-Prediction#-about-the-project)
- [Project Phases](https://github.com/yashwantpandey/House-Price-Prediction?tab=readme-ov-file#-project-phases)
- [Tech Stack](https://github.com/yashwantpandey/House-Price-Prediction?tab=readme-ov-file#%EF%B8%8F-tech-stack)
- [Features Used](https://github.com/yashwantpandey/House-Price-Prediction?tab=readme-ov-file#-features-used)
- [Modeling Workflow](https://github.com/yashwantpandey/House-Price-Prediction?tab=readme-ov-file#-modeling-workflow)
- [Results](https://github.com/yashwantpandey/House-Price-Prediction?tab=readme-ov-file#-results)
- [How to Run](https://github.com/yashwantpandey/House-Price-Prediction?tab=readme-ov-file#%EF%B8%8F-how-to-run)
- [Folder Structure](https://github.com/yashwantpandey/House-Price-Prediction?tab=readme-ov-file#-folder-structure)
- [Contributing](https://github.com/yashwantpandey/House-Price-Prediction?tab=readme-ov-file#-contributing)
- [Contact](https://github.com/yashwantpandey/House-Price-Prediction?tab=readme-ov-file#-contact)

## 📖 About the Project
This project predicts median house prices in Boston based on various features such as the number of rooms, crime rate, and distance to employment centers. It uses multiple regression models including **Random Forest**, **Gradient Boosting**, and **XGBoost**, and combines them using **Stacking Ensemble Techniques** with meta-models like Ridge and Extra Trees Regressor. Also, combines them using **Weighted Ensemble Learning Techniques**.

## 🧠 Project Phases

### 🔹 Phase 1: Individual Models
- Applied EDA, outlier handling, and feature selection.
- Implemented and evaluated Random Forest, Linear Regression, SVM, Gradient Boosting, and XGBoost.

### 🔹 Phase 2: Ensemble & Optimization
- Built stacking models with different meta-models.
- Also, built models by combining different algorithms using Weighted Ensemble Learning.
- Compared results against base papers to validate improvements.

## ⚙️ Tech Stack
- **Programming Language:** Python
- **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, XGBoost, LightGBM
- **Techniques:** Regression, Ensemble Learning (Stacking & Weighted Ensemble Learning)
- **Model Evaluation:** MAE, RMSE, R² Score

## 🧾 Features Used

| Feature   | Description                                |
|-----------|--------------------------------------------|
| RM        | Number of rooms per dwelling               |
| LSTAT     | % lower status population                  |
| CRIM      | Crime rate per capita                      |
| DIS       | Distance to employment centers             |
| TAX       | Property tax rate                          |
| NOX       | Nitric oxide concentration                 |
| PTRATIO   | Pupil-teacher ratio                        |
| INDUS     | Proportion of non-retail business acres    |

## 📊 Modeling Workflow

1. **Data Preprocessing**
   - Outlier capping using IQR method
   - MinMax scaling
   - Log transformation for skewed features

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots
   - Correlation heatmaps
   - Scatter and box plots

3. **Modeling**
   - Train/test split (80/20)
   - Individual models trained and tuned
   - Ensemble learning via stacking 
   - Meta-model: Ridge, LGBM, Extra Trees, SVR
   - Also, With Weighted Ensemble Learning

4. **Evaluation**
   - Used MAE, MSE, RMSE, and R² for comparison
   - Stacking with Ridge meta-model (RF + GBR) achieved highest R²: **0.927**

## ✅ Results

| Model                    | MAE   | RMSE  | R²     |
|-------------------------|-------|-------|--------|
| Random Forest           | 1.90  | 2.62  | 0.8592 |
| Gradient Boosting       | 1.84  | 2.46  | 0.8761 |
| XGBoost                 | 1.90  | 2.55  | 0.8664 |
| Extra Trees             | 1.76  | 2.52  | 0.8693 |
| **Stacking (Ridge Meta) - Ensemble method (RF + GBR)** | 1.62  | 2.24  | 0.9270 |

## ▶️ How to Run

1. **Clone the repository**
```bash
git clone https://github.com/yashwantpandey/House-Price-Prediction
cd house-price-prediction-ml
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the notebook**
```bash
jupyter notebook House_Price_Prediction.ipynb
```

## 🤝 Contributing

Beginner-friendly contributions are welcome!

1. Fork this repository  
2. Create a new branch (`git checkout -b feature-name`)  
3. Commit your changes (`git commit -m 'Add new feature'`)  
4. Push to the branch (`git push origin feature-name`)  
5. Open a Pull Request  


## 📬 Contact

**Project Contributors:**  
- Yashwant Pandey | Prateek Mudaliar | Utkarsh Gupta | Ethiya Firdouse – Final Year B.Tech, AI & ML  
- [LinkedIn - Yashwant](https://linkedin.com/in/yashwantpandey) | [LinkedIn - Prateek](https://linkedin.com/in/prateek-mudaliar-176741245) | [LinkedIn - Utkarsh](https://linkedin.com/in/utkarshgupta2502) | [LinkedIn - Ethiya](https://linkedin.com/in/ethiya-firdouse-36577b245)
- [GitHub - Yashwant](https://github.com/yashwantpandey) | [GitHub - Prateek](https://github.com/prateekMudaliar) | [GitHub - Utkarsh](https://github.com/) | [GitHub - Ethiya](https://github.com/)

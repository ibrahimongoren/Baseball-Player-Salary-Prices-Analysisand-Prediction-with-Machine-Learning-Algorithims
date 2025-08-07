## 📌 Project Overview

This project presents a complete machine learning workflow to **predict the salaries of professional baseball players** based on performance, experience, and league-level metrics.

Using advanced regression models and hyperparameter optimization techniques, we aim to create robust and interpretable models for player valuation.

> 🧠 Focus: Data science for sports analytics with real-world applications.

---

## 📊 Dataset

- 📂 **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/creepycrap/baseball-player-salary-prediction)
- 🎯 **Target**: `Salary`
- 🧾 **Features**: Batting stats, player experience, league details, career totals

### 🔧 Engineered Features
- `BattingAverage`
- `CareerBattingAvg`
- `ExperienceLevel` (Binned)

---

## 🛠️ Workflow Summary

| Step | Description |
|------|-------------|
| 🔍 EDA | Missing value handling, outliers, distributions |
| 🧪 Feature Engineering | Custom metrics, binning, encoding |
| ⚙️ Preprocessing | One-hot encoding, scaling |
| 🤖 Modeling | Linear, Ridge, Lasso, ElasticNet, XGBoost, LightGBM, CatBoost |
| 🔁 Hyperparameter Tuning | RandomizedSearchCV & Optuna |
| 🧬 Ensembling | Voting and Stacking Regressors |
| 📉 Evaluation | R², RMSE, MAE + visualizations |

---

## 🤖 Models Implemented

| Model                    | Type                          |
|--------------------------|-------------------------------|
| Linear Regression        | Baseline                     |
| Ridge / Lasso / ElasticNet | Regularized Linear Models  |
| Random Forest            | Bagging-based Ensemble       |
| XGBoost / LightGBM       | Gradient Boosting Models     |
| CatBoost                 | Boosting with Categorical Support |
| Voting / Stacking        | Ensemble Meta-Learning       |

> ✅ **Best Performance**: CatBoost on test set based on R² score.

---

## 📈 Evaluation Metrics

- **R²**: Coefficient of Determination  
- **RMSE**: Root Mean Squared Error  
- **MAE**: Mean Absolute Error  
- Residual and prediction comparison plots included.

---

## 📍 Try It Yourself

You can run the full notebook on Kaggle:

🔗 **[Kaggle Notebook](https://www.kaggle.com/code/ibrahimongoren/baseball-player-salary-analysis-and-prediction)**

---

## 💼 Author

**İbrahim Ongören**  
📧 ongorenibrahim78@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/ibrahimongoren)

---

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## 📌 Acknowledgements

- Kaggle dataset contributor [creepycrap](https://www.kaggle.com/datasets/creepycrap/)
- Open-source Python community  
- ML libraries: `Scikit-Learn`, `XGBoost`, `LightGBM`, `CatBoost`, `Optuna`

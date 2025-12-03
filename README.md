# ML in Rainfed Wheat: Seed Priming Effects

*A machine learning approach to investigate the impact of seed priming on rainfed wheat performance.*

---

## Project Overview

This project uses **machine learning (ML)** to analyze the effects of **seed priming treatments** on the performance of **rainfed wheat**. Rainfed wheat grows under **limited water conditions**, and seed priming can improve **germination, growth, and yield**. The goal of this project is to predict wheat yield and identify which factors most influence crop performance using ML techniques.

---

## Dataset

* Source: [Kaggle Notebook – Rainfed Wheat](https://www.kaggle.com/code/bardiatalebian/ml-in-rainfed-wheat-seed-priming-effects)
* Contains experimental data on wheat under different **seed priming treatments**.
* **Features may include:**

  * Seed priming method (hydropriming, chemical priming, nutrient priming, etc.)
  * Environmental conditions (rainfall, temperature, soil moisture)
  * Soil properties (texture, nutrients)
  * Plant growth traits (germination rate, plant height, biomass)
* **Target Variables:**

  * Wheat yield
  * Yield components (grain weight, grain number, etc.)

---

## Technical Details

* **Programming Language:** Python
* **Key Libraries:**

  * `pandas`, `numpy` – data manipulation
  * `matplotlib`, `seaborn` – visualization
  * `scikit-learn` – regression models and preprocessing
  * `xgboost` – gradient boosting model
  * `scipy` – statistical analysis
* **Machine Learning Workflow:**

  1. **Data Preprocessing:** Cleaning, missing value handling, categorical encoding, scaling.
  2. **Exploratory Data Analysis (EDA):** Visualizing the relationship between seed priming and wheat traits.
  3. **Model Training:** Regression models to predict yield (Linear Regression, Random Forest, XGBoost).
  4. **Model Evaluation:** Metrics like RMSE, MAE, and R² to assess performance.
  5. **Feature Importance Analysis:** Identify key factors affecting yield and growth.

---

## Results

* ML models successfully predict **yield and agronomic traits** under rainfed conditions.
* Feature importance analysis highlights **critical factors** that influence wheat performance.
* Insights can help optimize **seed priming strategies** for farmers in water-limited environments.

---

## Usage

1. Clone the repository:

   ```bash
   git clone <repo-url>
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:

   ```bash
   jupyter notebook ML_in_Rainfed_Wheat.ipynb
   ```

## References

* Kaggle Notebook: [ML in Rainfed Wheat: Seed Priming Effects](https://www.kaggle.com/code/bardiatalebian/ml-in-rainfed-wheat-seed-priming-effects)
* Seed Priming Techniques in Wheat: [ScienceDirect](https://www.sciencedirect.com/topics/agricultural-and-biological-sciences/seed-priming)


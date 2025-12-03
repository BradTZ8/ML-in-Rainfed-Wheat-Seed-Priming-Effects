# ML in Rainfed Wheat: Seed Priming Effects

*A machine learning approach to investigate the impact of seed priming on rainfed wheat performance.*

---

## Project Overview

This project applies **machine learning (ML)** to study the effects of **seed priming treatments** on **rainfed wheat** performance. Seed priming is a pre-sowing treatment that improves **germination, growth, and yield** under water-limited conditions. The aim is to predict wheat yield and growth traits and identify **key factors influencing crop performance**.

---

## Crop Monitoring and Growth Parameters

The following parameters were measured to evaluate wheat performance:

* **Spike Emergence:** Days from sowing to 50% spike appearance from the flag leaf sheath (Liu et al., 2022).
* **Plant Height:** Measured at physiological maturity from soil surface to spike tip, averaged over 10 plants per plot (Zhang et al., 2023).
* **Spike Density per m²:** Number of spikes counted within 1 m² at peak heading (Wen et al., 2022).
* **Number of Seeds per Spike:** Average seeds counted per randomly selected mature spikes (Chu et al., 2023).
* **Thousand-Seed Weight (TSW):** Weight of 1,000 cleaned, dried seeds in grams (Milivojević et al., 2022).
* **Seed Yield:** Harvested, cleaned, and dried grains extrapolated to kg/ha (Anbes & Asredie, 2025).
* **Biological Yield:** Total above-ground biomass harvested and dried for yield estimation (Lamlom et al., 2023).
* **Protein Percentage and Yield:** Grain protein measured by Kjeldahl method; protein yield = protein % × seed yield (Yan et al., 2022).
* **Harvest Index (HI):** Ratio of economic yield (grain) to total biomass, expressed as a percentage:
---

## Dataset

* Source: [Kaggle Notebook – Rainfed Wheat](https://www.kaggle.com/code/bardiatalebian/ml-in-rainfed-wheat-seed-priming-effects)
* Features include seed priming type, environmental factors (rainfall, temperature, soil moisture), soil properties, and plant growth traits.
* Target variables: Wheat yield, yield components, and protein yield.

---

## Data Modeling

* **Algorithms Used:**

  * Linear models: Linear Regression (LR), Ridge, Lasso, ElasticNet
  * Tree-based ensembles: Random Forest (RF)
  * Boosting: CatBoost (CB), Extreme Gradient Boosting (XGB)
  * Support Vector Regression (SVR)
* **Workflow:**

  1. Data preprocessing: Missing values, encoding, scaling
  2. Exploratory Data Analysis (EDA)
  3. Model training using 50% train / 50% test split
  4. 5-fold cross-validation applied for all models
  5. Performance evaluation using **Root Mean Square Percentage Error (RMSPE)** and **R²**
  6. 
* **Software:** Python with `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `catboost`, `scipy`.

---

## Results

* ML models successfully predicted **yield and agronomic traits** under rainfed conditions.
* Feature importance analysis identified **key factors influencing crop performance**, helping optimize seed priming strategies.
* RMSPE allowed **relative error assessment**, making model performance easier to interpret than standard RMSE.

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

---

## References

* Kaggle Notebook: [ML in Rainfed Wheat](https://www.kaggle.com/code/bardiatalebian/ml-in-rainfed-wheat-seed-priming-effects)



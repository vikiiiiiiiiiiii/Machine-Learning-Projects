# 🚀 Core Machine Learning & Deep Learning Portfolio

Welcome to my central machine learning project repository. This portfolio demonstrates production-ready implementations across the major pillars of modern data science: Supervised Regression, Sequential Deep Learning (Time-Series), and Unsupervised Clustering.

## 📂 Core Projects Included:

### 1. 🏠 House Price Valuation Model (Supervised Regression)
* **Objective:** Predict real estate market values based on physical and structural independent variables.
* **Architecture:** Structured a clean feature-to-target mapping matrix ($X$ and $y$), utilized custom data segregation for model training, and fitted a baseline `LinearRegression` algorithm.
* **Evaluation:** Evaluated model residuals by plotting an Actual vs. Predicted scatter matrix, achieving a stable baseline $R^2$ accuracy score of **79.3%**.

### 2. 💎 Diamond Price Prediction Pipeline (Advanced Regression)
* **Objective:** Automate inventory asset valuation based on raw categorical and numerical metrics.
* **Architecture:** Constructed an end-to-end `Scikit-Learn Pipeline` using a `ColumnTransformer` to route numerical data through a `StandardScaler` and text properties through a `OneHotEncoder` directly into a `RandomForestRegressor`.
* **Validation:** Achieved a highly stable **98.9% Mean Cross-Validation $R^2$ Score**, completely eliminating data leakage.

### 3. 📈 Bitcoin Trend Forecasting (Sequential Deep Learning)
* **Objective:** Capture temporal dependencies and historic trends in highly volatile financial time-series data.
* **Architecture:** Designed a Deep Recurrent Neural Network built with stacked **LSTM layers** utilizing a sliding 10-day lookback window. Normalized features with a bounded `MinMaxScaler` and regularized via `Dropout` layers to prevent neural path overfitting.
* **Evaluation:** Monitored network convergence utilizing automated Mean Squared Error loss mapping across training epochs.

### 4. 🌍 Global Development Profiling (Unsupervised Clustering)
* **Objective:** Segment socioeconomic country data into distinct development tiers without predefined labels.
* **Architecture:** Implemented a spatial distance-based **K-Means Clustering** engine optimized via smart centroid initialization (`k-means++`). Scaled metrics with `StandardScaler` to prevent feature scale dominance.
* **Evaluation:** Mathematically isolated 3 distinct country clusters (Low, Medium, High) verified through statistical group profiling (`groupby().mean()`).

---
💡 *Note: All scripts are fully functional, verified, and ready for live execution. Click the notebook files above to view the code cells and visual convergence graphs.*

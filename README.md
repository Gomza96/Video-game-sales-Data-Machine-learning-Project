# Video-game-sales-Data-Machine-learning-Project
### 1. **Data Preprocessing**
- Handled missing values using mean for numerical columns and mode for categorical columns.
- Normalized sales data to reduce skewness.
- Encoded categorical variables using Label Encoding.

### 2. **Prediction using Random Forest Regressor**
- **Polynomial Features**: Transformed sales features to create a more complex relationship for prediction.
- **Model Training**: Trained a Random Forest Regressor to predict `Global_Sales` using regional sales (`NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`).
- **Evaluation**: 
  - R² Score (Training): `0.9968`
  - R² Score (Testing): `0.9959`

### 3. **Clustering with KMeans**
- Used KMeans clustering to group video games based on sales data.
- Determined optimal number of clusters using the **Elbow Method**.

### 4. **Visualization with PCA**
- Applied PCA to reduce dimensions for cluster visualization.
- Plotted clusters to explore patterns and relationships.

---

## Key Results

1. **Prediction**:
   - The Random Forest Regressor achieved high accuracy with minimal overfitting due to the use of cross-validation and polynomial feature engineering.

2. **Clustering**:
   - Identified distinct clusters of video games based on sales data, revealing market segments and regional trends.

3. **Insights**:
   - NA and EU sales contribute significantly to global sales.
   - Certain platforms and genres dominate specific regions.

---

## Technologies Used

- **Python**: Primary programming language.
- **Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical computations.
  - `matplotlib` and `seaborn` for visualization.
  - `scikit-learn` for machine learning.
  - `PCA` for dimensionality reduction.
  - `KMeans` for clustering.

---

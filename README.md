# HomoCodeus-Cracking-the-Evolutionary-Code
Biological Data Of Human Evolution Data Sets

# HomoCodeus: Cracking the Evolutionary Code

## Overview
**HomoCodeus** is a Python-based machine learning project designed to explore a comprehensive dataset of hominid traits. The project analyzes evolutionary trends through supervised and unsupervised machine learning techniques, including regression models, clustering, and dimensionality reduction.

## Features
- **Regression Analysis**: Predict cranial capacity based on other attributes.
- **Clustering**: Group hominid species by shared traits using K-Means.
- **Dimensionality Reduction**: Visualize high-dimensional data in 2D space using PCA and t-SNE.

## Dataset
The dataset, `Homininos_DataSet.csv`, includes detailed information on hominid species, such as:
- **Cranial Capacity**
- **Height**
- **Jaw Shape**
- **Habitat**
- And more...

### Prerequisites
- Python 3.7+
- Libraries: `pandas`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`

Install dependencies via:
```bash
pip install pandas scikit-learn xgboost matplotlib seaborn
```

## Project Structure
```
.
├── Homininos_DataSet.csv      # Input dataset
├── HomoCodeus.py             # Main script
├── README.md                 # Project documentation
```

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```
2. Place the dataset `Homininos_DataSet.csv` in the project directory.
3. Run the Python script:
   ```bash
   python HomoCodeus.py
   ```
4. Visualizations and results will be displayed.

## Machine Learning Models
### Supervised Learning: Regression
- **Objective**: Predict cranial capacity based on attributes like height, jaw shape, and habitat.
- **Models**: 
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor

### Unsupervised Learning
#### Clustering
- **Objective**: Group hominid species by shared traits.
- **Model**: K-Means Clustering

#### Dimensionality Reduction
- **Objective**: Visualize high-dimensional data in 2D.
- **Models**:
  - Principal Component Analysis (PCA)
  - t-Distributed Stochastic Neighbor Embedding (t-SNE)

## Results
### Regression Performance
- **Linear Regression**:
  - RMSE: ~42.35
  - R²: ~0.98
- **Random Forest**:
  - RMSE: ~50.31
  - R²: ~0.97
- **XGBoost**:
  - RMSE: ~52.58
  - R²: ~0.97

### Clustering
- Visualized clusters using cranial capacity and height.

### Dimensionality Reduction
- Visualized traits in 2D using PCA and t-SNE.

## Visualizations
- Scatter plots for clustering.
- PCA and t-SNE visualizations for reduced dimensions.

## Future Improvements
- Address class imbalance in classification tasks.
- Experiment with advanced clustering techniques (e.g., DBSCAN).
- Enhance interpretability with SHAP or LIME.

## License
This project is licensed under the MIT License.

## Acknowledgments
- **Dataset**: Compiled by Biological Anthropology researchers.
- **Libraries**: Powered by Python's rich ML ecosystem.

---
Happy coding with **HomoCodeus**! 🌟

# Anomaly Detection using Unsupervised Learning

An unsupervised machine-learning project exploring anomaly detection with clustering and isolation-based methods.

## Objective

The project studies how unusual observations can be identified when labelled anomaly data is not available.

## Methods Explored

### DBSCAN

DBSCAN groups points based on density and naturally identifies points that do not belong to dense clusters.

### Isolation Forest

Isolation Forest identifies anomalies by measuring how easily observations can be isolated from the rest of the data.

The notebook also uses PCA for dimensionality reduction and visualization.

## Data

The repository includes:

```text
thyroid.csv
```

The notebook also demonstrates DBSCAN on a synthetic two-moons dataset.

## Workflow

```text
Raw Data
   ↓
Preprocessing
   ↓
Scaling
   ↓
Anomaly Detection
   ├── DBSCAN
   └── Isolation Forest
   ↓
Visualization / Analysis
```

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Getting Started

```bash
git clone https://github.com/muskanmundra18-lab/Anomaly-Detection.git
cd Anomaly-Detection
```

Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Open:

```text
anomaly_detection.ipynb
```

## Learning Outcomes

- Understanding unsupervised anomaly detection
- Density-based clustering with DBSCAN
- Isolation Forest
- Feature scaling
- PCA-based visualization
- Comparing different approaches to detecting unusual observations

## Future Improvements

- Add quantitative anomaly-detection metrics
- Compare additional methods such as One-Class SVM and LOF
- Add an interactive anomaly dashboard
- Investigate threshold selection
- Evaluate methods on domain-specific labelled data

## Author

**Muskan Mundra**

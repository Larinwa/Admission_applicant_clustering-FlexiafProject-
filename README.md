# Applicants Clustering for Program Targeting
This project displays an unsupervised clustering of 400 graduate school applicants to enable targeted outreach strategies.

## Dataset
- **Source:** [Kaggle - Graduate Admissions](https://www.kaggle.com/datasets/mohansacharya/graduate-admissions)
- **Size:** 400 applicants × 7 features
- **Cleaning:** Standardized column names (removed spaces), normalized features with StandardScaler

## Method
- K-Means clustering (k=2)
- PCA for dimensionality reduction and visualization
- Silhouette analysis for cluster validation

## Results
| Cluster | Size | Profile | Strategy |
|---------|------|---------|----------|
| 0 | 44% | Standard applicants | Support pathway, prep resources |
| 1 | 56% | High achievers | Fast-track, scholarship offers |

## Files
| File | Description |
|------|-------------|
| `applicant_clusters.csv` | Full dataset with cluster labels |
| `cluster_profiles.csv` | Cluster summary statistics |
| `clustering_dashboard.png` | 6-panel visualization |
| `notebook.ipynb` | Complete analysis code |

## Links
- **Notebook:** [Colab](https://colab.research.google.com/drive/1k_EYPubMWjEjgcjW8TNUnBcoKYZBa_-z?usp=sharing)
- **Slides:** [PDF Summary]([(https://canva.link/iu61iucswbzu0yl)

## Key Insight
Model successfully segments applicants into distinct groups with different admission probabilities, enabling data-driven resource allocation for admissions teams.

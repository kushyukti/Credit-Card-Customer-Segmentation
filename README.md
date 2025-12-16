# Credit-Card-Customer-Segmentation

Data is of various customers of a bank with their credit limit, the total number of credit cards the customer has, and different channels through which customer has contacted the bank for any queries, different channels include visiting the bank, online and through a call centre.

## Dataset
- Contains 660 customer records
- Key features: Average Credit Limit, Total Credit Cards, Total Visits to Bank, Total Visits Online, Total Calls Made
- Data loaded from Kaggle dataset https://www.kaggle.com/datasets/rupindersinghrana/credit-card-customer-segmentation/data

## Analysis Steps
- Imports libraries like Pandas, Scikit-learn, Matplotlib, Seaborn
- Loads and explores data with head(), shape(), info()
- Creates histograms for feature distributions
- Selects relevant columns for clustering

## Clustering Methods
- **K-Means**: Optimal k=3 using Elbow Method; Silhouette Score: 0.516 
- **Hierarchical**: Dendrogram shows 3 clusters; Silhouette Score: 0.503

## Key Results
Both methods identify 3 customer groups (G1, G2, G3):

| Group | Avg Credit Limit | Total Cards | Bank Visits | Online Visits | Calls Made |
|-------|------------------|-------------|-------------|---------------|------------|
| G1    | 33,782           | 6           | 3           | 1             | 2          |
| G2    | 12,174           | 2           | 1           | 4             | 7          |
| G3    | 141,040          | 9           | 1           | 11            | 1          |

## Business Insights
- G3: High-value customers (high limit/cards, online-focused)
- G1: Active multi-channel customers
- G2: Low-value, call-heavy customers 


## 🛠️ Technologies & Libraries
✅ Python 3.11
✅ Pandas (Data manipulation)
✅ Scikit-learn (K-Means, StandardScaler)
✅ Seaborn/Matplotlib (Visualizations)
✅ SciPy (Hierarchical clustering)
✅ Jupyter Notebook

## Technologies Used
- Python 3, Pandas, Scikit-learn, Matplotlib, Seaborn [file:1]

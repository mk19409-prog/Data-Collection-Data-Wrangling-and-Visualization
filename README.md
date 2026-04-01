# Data-Collection-Data-Wrangling-and-Visualization
This repository contains the Milestone 2 deliverables for **CSCI-7090: Data Science & Machine Learning** (Spring 2026), focused on **Data Collection, Wrangling, and Visualization**. This milestone builds on our literature review (Milestone 1) and prepares the dataset for predictive modeling in Milestone 3.  


# Team 10 – CSCI-7090: Data Collection, Wrangling, and Visualization (Milestone 2)


The primary goal of this milestone is to demonstrate the ability to:  
- Acquire and document a real-world dataset relevant to our research topic.  
- Clean, preprocess, and engineer features to produce an analysis-ready dataset.  
- Explore and visualize the data to uncover patterns, relationships, and insights.  

---

## Repository Structure

Team10-Milestone2/
│
├─ data/
│ ├─ raw/ #raw dataset
│ └─ cleaned/ # Cleaned dataset ready for analysis (CSV)
│
├─ notebooks/
│ └─ Milestone2.ipynb # Jupyter Notebook with complete data pipeline, wrangling, EDA, and visualizations
│
├─ visuals/
│ └─ figures/ # Exported figures and plots from EDA
│
├─ README.md # Project overview and instructions
└─ references.md # Sources, dataset links, and citations



---

## Dataset Description

- **Source:** [Insert dataset source, e.g., Kaggle, UCI ML Repository, government portal, API, or web scraping link]  
- **Access Date:** [MM/DD/YYYY]  
- **Number of Records:** [e.g., 10,000 rows]  
- **Number of Features:** [e.g., 15 columns]  
- **Target Variable:** [If applicable, specify the target]  

### Data Dictionary
| Feature Name | Data Type | Description | Example Values |
|--------------|-----------|-------------|----------------|
| feature_1    | int       | Description | 123            |
| feature_2    | float     | Description | 45.67          |
| ...          | ...       | ...         | ...            |

### Relevance Statement
*This dataset is directly relevant to our literature review topic on [insert topic]. It provides [describe types of data], which allows us to [describe what analysis or insights are enabled]. The dataset is appropriate for predictive modeling due to [state justification, e.g., variety of features, numerical and categorical types, sufficient sample size].*

---

## Data Wrangling and Preprocessing

The dataset was cleaned and prepared for analysis through the following steps:  

1. **Missing Value Analysis:** Identified missing values and applied appropriate imputation strategies (mean/median/mode imputation, forward/backward fill, or deletion).  
2. **Data Type Conversion:** Ensured correct types, converted date strings to datetime, and encoded categorical variables (label encoding or one-hot encoding).  
3. **Outlier Detection and Treatment:** Detected outliers using IQR and Z-score methods; treated them by removal or capping with justification.  
4. **Feature Engineering:** Created new features such as [feature examples] to enhance model performance.  
5. **Normalization/Scaling:** Applied [StandardScaler / MinMaxScaler / RobustScaler] to numerical features for consistent range and distribution.  
6. **Final Dataset Summary:** Compared dataset shape, missing values, and descriptive statistics before and after wrangling.

---

## Exploratory Data Analysis (EDA) & Visualizations

Visualizations were created to uncover patterns, relationships, and trends:  

- **Distribution Plots:** Histograms/KDE plots for key numerical features.  
- **Correlation Heatmap:** Highlighting relationships between features.  
- **Categorical Analysis:** Bar charts, count plots, and pie charts for categorical variables.  
- **Feature Relationships:** Scatter plots or pair plots for interactions and target variable relationships.  
- **Time Series / Specialized Plots:** Trend visualizations, geographic plots, or alternative visualizations appropriate to the dataset.  

All visualizations are publication-quality with clear titles, labeled axes, consistent color schemes, and interpretation text accompanying each figure.

---


🛠 How to Compile Locally (LaTeX)


Step 1: Install LaTeX
Install one of the following distributions:
- Windows → MiKTeX
- Mac → MacTeX
- Linux → TeX Live

Step 2: Clone the Repository
git clone <repository-link>
cd <repository-folder>

Step 3: Compile the Document
- pdflatex main.tex
- bibtex main
- pdflatex main.tex
- pdflatex main.tex



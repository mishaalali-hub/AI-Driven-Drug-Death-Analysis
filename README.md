# AI-Driven-Drug-Death-Analysis

An end-to-end Data Mining and Machine Learning project focused on analyzing accidental drug-related deaths using preprocessing, exploratory data analysis (EDA), classification, clustering, and predictive modelling techniques.

This project was developed as part of a university group assignment for the Data Mining course.

---

# Project Overview

The main objective of this project is to:

- Clean and preprocess real-world healthcare-related data
- Perform exploratory data analysis (EDA)
- Apply machine learning classification models
- Perform clustering analysis for pattern discovery
- Evaluate model performance using multiple metrics
- Generate meaningful insights from accidental drug-related death records

The dataset used contains accidental drug-related death records collected from public healthcare sources.

---

# Dataset

Dataset Used:
- Accidental Drug Related Deaths Dataset

Source:
- Connecticut Open Data Portal

Dataset File:
- `Accidental_Drug_Related_Deaths_CLEANED_V2.csv`

---

# Technologies Used

## Programming Language
- Python

## Libraries & Frameworks
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

---

# Project Structure

```bash
AI-Driven-Drug-Death-Analysis/
│
├── Accidental_Drug_Related_Deaths_CLEANED_V2.csv
├── Classification_and_Clustering_Codes.ipynb
├── Preprocesing_Codes.ipynb
├── README.md
```

---

# Features Implemented

## 1. Data Preprocessing

The preprocessing notebook includes:

- Missing value identification and analysis
- Median imputation for numerical features
- Dataset structure inspection
- Duplicate checking
- Feature cleaning and transformation
- Encoding categorical variables
- Data consistency validation
- Statistical summaries

---

## 2. Exploratory Data Analysis (EDA)

Performed analyses include:

- Correlation analysis
- Histograms and distributions
- Feature relationship analysis
- Missing value visualization
- Class distribution analysis
- Statistical exploration

---

## 3. Classification Modelling

Implemented workflow:

- Feature selection
- Target variable definition
- Train-test split with stratification
- Decision Tree Classifier training
- Model prediction and evaluation

Evaluation metrics used:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 4. Clustering Analysis

Implemented clustering workflow for:

- Pattern discovery
- Group segmentation
- Behaviour analysis
- Cluster visualization

---

# Algorithms Used

## 1. Decision Tree Classifier

### Why It Was Used

The Decision Tree algorithm was selected because:

- It is easy to interpret and visualize
- Works well with structured tabular datasets
- Handles both numerical and categorical features
- Suitable for classification problems
- Helps identify important decision-making patterns in the dataset

### How It Works

Decision Tree works by:

1. Splitting the dataset into branches based on feature conditions
2. Selecting the best split using impurity measures such as Gini Index or Entropy
3. Repeating the process recursively until predictions can be made
4. Producing a tree-like structure for classification decisions

### Purpose in This Project

The algorithm was used to:

- Predict patterns in drug-related death records
- Analyze relationships between variables
- Perform classification tasks on the processed dataset
- Generate interpretable analytical results

---

## 2. Clustering Algorithm

### Why It Was Used

Clustering was implemented to:

- Discover hidden patterns in the dataset
- Group similar records together
- Identify behavioral or statistical similarities
- Perform unsupervised learning analysis

### How It Works

Clustering algorithms group data points based on similarity by:

1. Measuring distances between data samples
2. Creating clusters with similar characteristics
3. Separating different data patterns into groups

### Purpose in This Project

The clustering process helped:

- Detect natural groupings in drug-related death cases
- Improve data understanding
- Support exploratory pattern analysis

---

## 3. Data Preprocessing Techniques

### Median Imputation

#### Why It Was Used

Median imputation was selected because:

- It handles missing numerical values effectively
- Less sensitive to outliers compared to mean imputation
- Maintains better statistical stability

#### How It Works

Missing numerical values are replaced using the median value of the corresponding feature column.

---

## 4. Train-Test Split

### Why It Was Used

Train-test splitting was necessary to:

- Evaluate model performance fairly
- Prevent overfitting
- Measure prediction capability on unseen data

### How It Works

The dataset was divided into:

- Training dataset for learning
- Testing dataset for evaluation

Stratified splitting was applied to preserve class distribution balance.

---

## 5. Evaluation Metrics

| Metric | Purpose |
|---|---|
| Accuracy | Measures overall prediction correctness |
| Precision | Measures correctness of positive predictions |
| Recall | Measures ability to detect actual positives |
| F1-Score | Balances Precision and Recall |
| Confusion Matrix | Visualizes classification performance |

---

# Included Notebooks

## 1. Preprocesing_Codes.ipynb

This notebook focuses on:

- Data cleaning
- Missing value handling
- Exploratory Data Analysis
- Feature preprocessing
- Dataset preparation

---

## 2. Classification_and_Clustering_Codes.ipynb

This notebook focuses on:

- Machine learning modelling
- Decision Tree Classification
- Classification evaluation
- Clustering analysis
- Predictive analytics

---

# Machine Learning Workflow

```text
Raw Dataset
    ↓
Data Cleaning & Preprocessing
    ↓
Exploratory Data Analysis
    ↓
Feature Selection
    ↓
Train-Test Split
    ↓
Model Training
    ↓
Evaluation & Insights
```

---

# How to Run the Project

## 1. Clone the Repository

```bash
git clone https://github.com/yourusername/AI-Driven-Drug-Death-Analysis.git
cd AI-Driven-Drug-Death-Analysis
```

---

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3. Open Jupyter Notebook

```bash
jupyter notebook
```

---

## 4. Run the Notebooks

Execute:

- `Preprocesing_Codes.ipynb`
- `Classification_and_Clustering_Codes.ipynb`

---

# Results

The project successfully:

- Cleaned and transformed a real-world healthcare dataset
- Identified patterns in drug-related deaths
- Built predictive machine learning models
- Generated meaningful visualizations and analytical insights
- Demonstrated practical applications of Data Mining techniques

---

# Academic Purpose

This repository was developed strictly for:

- Educational purposes
- Academic research and learning
- Data Mining coursework demonstration

---

# Future Improvements

Potential future enhancements include:

- Advanced ensemble models
- Deep learning integration
- Interactive dashboard deployment
- Real-time analytics
- Automated preprocessing pipeline
- Explainable AI (XAI) integration

---

# License

This project is intended for academic and educational purposes only.

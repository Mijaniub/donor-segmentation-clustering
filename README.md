#  Donor Segmentation using Unsupervised Machine Learning

> Identifying meaningful donor profiles through clustering techniques to support data-driven fundraising strategies.

---

##  Overview

This project applies **Unsupervised Machine Learning** techniques to segment donors based on demographic, socioeconomic, and historical donation behavior.

The objective is to discover hidden donor groups that can help nonprofit organizations better understand their supporters and develop more personalized and effective fundraising campaigns.

This project was completed as part of the **Data Science & Machine Learning** course in the **Postgraduate Program in Enterprise Data Science & Analytics** at **NOVA Information Management School (NOVA IMS), Universidade Nova de Lisboa**.

---

##  Business Problem

Many nonprofit organizations send the same fundraising campaigns to every donor, regardless of their interests or donation history. This often results in lower engagement and reduced campaign effectiveness.

Using historical donor data, this project aims to identify distinct donor segments that can support:

- Personalized fundraising campaigns
- Better donor engagement
- Improved resource allocation
- Increased fundraising efficiency
- Data-driven decision making

---

## 📂 Dataset

The dataset contains historical information about potential donors, including:

- Demographic information
- Socioeconomic indicators
- Donation history
- Campaign response behavior
- Income and wealth information
- Home ownership
- STAR donor status
- Recent and lifetime donation statistics

**Examples of features include:**

- Donor Age
- Income Group
- Wealth Rating
- Household Income
- Home Owner Status
- Lifetime Donation Amount
- Lifetime Donation Count
- Recent Average Gift Amount
- Months Since Last Gift
- Recent Response Rate

---

##  Project Workflow

### 1. Data Preprocessing

- Data cleaning
- Handling missing values
- Duplicate checking
- Data transformation
- Feature scaling

---

### 2. Exploratory Data Analysis (EDA)

- Summary statistics
- Distribution analysis
- Correlation analysis
- Outlier detection
- Feature relationship visualization

---

### 3. Feature Engineering

- Encoding categorical variables
- Selecting relevant features
- Data normalization
- Preparing data for clustering

---

### 4. Dimensionality Reduction

Applied **Principal Component Analysis (PCA)** to reduce dimensionality while preserving the majority of data variance.

---

### 5. Clustering

Implemented **K-Means Clustering** to identify meaningful donor groups.

Model evaluation included:

- Elbow Method
- Silhouette Score

---

### 6. Cluster Analysis

Each cluster was analyzed based on:

- Demographics
- Donation behavior
- Wealth indicators
- Engagement level
- Giving patterns

---

### 7. Business Recommendations

Based on the identified donor segments, practical recommendations were proposed to support targeted fundraising campaigns and improve donor communication strategies.

---

#  Technologies Used

| Category | Tools |
|----------|-------|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Dimensionality Reduction | PCA |
| Clustering | K-Means |
| Development Environment | Jupyter Notebook |

---

# 📊 Machine Learning Techniques

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Standardization
- Principal Component Analysis (PCA)
- K-Means Clustering
- Elbow Method
- Silhouette Analysis

---

# 📁 Repository Structure

```
donor-segmentation-clustering/
│
├── data/
│   └── donors_train.csv
│
├── notebooks/
│   └── Uncovering_DONOR_Profiles_Through_Clustering.ipynb
│
├── images/
│   └── (plots and visualizations)
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 📈 Key Outcomes

✅ Cleaned and preprocessed donor data

✅ Performed comprehensive Exploratory Data Analysis (EDA)

✅ Reduced dimensionality using PCA

✅ Identified meaningful donor segments using K-Means Clustering

✅ Evaluated clustering performance using the Elbow Method and Silhouette Score

✅ Generated actionable business insights for targeted fundraising strategies

---

#  Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Unsupervised Machine Learning
- Customer Segmentation
- Clustering Analysis
- Principal Component Analysis
- Data Visualization
- Business Analytics
- Model Evaluation
- Python Programming

---

#  Future Improvements

- Hierarchical Clustering
- DBSCAN
- Gaussian Mixture Models (GMM)
- Interactive Dashboard (Power BI / Tableau)
- Automated Clustering Pipeline
- Predictive Donation Modeling

---

#  Sample Visualizations

This repository includes visualizations such as:

- Data Distribution Plots
- Correlation Heatmap
- PCA Projection
- Elbow Curve
- Silhouette Analysis
- Cluster Scatter Plot
- Cluster Profiling Charts

---

#  Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/donor-segmentation-clustering.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

# 📄 License

This project is released under the MIT License.

---

# 👨‍💻 Author

**MD Mijanul Haque**

🎓 Postgraduate in Enterprise Data Science & Analytics  
🏫 NOVA Information Management School (NOVA IMS)  
📍 Lisbon, Portugal

**LinkedIn:**  
https://www.linkedin.com/in/md-mijanul-haque-165188212/

**GitHub:**  
https://github.com/Mijaniub

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Feedback and suggestions are always welcome!

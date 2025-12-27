⚽ Player Rating Analysis (FIFA Dataset)

This project focuses on analyzing FIFA player ratings using Exploratory Data Analysis (EDA) and basic machine learning techniques to understand player performance, value, and grouping patterns.

The analysis uses visualizations to make insights easy to understand and intuitive.

🎯 Objective

Understand how player ratings are distributed

Analyze relationships between age, value, wage, and overall rating

Identify top-performing clubs

Explore player similarity using clustering and PCA

Apply basic regression and unsupervised learning

📂 Project Structure

Player-Rating-Analysis/
│
├── data/
│ └── players_20.csv
│
├── images/
│ ├── correlation_heatmap.png
│ ├── rating_distribution.png
│ ├── top_clubs.png
│ ├── age_vs_rating.png
│ ├── linear_regression.png
│ ├── kmeans_pca.png
│ ├── pca_2d.png
│ └── pca_3d.png
│
├── Player_Rating_Analysis.ipynb
└── README.md

📊 Dataset Overview

Dataset: FIFA 20 Player Dataset
Source: Kaggle
Records: 18,000+ players

Key Features Used:

Age

Height & Weight

Overall Rating

Potential

Market Value

Wage

📈 Visual Analysis & Insights


Shows relationships between numerical player attributes.


Displays how player ratings are distributed across the dataset.


Compares average player ratings across top football clubs.


Examines how player performance varies with age.


Explores how selected features influence overall player rating.

🤖 Machine Learning Analysis


Clusters players using K-Means after dimensionality reduction.


Reduces high-dimensional data into two principal components.


Visualizes player clusters in three-dimensional PCA space.

🛠 Tools & Technologies

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

🚀 How to Run

git clone https://github.com/mohittharu/EDA-Projects.git

cd Player-Rating-Analysis
jupyter notebook Player_Rating_Analysis.ipynb

🎓 Key Learnings

Practical EDA on real-world sports data

Feature correlation and visualization

Clustering and PCA for player segmentation

Data-driven insights for sports analytics

👤 Author

Mohit Tharu
Data Analytics Enthusiast | Python | EDA | Machine Learning Basics

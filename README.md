Application of Linear Algebra in Control Charts for Process Monitoring

•	Overview

This project investigates the integration of advanced linear algebra techniques with classical control charts (Shewhart, EWMA, CUSUM) to enhance process monitoring and fault detection in multivariate settings. Using the **Steel Plates Faults Dataset**, the project demonstrates the role of Singular Value Decomposition (SVD), quadratic forms, and constrained optimization in improving sensitivity and accuracy when detecting process anomalies.

•	Objective

The primary goal is to combine tools from **advanced linear algebra** with **control charts** for improved monitoring of high-dimensional data, such as in quality control and multichannel data analysis. Key objectives include:
-	Applying **SVD** for dimensionality reduction.
-	Using **quadratic forms** to analyze variance-covariance structures.
-	Designing control charts (Shewhart, EWMA, CUSUM) enhanced with linear algebra techniques.
-	Visualizing and interpreting "out-of-control" signals effectively.

•	Dataset

We use the **Steel Plates Faults Dataset**, available on the UCI Machine Learning Repository. The dataset contains multivariate features that describe various types of faults in steel plates.

-	**Dataset Features:**
-	27 predictor variables.
-	1 target variable representing fault types (7 classes).
-	**Use Case:**
The dataset provides a real-world example of multivariate process monitoring and anomaly detection in quality control.

•	Prerequisites
Before you start, make sure you have the following installed:
-	Python 3.8 or higher
-	Jupyter Notebook (optional for running notebooks)
-	Git

•	Dependencies
•	Install the required Python libraries using:
•	pip install -r requirements.txt
requirements.txt 
•	numpy
•	pandas
•	matplotlib
•	seaborn
•	scipy
•	scikit-learn

Project Structure
plaintext
CopyEdit
├── README.md                  # Project documentation
├── requirements.txt           # Dependencies
├── src/                       # Source code directory
│   ├── preprocessing.py       # Data preprocessing scripts
│   ├── svd_analysis.py        # SVD implementation
│   ├── quadratic_forms.py     # Quadratic forms analysis
│   ├── control_charts.py      # Shewhart, EWMA, CUSUM implementations
│   └── visualization.py       # Visualization tools
├── data/                      # Dataset folder
│   ├── steel_plates_faults.csv
├── reports/                   # Project report in IEEE format
├── results/                   # Generated results and plots
└── notebooks/                 # Jupyter notebooks for experimentation

Usage
1.	Clone the Repository
git clone https://github.com/yourusername/linear-algebra-control-charts.git
cd linear-algebra-control-charts
2.	Run Preprocessing Prepare the dataset by cleaning, normalizing, and representing it as matrices:
python src/preprocessing.py
3.	Apply Linear Algebra Techniques Run SVD or quadratic forms analysis:
python src/svd_analysis.py
python src/quadratic_forms.py
4.	Generate Control Charts Create enhanced Shewhart, EWMA, and CUSUM charts:
python src/control_charts.py
5.	Visualize Results View anomaly detection results and interpret the control charts:
python src/visualization.py

Results
The project explores the following:
•	The effectiveness of SVD in reducing dimensionality while preserving critical features.
•	How quadratic forms enhance control chart sensitivity in detecting fault patterns.
•	Improvements in anomaly detection accuracy by integrating control charts with linear algebra.
References
•	Steel Plates Faults Dataset: UCI Machine Learning Repository
•	Advanced Linear Algebra Techniques: Textbooks and research articles.

Contributors
•	Adina Kamran
Advanced Linear Algebra Student, GIK Institute
Fall 2024 Semester


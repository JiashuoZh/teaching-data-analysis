# Data Analysis with Python — Teaching Portfolio

This repository is part of my **Teaching Portfolio** and is designed for both **instruction** and **research-oriented analysis** using Python.  
It merges overlapping content from two textbooks into a unified, non-redundant structure and integrates **research hooks** relevant to finance and NLP.

> Prerequisite: basic Python programming (see my repository [`teaching-python-programming`](https://github.com/JiashuoZh/teaching-python-programming)).

---

## 🎯 Learning Objectives
- Build an end-to-end pipeline: **ingest → clean → analyze → visualize → baseline modeling**.
- Write **reproducible** notebooks with clear narratives and tidy code.
- Connect methods to **finance/NLP** cases that could evolve into preprints.

---

## 📦 Repository Structure

```text
01_python_basics/              # Minimal setup & notebook conventions (link to fundamentals repo)
02_numpy_pandas/               # NumPy arrays, Pandas Series/DataFrame, indexing, groupby
03_data_cleaning/              # Missing/duplicate/outliers, type/date parsing, joins
04_data_visualization/         # Matplotlib & Seaborn (PyEcharts optional)
05_time_series/                # Timestamp/Period/Timedelta, resampling, rolling windows
06_text_analysis/              # Basic NLP: tokenization, bag-of-words, simple sentiment
07_machine_learning_intro/     # KNN, train/validation split, evaluation metrics
08_advanced_methods/           # Regression/Clustering/Association rules/ARIMA
09_projects/                   # Domain cases: real estate, financial sentiment, stock forecasting

---

🧭 Module Map & Sources
Module	Key Topics	Source Chapters (merged)	Primary Outputs
01 Python Basics	Conda/Anaconda, Jupyter, repo conventions	Both books: Intro/Setup	setup_guide.md (links to teaching-python-programming)
02 NumPy & Pandas	ndarray, Series, DataFrame, indexing, groupby, aggregation	Both: NumPy/Pandas chapters	numpy_basics.ipynb, pandas_core.ipynb
03 Cleaning	Missing/duplicate/outliers, type casting, datetime parsing, joins/merge	Both: Data import/cleaning	cleaning_toolbox.ipynb
04 Visualization	Plot foundations, styles, layouts; Seaborn grammar	Book A: Visualization; Book B: Matplotlib/Seaborn	viz_matplotlib.ipynb, viz_seaborn.ipynb (PyEcharts optional)
05 Time Series	Frequencies, resampling, rolling stats	Both: Time series chapters	timeseries_core.ipynb
06 Text Analysis	Tokenization (jieba/NLTK), term stats, simple sentiment	Both: Text analysis	text_basics_jieba_nltk.ipynb
07 ML Intro	KNN, train_test_split, confusion matrix, precision/recall	A: ML intro; B: ML basics	ml_knn_basics.ipynb
08 Advanced Methods	Linear/Logistic regression, clustering, association rules, ARIMA	A: assoc. rules & ML; B: stats & ARIMA	regression_clustering.ipynb, arima_demo.ipynb
09 Projects	Real estate, review sentiment, stock forecasting, basic image tasks	Both: capstone cases	real_estate_case/, finance_sentiment_case/, stock_forecast_case/

Book A = “Python Data Analysis and Applications: from Acquisition to Visualization”
Book B = “Python Data Analysis”

---

🗂️ File Convention
Each module contains:

README.md — learning goals, key APIs, common pitfalls

*.ipynb — reproducible notebooks (with Objective → Dataset → Steps → Evaluation → Reflection pattern)

data/ — small example datasets or links

---

🧪 Mini-Assignments
Produce a publication-quality grouped summary table using groupby + agg.

Compute rolling volatility for returns using rolling/expanding and visualize with confidence bands.

Run a Chinese review pipeline: tokenization → term stats → simple sentiment; discuss bias sources.

Train a baseline KNN classifier; output confusion matrix + precision/recall/F1.

---

🔬 Research Hooks
Cleaning: Bias from imputation strategies; impact on downstream fairness.

Visualization: Truthful graphics—axes limits, log scales, outlier handling.

Time Series: Volatility clustering & resampling choices in finance.

Text: Domain lexicons vs. general sentiment; label noise in financial news.

ML Intro: Validation leakage, imbalanced data, baseline vs. complex models.

---

🚀 How to Use
Start at 02 → 03 → 04 for the core workflow.

Branch to 05 (time series) or 06 (text) based on your project.

Use 07/08 for baseline modeling — focus is analysis quality, not model zoo.

Promote a finished notebook into 09_projects with a short report.

---

🔗 Cross-Repository Links
Python fundamentals: teaching-python-programming

Applied projects (EdX/Kaggle): applied-data-science

Research drafts / preprints: research-preprints

---

📜 License
MIT License — academic and personal use permitted.

---

If you want, I can now **also** generate a *mini README template* for each module folder (so every subfolder has its own goals/datasets/reflections format), which will make the repo look extremely professional when viewed by a PhD committee.  

Do you want me to prepare that next? That way you can just paste it into each folder and fill in as y

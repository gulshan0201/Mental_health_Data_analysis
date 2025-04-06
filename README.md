🗂️ Dataset Description:
The dataset contains records of 120 patients, focusing on mental and emotional health indicators.
It includes 18 features such as:

Emotional states: Sadness, Euphoric feelings, Mood Swing, Nervous breakdown

Mental health risks: Suicidal thoughts, Anorexia, Overthinking

Behavioral traits: Authority Respect, Admit Mistakes, Ignore & Move-On

Cognitive factors: Concentration, Optimism

Target variable: Expert Diagnose — indicates whether the patient is diagnosed with a mental health disorder.

All entries are categorical, mostly with "YES"/"NO" responses.

🧩 Task Overview: What We Did
✅ Data Preparation

Checked for missing values.

Cleaned and converted categorical data to numerical (YES ➡️ 1, NO ➡️ 0) for analysis.

✅ Exploratory Data Analysis (EDA)

Visualised distributions of features.

Analysed class imbalance in Expert Diagnose.

Examined relationships between mood swings, suicidal thoughts, and other factors.

Detected outliers using boxplots.

Explored correlations between numerical features using heatmaps.

✅ Insights Generation

Identified which emotional and behavioral traits are strongly associated with expert diagnoses.

Visualised key mental health patterns that could help in early identification.

✅ Tools & Libraries Used

Pandas: Data handling and transformation

Seaborn & Matplotlib: Data visualisation (histograms, countplots, boxplots, heatmaps)

Jupyter Notebook: To build and document the analysis step-by-step.

In short:
We turned raw, categorical patient data into actionable insights about mental health patterns using Python’s data analysis stack.

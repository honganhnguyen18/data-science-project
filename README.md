# Data Science Project: Determinants of Language Learning Success and Fluency

## 1. Problem or Research Question
This project investigates the critical behavioral and structural factors influencing successful language acquisition. Specifically, it analyzes how total study hours, motivation, active use share, and starting age impact a learner's ability to achieve conversational fluency (CEFR B2 or above) or lead to dropping out.

## 2. Dataset Source and Usage Permissions
- **Source:** Language Learning Fluency Dataset (`language_learning_fluency.csv`), containing 45,000 learner behavioral records.
- **Permissions:** Publicly available dataset used strictly for academic research, data exploration, and educational portfolio demonstration purposes. All personal identifiers are anonymized.

## 3. Methods and Tools Used
- **Languages & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn.
- **Methods:** Exploratory Data Analysis (EDA), data cleaning, statistical distribution profiling, and feature correlation visualization.

## 4. Findings and One Limitation
- **Key Findings:** Total study hours and active practice share show a robust positive correlation with achieving fluency (CEFR B2+), whereas starting age primarily impacts pronunciation/accent scores rather than general milestone achievements.
- **Limitation:** The dataset assumes linear psychological metrics (such as motivation and consistency scores rated 0-10) which may contain subjective reporting bias from learners.

## 5. Instructions for Running the Analysis
1. Clone this repository: `git clone https://github.com/honganhnguyen18/data-science-project.git`
2. Install required packages: `pip install -r requirements.txt`
3. Ensure `language_learning_fluency.csv` is placed in the root directory.
4. Open `analysis.ipynb` in Jupyter Notebook and run all cells sequentially.

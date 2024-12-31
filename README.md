# AlphaCare-Insurance-Solutions
This repository contains the code, data, and reports for a multi-phase data analysis and modeling project. The project involves the use of Git, GitHub, Exploratory Data Analysis (EDA), Data Version Control (DVC), A/B Hypothesis Testing, and Statistical Modeling. The tasks are broken down into weekly milestones, with each task focusing on a different aspect of the data science workflow.
## Project Overview
This project is divided into four tasks that cover the complete data science pipeline:

**1. Task 1:Git, GitHub, and Exploratory Data Analysis (EDA)**
- Set up a GitHub repository with a clear README file.
- Branch out (task-1) and commit work regularly.
- Perform Descriptive Statistics and check data types.
- Identify missing values and handle them appropriately.
- Create and analyze visualizations (histograms, scatter plots, box plots, etc.).
- Create a summary report based on findings.

  
**2. Task 2: Data Version Control (DVC)**
- Install DVC and initialize it in the project directory.
- Set up local or cloud remote storage for data tracking.
- Add datasets to DVC and track versions.
- Commit .dvc files to Git and push changes to the remote repository.
- Create multiple versions of the dataset for tracking.

  
**3. Task 3: A/B Hypothesis Testing**
- Define key performance metrics (KPI) for testing.
- Segment data into control and test groups.
- Perform statistical tests (t-test, z-test, chi-square) for various hypotheses:
- Risk differences across provinces.
- Risk differences between zip codes.
- Gender differences in risk and margin.
- Analyze p-values and decide to accept or reject the null hypotheses.

  
**4. Task 4: Statistical Modeling**
- Handle missing data and perform feature engineering.
- Encode categorical data for modeling.
- Split data into training and test sets.
- Train models including Linear Regression, Decision Trees, Random Forest, and XGBoost.
- Evaluate models using accuracy, precision, recall, and F1-score.
- Interpret model outcomes using SHAP or LIME to understand feature importance.
- Compare the performance of different models.

Each task is tracked with version control using Git, and branches are created for each task for proper organization and collaboration.

## Technologies and Tools
- **Python:** Core programming language used for data analysis and modeling.
- **Pandas, Numpy:** Data manipulation and analysis.
- **Matplotlib, Seaborn:** Data visualization.
- **SciPy, Statsmodels:** Hypothesis testing and statistical analysis.
- **Scikit-learn:** Machine learning algorithms and modeling.
- **DVC:** Data version control for tracking datasets and models.
- **Git & GitHub:** Version control and collaboration.
- **GitHub Actions:** Continuous Integration (CI) and Continuous Deployment (CD).
## How to Use This Repository
1. Clone the repository:

```
git clone git@github.com:Eldiyanaa/AlphaCare-Insurance-Solutions.git
```
2. Set up a virtual environment and install dependencies:

```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```
3. Install DVC:

```
pip install dvc
```
4. Track datasets with DVC:

```
dvc pull
```
5. Run the analysis notebooks or scripts:

```
jupyter notebook  # or python src/eda.py
```
6. Commit and push changes:
```
git add .
git commit -m "Descriptive commit message"
git push origin branch-name
```
## License
This project is licensed under the MIT License.
"# AlphaCare-Insurance-Solutions-Analysis-updated" 

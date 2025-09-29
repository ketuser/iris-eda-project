# Iris Flower EDA: Exploring Species Classification

## Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Iris dataset**.  
The goal is to uncover patterns in sepal and petal measurements that help classify iris species.  


Key Skills Demonstrated

- Data Analytics: Python, Pandas
- Visualization: Seaborn, Plotly 3D
- SQL in Python: pandasql
- Version Control: Git & GitHub

>⚠️ Note: Interactive **Plotly 3D plots** do not render directly in GitHub’s preview.  
To view them online, see the **Deployment** section below.

---

## Problem Statement
**How do sepal and petal dimensions help distinguish between Iris species?

Key guiding questions:
1. Which species has the largest and smallest petals and sepals?
2. Are species clearly separable by petal/sepal dimensions?
3. What relationships exist between the four features?

Key Findings
1. Setosa has the smallest petals, while Virginica has the largest.
2. Setosa is clearly separable from the other two species, while Versicolor and Virginica show overlapping measurements.
3. Petal length and width are the strongest predictors of species classification, showing a very strong correlation (0.96).
4. A 3D scatter plot confirms clustering of Setosa, while Versicolor and Virginica remain harder to distinguish visually.

---

## Setup & Installation
Clone the repository and set up the environment:

```bash
git clone https://github.com/ketuser/iris-eda-project.git
cd iris-eda-project

# Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook eda.ipynb

---

## Project Structure
iris-eda-project/
│── eda.ipynb          # Jupyter Notebook with full analysis
│── iris-eda.html      # Interactive HTML version (for GitHub Pages)
│── requirements.txt   # Dependencies
│── README.md          # Project documentation





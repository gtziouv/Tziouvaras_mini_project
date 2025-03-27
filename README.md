# Tziouvaras_mini_project
Mini-Project for Programming Class 27/03/25
# MiniProject: Regression Analysis

## Overview
This project performs a regression analysis on fatigue levels, reaction time, and other variables. It includes data loading, visualization, regression modeling, and unit testing.

## Installation
Ensure you have Python installed. You can create an environment using `conda`:

```sh
conda create --name miniproject_env python=3.8
conda activate miniproject_env
```

Install required dependencies:

```sh
pip install pandas numpy matplotlib seaborn statsmodels openpyxl
```

## Running the Project
1. Place your dataset (`.xlsx` file) in the project folder.
2. Run the Jupyter Notebook (`miniproject_tziouvaras.ipynb`).
3. Ensure `miniproject.py` is in the same directory.

To run tests:

```sh
python -m unittest test_miniproject.py
```

## Project Structure
```
miniproject/
│── miniproject.py          # Main script with functions
│── miniproject_tziouvaras.ipynb  # Jupyter Notebook for analysis
│── test_miniproject.py     # Unit tests
│── data.xlsx               # Example dataset (not committed)
│── README.md               # Project documentation
```

## Version Control
Ensure you are using Git:
```sh
git init
git add .
git commit -m "Initial commit"
git remote add origin <your-repo-url>
git push -u origin main
```

## Notes
- The regression results are interpreted in the notebook.
- The project considers weaknesses and potential improvements.

Enjoy your analysis! 


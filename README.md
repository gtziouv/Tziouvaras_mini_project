# Driving Fatigue Analysis

This project investigates the relationship between driving fatigue and reaction times. Using a dataset that includes fatigue levels, hours of wakefulness, volume of work, and other driving-related metrics, the goal is to analyze how these variables influence a driver’s reaction time. The project performs statistical analysis through regression models and provides insights on the most significant predictors of reaction time while driving.

## Project Overview

Driving fatigue is a significant factor that can lead to reduced reaction times, increasing the risk of accidents on the road. In this project, we aim to identify the impact of various factors, such as fatigue levels and hours awake, on reaction time using Ordinary Least Squares (OLS) regression analysis. The insights gained could potentially contribute to road safety measures and help in understanding the critical elements that lead to poor reaction times in drivers.

## Installation

To set up the environment, you'll need to install the necessary dependencies. First, ensure you have Python installed. Then, create a virtual environment and install the required packages.

1. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

2. Activate the virtual environment:

    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```

3. Install the dependencies using `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Once you have the dependencies installed, you can run the project. The script will load the data, create visualizations, perform regression analysis, and print out the regression summary, followed by an interpretation of the results.

To run the analysis:

```bash
jupyter lab code_miniproject.ipynb




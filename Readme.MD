# Automobile Price Prediction - Auto MPG Dataset


## Overview

This project explores the fundamentals of machine learning by building regression models to predict automobile prices using the UCI Auto MPG dataset. The content is designed for educational purposes, suitable for workshops, tutorials, and as a reference for those interested in practical machine learning applications.

---

## Objectives

- **Hands-on experience** with regression (supervised learning) problems.
- **Understanding data preprocessing**, exploratory data analysis (EDA), and feature engineering.
- **Implementing and evaluating** various regression models, starting from simple linear regression to advanced methods.
- **Developing reproducible and well-documented code** in Jupyter Notebooks.

---

## Dataset Description

- **Source**: [UCI Machine Learning Repository - Auto MPG Data Set](https://archive.ics.uci.edu/ml/datasets/auto+mpg)
- **Description**: Contains data on fuel efficiency and other attributes of various cars from 1970s and 1980s, providing a practical regression problem.
- **Features:**
  - `mpg` — Miles per gallon *(target variable)*
  - `cylinders` — Number of cylinders
  - `displacement` — Engine displacement (cu. inches)
  - `horsepower` — Engine horsepower
  - `weight` — Vehicle weight (lbs)
  - `acceleration` — Acceleration (0-60 mph in seconds)
  - `model year` — Year of the car model
  - `origin` — Origin of car (US, Europe, Japan)
  - `car name` — Name/description (string, not used directly in modeling)

---

## Repository Structure
    ├── data/ # Raw and cleaned datasets
    ├── notebooks/ # Jupyter notebooks for tutorials and analysis
    ├── src/ # Source code (feature engineering, models, utils)
    ├── docs/ # Additional documentation, reports, or slides
    ├── README.md
    └── requirements.txt # Python dependencies

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/<your-username>/automobile-price-prediction.git
   cd automobile-price-prediction
2. **Install required packages:**
   ```bash
   pip install -r requirements.txt
3. **Run jupyter Notebook:**   
    jupyter notebook
    # or
    jupyter lab

4. **Open the main notebook in the notebooks/ directory.**

## Prerequisites
    Python 3.8+
    Jupyter Notebook / Jupyter Lab
    Data science libraries: numpy, pandas, scikit-learn, matplotlib, seaborn, etc.

## Learning Goals
    By the end of this exercise, you will be able to:
    Prepare and clean real-world datasets for regression analysis
    Visualize data distributions and relationships between features
    Implement, tune, and evaluate regression models
    Interpret results and identify potential improvements

## License
This project is licensed under the MIT License.


## Author
    Name : Mahdi Farhani
    Position : Senior Software Developer, Ph.D. candidate (AI)

## Acknowledgements
    UCI Machine Learning Repository
    scikit-learn, pandas, matplotlib, seaborn contributors
    Workshop participants and reviewers
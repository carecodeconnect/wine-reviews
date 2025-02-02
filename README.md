# Introduction to Exploratory Data Analysis

## Wine Reviews Tutorial

In this tutorial, we use the `wine-reviews` dataset to learn exploratory data analysis using Python.

![Wine Reviews Tutorial](https://upload.wikimedia.org/wikipedia/commons/a/a0/Tempranillowine.jpg)

We learn how to apply tools used by data analysts and data scientists for data exploration and data visualisation:

* `pandas`: data importing, exploration, manipulation.

* `matplotlib`: creating static, animated, and interactive visualisations.

* `seaborn`: high-level data visualisation library built ontop of `matplotlib`.

* `ydata-profiling`: data profiling tool for exploratory data analysis.

* `pygwalker`: creates Tableau-style data visualisations.

## Dataset

We analyse the [wine-reviews](https://www.kaggle.com/datasets/zynicide/wine-reviews) dataset, which features `150_930` wine reviews scraped from the **WineEnthusiast** magazine in 2017.

## Getting Started

To do the tutorial:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/carecodeconnect/wine-reviews
   ```

2. Navigate to the project directory:

   ```
   cd wine-reviews
   ```

3. Setup your environment and required dependencies:

   ```
   conda create -n wine-reviews python=3.10
   pip install -r requirements.txt
   ```
4. Open the Jupyter notebooks with a text editor of your choice (e.g. Visual Studio Code).

## Project Structure

Below is the tree structure of the project for quick reference:

```
├── data/                   # Folder containing data file
├── notebooks/              # Folder containing Jupyter notebooks 
├── LICENCE                 # MIT licence
├── README.md               # Project overview and setup instructions
└── requirements.txt        # List of dependencies to install
```

# Big Data Analytics Course Final Project

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributors](#contributors)

## Introduction
This repository contains the final project of the Big Data Analytics course. The project demonstrates our ability to handle, process, and analyze large datasets using various big data technologies and techniques.

## Project Overview
In this project, we analyzed the relationship between the movement of people in the U.S. and the spread of COVID-19. We gathered different kinds of data from multiple sources, cleaned and merged them, and performed various analyses to uncover insights.

### Key Features
- Data preprocessing and cleaning
- Exploratory data analysis (EDA)
- Implementation of data analytics models
- Visualization of results
- Interpretation and insights

## Dataset
The datasets used for this project are:
1. **Trips by Distance**: Data from the U.S. Department of Transportation on the number of trips taken and the distance traveled.
   - Source: [Trips by Distance](https://data.bts.gov/Research-and-Statistics/Trips-by-Distance/w96p-f2qv/data)
   
2. **COVID-19 Cases and Deaths**: Data from USAFacts.org on the number of COVID-19 cases and deaths over time.
   - Source: [USAFacts COVID-19 Data](https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/)

## Installation
To run the code in this repository, you'll need the following libraries and dependencies:

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone [repository link]
   cd [repository folder]
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Copy_of_Project_CIS_545.ipynb
   ```

3. Follow the instructions in the notebook to run each cell sequentially.

### Data Cleaning and Preprocessing
The data cleaning and preprocessing steps involved:
- Removing irrelevant columns and rows with missing data
- Aggregating data on a monthly basis
- Merging datasets to create a comprehensive time series dataset

### Analysis
The analysis performed includes:
- Visualization of COVID-19 cases and deaths over time
- Examination of the correlation between travel patterns and COVID-19 spread
- Identification of trends and patterns in the data

## Results
The project resulted in several key findings:
- There is a notable correlation between the movement of people and the spread of COVID-19.
- Certain periods of increased travel correspond to spikes in COVID-19 cases and deaths.
- Visualizations clearly show the impact of travel restrictions on the pandemic's progression.

![Visualization Example](path/to/visualization.png)

## Contributors
- Olanrewaju Soetan
- Ibrahim Fagbamila
- Kamran Elahi

 # COVID-19 Data Analysis and Visualization

This repository contains code for analyzing and visualizing COVID-19 data at the county level. It includes functionalities for loading data, generating predictions, visualizing results, and creating interactive HTML reports.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
- [Data Sources](#data-sources)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is designed to provide insights into the spread and impact of COVID-19 at the county level. By leveraging various data science techniques and visualization tools, users can gain a better understanding of the trends and patterns in the data. The main features of this project include data loading, prediction generation, and interactive visualizations.

## Installation

To run this project, you need to have Python installed on your system. Follow the steps below to set up the project:

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/your-repo.git
    cd your-repo
    ```

2. **Install Required Packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Once you have installed the required packages, you can run the main script to start the data analysis and visualization process:

1. **Run the Main Script:**
    ```bash
    python main_script.py
    ```

This will execute the necessary functions to load the data, generate predictions, and create visualizations.

## Functions

The project contains several key functions that perform specific tasks:

- **`add_pre(df, var, name, newname)`**: Adds predictions to the dataframe.
- **`add_prediction_history(df_tab)`**: Adds prediction history to the dataframe.
- **`generate_all_counties()`**: Generates HTML reports for individual counties.
- **`rename(df)`**: Renames columns in the dataframe.
- **`generate_map(df)`**: Generates map and table HTML code.
- **`fillstate(df)`**: Fills the state full name according to their abbreviations.
- **`update_html(maps)`**: Updates `search.html`.
- **`add_rates(df_county)`**: Adds cases/deaths rate to the dataframe.
- **`add_new(df_county)`**: Adds new cases/deaths to the dataframe.
- **`add_new_pre(df_county, var, name, newname)`**: Adds new predictions and intervals.

## Data Sources

The data is loaded from various sources and can be customized based on your requirements. This allows for flexible and comprehensive analysis tailored to different datasets.

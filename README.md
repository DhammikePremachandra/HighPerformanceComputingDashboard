# HPC Insight Dashboard

## Table of Contents
- Introduction
- Project Details
- Features
- Getting Started
- Usage
- Visualizations
- Insights and Conclusions

## Introduction
The HPC Insight Dashboard is a visualization tool that provides detailed insights into the performance metrics of various High-Performance Computing (HPC) systems. It is designed to assist users in comparing and analyzing the capabilities of different HPC systems for Data Science tasks, enabling informed decision-making and strategic planning.

## Project Details
The project involves the following key steps:

1. Importing necessary libraries for data analysis and visualization.
2. Loading the dataset into a pandas DataFrame.
3. Data preprocessing, including handling missing values, dropping unnecessary columns, and normalizing text data.
4. Exploratory Data Analysis (EDA) to gain insights into the dataset.
5. Visualization of performance metrics using various plots such as bar plots, box plots, violin plots, and scatter plots.
6. Creation of interactive and informative visualizations to showcase top performers, trends over time, and geographical distribution.
7. Conclusion and recommendations based on the insights derived from the analysis.

## Features
- **Data Preprocessing**: Automated cleaning and preparation of the TOP500 supercomputer dataset.
- **Advanced Visualization**: Customizable plots using Matplotlib and Seaborn to illustrate HPC systems' performance.
- **Performance Metrics Analysis**: Evaluation based on Rmax (TFlop/s), processor speed, and total cores.
- **Interactive User Interface**: Easy-to-navigate dashboard for non-technical stakeholders.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn

### Installation
Clone the repository:
```bash
git clone https://github.com/DhammikePremachandra/HighPerformanceComputingDashboard.git
```
Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage
To run the HPC Insight Dashboard, navigate to the project directory and execute:
```bash
python HPC_Dashboard.ipynb
```

## Visualizations
The dashboard provides several visualizations to assess the performance of supercomputers, including:
- **Parallel Coordinates Plot**: For top systems comparison.
- **Bar Plot**: Comparing top systems vs processor speed for top performers.
- **Area Map**: Showcasing top performers over the years.
- **Violin Plots**: Illustrating Rmax distribution by continent.
- **Bar Plot**: Highlighting top manufacturers by the number of systems.
- **Bar plots**: Illustrating Top performers by Rmax (TFlop/s).
- **Scatter plot**: Scatter plot matrices for metric distributions.
- **Heatmaps**: Correlation analysis.
- **Count plots**: Illustrating processor speed frequency.

## Insights and Conclusions
- **Top Performer**: Fugaku, with an Rmax of approximately 470,000 TFlop/s.
- **Top Manufacturer**: Lenovo, leading in the number of supercomputers produced.
- **Optimal Choices**: Depending on the need for computational performance, processor speed, or core count, Fugaku, Sierra, or Summit might be suitable.

📊 Environmental Telemetry Data Analytics & Law of Large Numbers Visualization

This project applies data analytics, feature engineering, and statistical visualization techniques to real-world IoT telemetry data and simulated statistical experiments.
It demonstrates how data preprocessing and visualization help uncover insights from both environmental sensor readings and probabilistic models.

Kaggle dataset link: https://bit.ly/environmental-sensor-data

🌱 Project Summary

The project is divided into two main parts:

Environmental Telemetry Data Analytics
Focused on cleaning, standardizing, and extracting meaningful features from IoT sensor data.
Multiple visualizations were created to explore and compare environmental metrics across devices.

Law of Large Numbers (LLN) Visualization
Used statistical simulation to show how sample means converge to true expectations.
Visualized the stabilization of empirical averages through dynamic data plots.

🔍 Part 1: Environmental Sensor Data Analytics

Imported and cleaned IoT telemetry data collected from Raspberry Pi-based environmental sensors.

Applied feature engineering techniques such as:

Mean, geometric mean, harmonic mean

Variance, skewness, and kurtosis

Standardized continuous variables and applied one-hot encoding to categorical variables.

Generated grouped bar charts and summary visualizations comparing devices across key environmental parameters (temperature, humidity, CO, LPG, smoke).

Transformed raw sensor data into a structured analytical dataset ready for statistical modeling.

Visualization Example:
Grouped bar charts showing mean and variance comparisons across three IoT devices.

🎲 Part 2: Law of Large Numbers Simulation

Conducted Monte Carlo–style simulations of 10,000 dice rolls (both fair and biased).

Calculated empirical means for each trial and compared them to expected values.

Created Matplotlib visualizations demonstrating:

How the empirical mean stabilizes around the expected value (E[D]) as sample size increases.

How absolute discrepancies decrease with larger sample sizes (|Mₙ − E[D]|).

Highlighted the statistical foundation behind Empirical Risk Minimization (ERM) in machine learning.

Visualization Example:
Line plots showing convergence of sample means for fair and unfair dice — an illustration of LLN in action.

🧠 Data Analytics Concepts Demonstrated

Data preprocessing and feature engineering

Standardization and encoding techniques

Exploratory data analysis (EDA) using visualizations

Understanding of statistical convergence (LLN)

Interpretation of data trends using Python plots

Communicating insights through graphs and annotations

🧰 Tools and Libraries

Python 3.x

NumPy

Pandas

SciPy

Matplotlib

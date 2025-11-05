Environmental Telemetry and Law of Large Numbers Simulation

This project combines feature engineering, data preprocessing, and statistical visualization using Python.
It explores how empirical averages converge to expected values (Law of Large Numbers) through simulations and applies feature extraction on IoT sensor telemetry data.

Project Overview

Feature Engineering for IoT Sensor Data

Processed environmental telemetry data from Raspberry Pi sensor arrays.

Performed data standardization, one-hot encoding, and feature generation (mean, variance, geometric mean, kurtosis, skewness, etc.).

Created grouped bar charts comparing sensor metrics across multiple devices.

Visualization of the Law of Large Numbers (LLN)

Simulated 10,000 dice rolls (fair and unfair) to analyze empirical mean stabilization.

Visualized convergence behavior using Matplotlib line plots:

Empirical average vs. expected value for fair and biased dice.

Absolute discrepancy decreasing with sample size (|Mₙ − E[D]|).

Demonstrated LLN concept, showing that as n increases, sample averages approach true expectations.

Tools and Libraries

Python (NumPy, Pandas, SciPy, Matplotlib)

Data visualization and statistical analysis

Jupyter Notebook environment

Concepts Demonstrated

Feature engineering and data preprocessing

Empirical Risk Minimization (ERM)

Statistical visualization of convergence trends

Interpretation of real-world IoT data patterns

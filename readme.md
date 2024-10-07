###Confidence Interval Calculator for Z Procedure
This is a simple web app that calculates and visualizes the confidence interval for a population mean using a Z-procedure. The app allows users to input parameters like confidence level, sample mean, population standard deviation, and sample size, and then computes the confidence interval along with a visualization of the interval.

Features
Calculates the confidence interval for a population mean using a Z-procedure.
Allows users to adjust the confidence level, sample mean, population standard deviation, and sample size via an interactive sidebar.
Displays the computed critical value (z-score), margin of error, and the confidence interval.
Visualizes the confidence interval in a simple matplotlib bar chart with the lower and upper limits and a reference line for the sample mean.
Demo
The app looks like this when it's running:

<!-- You can add an actual image here by taking a screenshot of the app -->

How to Use
Set the Input Parameters:

Use the sidebar to set the confidence level (in percentage).
Input values for the sample mean, population standard deviation, and sample size.
Get the Results:

The app will automatically calculate and display:
The critical value (z-score).
The margin of error.
The confidence interval as a range (lower limit, upper limit).
Visualize the Confidence Interval:

A simple bar plot will show the lower limit, upper limit, and a dashed line indicating the sample mean.
Getting Started
Prerequisites
Before running the app, ensure that you have Python installed on your machine. You will also need the following Python packages:

Streamlit
NumPy
SciPy
Matplotlib



Files
Confidance_interval.py: The main Python script containing the Streamlit app code.
requirements.txt: Lists the required Python packages for the project (if you wish to add one).
README.md: This documentation file.
Technologies Used
Streamlit: Used to build the web app interface.
NumPy: For numerical computations.
SciPy (norm.ppf): For calculating the z-score based on the confidence level.
Matplotlib: For visualizing the confidence interval as a bar plot.
# geomagnetic
Predicting Geomagnetic Storms: Interactive Report
Overview

This project presents an interactive web-based report designed to communicate the findings of a thesis on predicting geomagnetic storms using machine learning models, with a focus on New Zealand's local data from the Eyrewell Geomagnetic Observatory.

The report provides:

    A high-level introduction to the problem.

    Exploratory data analysis showcasing storm patterns and feature importance.

    A model comparison dashboard ("Model Showdown") for evaluating prediction performance.

    A probabilistic forecasting section to illustrate uncertainty.

    Key takeaways and future directions.

Features

    Interactive Charts: Built using Chart.js, users can explore storm timelines, magnetic field behavior, and model performance.

    Dynamic Model Comparison: Switch between different machine learning models and feature sets to see their effects on predictions.

    Probabilistic Forecasting: Visualize uncertainty through confidence intervals from Monte Carlo LSTM and Quantile Regression models.

    Responsive Design: The report adjusts to different screen sizes for optimal viewing.

Technologies Used

    HTML/CSS: TailwindCSS for styling and responsive design.

    JavaScript: Core logic and interactivity.

    Chart.js: All charts and visualizations are powered by this library.

    Fonts: Google Fonts (Inter).

File Structure

    geomagneticstormdetails.html: Main interactive report containing all visualizations and logic in a single file.

How to Run

    Open geomagneticstormdetails.html in any modern web browser (e.g., Chrome, Firefox).

    No server setup or additional installation is required. All charts and interactions are rendered client-side.

Sections of the Report

    Introduction: Context of geomagnetic storms and their impact.

    Understanding the Data: Exploratory charts, storm vs. quiet day behavior, and feature correlations.

    Model Showdown: Interactive model predictions and performance metrics.

    Forecasting with Uncertainty: Probabilistic forecast comparisons.

    Key Takeaways: Summary of insights and future recommendations.

Notes

    All data shown in the interactive charts are either simulated for demonstration or drawn from the summarized results of the thesis work.

    The application is self-contained; no external APIs or dynamic data sources are queried at runtime.

Author

This report was designed and developed by Dhruv Sharma as part of the thesis project at the University of Otago (2025).

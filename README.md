# heart-desease-dashboard
📊 Heart Disease Interactive Visualization Dashboard
🧠 Overview

This project is an interactive web-based data visualization dashboard built using Plotly.js. It uses the Heart Disease UCI dataset (Kaggle version) to explore relationships between medical attributes and heart disease presence.

The dashboard is fully dynamic, allowing users to filter, compare, and interact with multiple visualizations simultaneously.

⚙️ Dataset Information

The dataset contains patient health records used for heart disease analysis. Key attributes include:

Age
Sex
Resting Blood Pressure (RestingBP)
Cholesterol
Maximum Heart Rate (MaxHR)
Heart Disease (target variable: 0 or 1)

It is widely used for binary classification and exploratory medical data analysis.

🚀 Dashboard Features (7 Core Interactions)
1. 📍 Interactive Scatter / Line / Bubble Plot

Users can dynamically explore relationships between variables:

Select X-axis and Y-axis variables
Switch between:
Scatter plot (markers)
Line chart
Line + markers
Enable bubble sizing based on Age or Cholesterol
Apply color encoding using:
Heart Disease
Sex
Choose different color scales (Viridis / Jet)

👉 Purpose: Understand correlations between health indicators.

2. 🔄 Axis Swapping (Scatter Plot)

A single button allows users to:

Swap X and Y axes instantly
Re-render the visualization dynamically

👉 Purpose: Quickly compare inverse relationships between variables.

3. 🎯 Dynamic Filtering (Age-based + Cross-filtering)

Each chart includes filtering options:

Filter data by Age threshold
Apply global filter from clicked points
Clicking a data point in any chart updates all others

👉 Purpose: Enables linked exploration across all visualizations.

4. 📊 Histogram + Box Plot Switching

Users can switch between:

Histogram (distribution view)
Box plot (statistical summary)

Additional options:

Group by Sex or Heart Disease
Overlay or stacked visualization modes

👉 Purpose: Understand distribution and spread of medical features.

5. 🧮 Bar Chart + Pie Chart Toggle

The categorical visualization supports:

Bar chart (vertical / horizontal)
Pie chart representation
Aggregation by:
Sex
Heart Disease

👉 Purpose: Compare class distributions visually.

6. 🎨 Color Encoding + Scaling System

All charts support advanced color mapping:

Categorical encoding (Sex / Heart Disease)
Continuous scaling using:
Viridis
Jet

👉 Purpose: Improve pattern recognition and grouping.

7. 🔗 Cross-Chart Interaction (Linked Brushing)

This is the most powerful feature:

Clicking a point in the scatter plot:
Sets a global filter
Updates histogram + bar chart automatically
Clicking bar segments also updates other plots

👉 Purpose: Enables multi-view data exploration (brushing & linking).



💡 Key Learning Outcomes

This project demonstrates:

Interactive data visualization design
Event-driven programming in JavaScript
Data filtering and aggregation techniques
Multi-view linked visual analytics
Real-world medical dataset exploration

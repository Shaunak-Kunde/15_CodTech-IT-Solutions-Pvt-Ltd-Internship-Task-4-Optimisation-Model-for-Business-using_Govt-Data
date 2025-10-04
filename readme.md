# CODTECH Internship – Task 4: Optimising Index of Industrial Production and Growth Rate for Bottom-Performing Industries in India

### Company:- CodTech IT Solutions Pvt. Ltd., Hyderabad
### Name:- Shaunak Damodar Sinai Kunde
### Intern ID:- CT04DY1729
### Domain:- Data Science
### Duration:- 4 weeks
### Mentor:- Muzammil Ahmed

This project is part of my Virtual Internship with CODTECH IT Solutions Pvt. Ltd. Hyderabad,  under Data Science domain.

The objective is to analyse real-world business problem, identify bottom-performing industries, and apply an optimization model to improve their Index of Industrial Production (IIP) and Growth Rate.

Unlike Kaggle or synthetic datasets,
# this project uses authentic data from the Ministry of Statistics and Programme Implementation (MOSPI) e-Sankhyiki portal, ensuring real-world relevance.

# 📊 Project Overview

# Goal: Optimise IIP and Growth Rate for industries underperforming in India.

Dataset Source: MOSPI e-Sankhyiki – IIP

## URL https://esankhyiki.mospi.gov.in/macroindicators?product=iip

Time Period: 2012–2025

Focus: Industries (sub-categories) with lowest Index (<100) and negative Growth Rate (<0).

# 🚀 Workflow
# 1. Data Preprocessing

Cleaned and standardized column names.

Handled missing values by replacing NaN with 0.

Converted month names to numeric and abbreviated forms.

Filtered to identify bottom-performing sub-categories based on Index and Growth Rate.

# 2. Exploratory Data Analysis & Visualizations

Category-level Insights:

Bar chart of average IIP Growth Rate by category (2012–2025).

Box plot showing distribution of Index across categories.

Heatmap of monthly average Index values per category.

Line plot of average Index by category over years.

Pie chart showing contribution of each category to overall Index.

Bottom 5 Sub-Categories Analysis (2025):

Bar chart of lowest Growth Rate sub-categories.

Side-by-side bar chart: Index before vs after optimization.

Line chart: Growth Rate before vs after optimization.

# 3. Optimization Model

Developed a custom optimization function focused on the bottom 5 performers.

Steps in optimization:

Boosted Index values by a configurable improvement factor (e.g., 20%).

Adjusted Growth Rate values closer to zero or positive.

Compared metrics before and after optimization to quantify improvement.

# 4. Insights from Optimization

Average Index (Bottom 5): improved after optimization.

Average Growth Rate (Bottom 5): positive trend observed after optimization.

Visualization confirms targeted improvements in weakest-performing sub-categories.

# 🛠️ Tools & Libraries

Python 3.10+ – Programming language

Pandas & NumPy – Data manipulation

Matplotlib & Seaborn – Data visualization

# PuLP – Optimization modeling (linear programming for Index improvement)

📂 Project Structure
Task-4 IIP Optimisation Project/
│── iip_2.xlsx
│── Task4_Optimisation_Model.ipynb
│── readme.md

# ✅ Key Takeaways

Focusing on bottom performers allows targeted performance improvement.

The optimization model is scalable and adaptable to other sub-categories or industries.

Real-world Government of India IIP data ensures authenticity and applicability.

Visualizations clearly show pre- and post-optimization trends for Index and Growth Rate.
<img width="911" height="480" alt="image" src="https://github.com/user-attachments/assets/7a42a8b0-549e-480f-9d54-c91fa51be1e1" />


# ⚠️ Notes

Only bottom 5 sub-categories were optimized; the model can be extended to more industries.

Ensure iip_2.xlsx is present to run the notebook and reproduce results.

Improvement factor in the optimization function can be adjusted to explore different impact levels.


# 👨‍💻 Developed by: Shaunak Damodar Sinai Kunde





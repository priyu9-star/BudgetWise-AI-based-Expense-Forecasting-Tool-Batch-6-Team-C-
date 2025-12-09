⚡ SpendGenie – AI-Powered Personal Expense Tracker
Overview

SpendGenie is an intelligent personal expense tracking system designed to help users analyze, categorize, and predict their expenses. It integrates data processing, visualization, and predictive analytics into a single, user-friendly web interface.

<p align="center"> <img src="/assets/images/dashboard.png" alt="SpendGenie Dashboard" width="700"/> </p>

Key Highlights:

Dynamic category-wise expense tracking
Time-based filtering: daily, weekly, monthly, or custom ranges
Predictive analysis based on historical averages
Interactive and clean Notion-inspired UI

Problem Statement

Many individuals struggle to manage finances due to:
Lack of category-wise visibility
Difficulty tracking spending trends over time
Inability to forecast future expenses
SpendGenie solves this by providing data-driven insights and predictions, empowering users to make informed financial decisions.

Objectives

Track Expenses: Categorize expenses from CSV uploads or manual input.
Analyze Spending Patterns: Summarize expenses by category and time periods.
Predict Future Expenses: Estimate upcoming costs using historical averages.
Interactive Dashboard: Provide an intuitive interface for quick analysis.

Architecture & Workflow

Conceptual Flow
CSV Upload / Manual Entry → Data Normalization → Category Aggregation → Display Totals
                                               → Average Calculation → Predictive Estimate

Technical Architecture

Frontend: HTML, CSS, Flask templates for UI and forms
Backend: Flask routes handle data processing, aggregation, and prediction
Data Handling: Pandas for normalization, aggregation, filtering, and calculations
Deployment: ngrok exposes Flask server publicly from Google Colab

Features

1. Expense Tracking
Upload CSV with item/category, price, date
Automatically detect and normalize categories
Time-based filtering: daily, weekly, monthly, or custom ranges
<p align="center"> <img src="/assets/images/upload.png" alt="Flowchart" width="600"/> </p>

2. Predictive Analysis
   
Predict future expenses for any category
Simple historical average × days/weeks/months model
<p align="center"> <img src="/assets/images/prediction page.png" alt="Prediction Page" width="600"/> </p>

Prediction Formula:

Predicted Expense = Average Daily Expense × Number of Days (or Weeks/Months)
Predicted Expense=Average Daily Expense×Number of Days (or Weeks/Months)

3. Manual Expense Input
   
Add expenses matching existing categories
Ensures data consistency with CSV-imported categories
<p align="center"> <img src="/assets/images/add expense.png" alt="Manual Expense Input" width="600"/> </p>

Technologies Used

Python 3.10+ – Core programming language.
Flask – Web framework for building interactive routes and templates.
Pandas – Data processing, parsing, and analytics.
ngrok – Expose local Flask server to a public URL.
HTML/CSS – Frontend layout with a modern, dark UI.

Benefits

Gain financial awareness by category
Forecast future expenses for better budgeting
Flexible data input: CSV or manual entry
Interactive dashboard: easy-to-read summaries

Future Enhancements

Graphs & Visualizations: Pie charts, bar graphs, trendlines
Advanced Prediction Models: ML-based forecasting
Multi-user Support: Personalized dashboards
Export Reports: PDF or Excel summaries
Mobile-Friendly UI: Responsive design for smartphones

How to Run

Open the SpendGenie Colab notebook
Install dependencies (Flask, Pandas, ngrok)
Run the notebook; a public URL is generated
Upload your CSV file or add manual expenses
Navigate the Expense Tracker, Prediction, and Expense Input tabs

## License

This project is **proprietary**. Usage of this code is **restricted** to the following team members only:

- Kavya Sampathirao (kavs14345@gmail.com)  
- Kokila M (kokilakoki3376@gmail.com)  
- Nandi Mangalam Geervani (geervaninandimangalam26@gmail.com)  
- Poolasetty Chandana (chandana334411@gmail.com)  
- Pratyasha Basak (pratyasha.basak17@gmail.com)  
- Priyanshi Jayant (priyanshijayant729@gmail.com)  
- Pulugrutha Sai Tejaswini (saitejaswini389@gmail.com)  

For full license details, see the [LICENSE](./LICENSE) file.


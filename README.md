📊 Investment Behavior Analysis Dashboard – Power BI
📌 Project Overview
The Investment Behavior Analysis Dashboard analyzes survey data of 40 respondents to understand their investment preferences, risk appetite, financial goals, and decision-making behavior.
This project demonstrates data cleaning, transformation (unpivoting), DAX calculations, and interactive dashboard design in Power BI.

📂 Dataset Summary
Total Respondents: 40
Total Columns: 24
Average Age: 27.8 years
Gender Distribution:
Male: 25
Female: 15

🎯 Analysis Objectives
The dashboard answers the following questions:
Which investment avenues are most preferred?
What is the preferred investment duration?
What returns do investors expect?
What factors influence investment decisions?
What are the primary savings objectives?
What sources influence investment decisions?

📊 Key Insights from Dataset
🏆 Most Preferred Investment Avenue
Mutual Fund (Highest selected in “Avenue” column)

⏳ Investment Duration Preference
3–5 years → 19 respondents (Highest)
1–3 years → 18 respondents
Less than 1 year → 2 respondents
More than 5 years → 1 respondent
➡ Majority prefer medium-term investments (1–5 years).

📢 Top Investment Information Source
Financial Consultants (Most common source)

💰 Expected Returns
Most respondents expect returns between 20%–30%

🎯 Savings Objectives
Retirement Planning
Health Care
Wealth Creation

🧠 Factors Influencing Investment
Better Returns
Capital Appreciation
Tax Benefits
Safe Investment
High Interest Rates

🧮 Important DAX Measures Used
Total Respondents = COUNTROWS(Data_set 2)

If using unpivoted table:
Total Respondents = DISTINCTCOUNT(Data_set 2[Index])
Preferred Avenue Count = COUNT(Data_set 2[Avenue])
Investment Percentage =
DIVIDE(
    COUNT(Data_set 2[Avenue]),
    COUNTROWS(Data_set 2)
)

📊 Dashboard Visuals Included
✅ KPI Cards
Total Respondents
Average Age
Most Preferred Investment
✅ Gender Distribution (Pie/Donut Chart)
✅ Investment Duration (Bar Chart)
✅ Expected Return Distribution
✅ Investment Source Analysis
✅ Savings Objectives Breakdown
✅ Reasons for Investment (Equity, Mutual Fund, Bonds, FD)
✅ Interactive Slicers (Gender, Duration, Source, Expectation)

📈 Business Insights
Mutual Funds are the most preferred investment option.
Investors prefer medium-term investments (1–5 years).
Financial Consultants are the strongest influence source.
Safety, returns, and capital appreciation are key decision drivers.
Majority expect 20%–30% returns, indicating moderate-to-high return expectations.

💡 Skills Demonstrated
Data Cleaning & Transformation
Handling Unpivot Data Issues
Data Modeling in Power BI
DAX Calculations
Business Insight Generation
Interactive Dashboard Design

COGNIFYZ DATA VISUALIZATION INTERNSHIP

# Excel Data Analysis – Gender & Investment Preferences

## Project Overview
This repository contains Excel-based data analysis for survey data, focusing on two key areas:  

1. **Level 1:** Gender Distribution Analysis  
2. **Level 2:** Investment Preferences Analysis  

The analysis includes calculations using Excel functions and visualizations using pivot tables, pie charts, and stacked bar charts.

---

## Level 1: Gender Distribution Analysis

### Objective
Analyze the gender distribution of participants and visualize it clearly.

### Steps Performed
1. Opened the dataset in Excel and preserved all original data.
2. Calculated the count of participants for each gender using the `COUNTIF` function.
3. Created a pie chart to visualize the distribution of male and female participants.
4. Labeled pie chart segments with gender categories (Male / Female).
5. Customized chart appearance (colors, labels).
6. Added chart title: **"Gender Distribution Analysis"**.
7. Saved the Excel file with the chart included.

### Outcome
- Clear visual representation of gender distribution in the dataset.
- Ready for presentation or reporting purposes.

---

## Level 2: Investment Preferences Analysis

### Objective
Analyze participants' investment preferences and their reasons for choosing specific avenues.

### Steps Performed

#### 1. Distribution of Investment Avenues
- Created a pivot table summarizing the count of participants for each investment avenue (`Investment_Avenues` column).
- Generated a **bar chart** to illustrate the distribution of participants across different investment avenues.
- Added chart title: **"Distribution of Participants Across Investment Avenues"**.
- Customized chart with axis labels and legend.

#### 2. Reasons for Choosing Investment Avenues
- For each type of investment (Equity, Mutual Funds, Bonds, Fixed Deposits):
  - Created separate pivot tables summarizing **reasons provided by participants**.
  - Rows: `Investment_Avenues`
  - Columns: Reason column (e.g., `Reason_Equity`, `Reason_Mutual`, etc.)
  - Values: Count of participants (`gender` column used as identifier)
- Created **4 stacked bar charts**, one for each investment type:
  1. **Reasons for Choosing Equity Investments**  
  2. **Reasons for Choosing Mutual Fund Investments**  
  3. **Reasons for Choosing Bonds**  
  4. **Reasons for Choosing Fixed Deposits**
- Labeled axes, added chart titles, legends, and customized colors for clarity.

### Outcome
- Bar chart showing **participant distribution across investment avenues**.
- Four stacked bar charts showing **reasons for choosing each investment type**, clearly visualized per investment avenue.
- Excel file contains all pivot tables and charts, ready for reporting or presentation.

---

## Tools Used
- Microsoft Excel
- Functions: `COUNTIF`
- Pivot Tables
- Pie Charts
- Bar Charts
- Stacked Bar Charts

---

## File Structure
- `Level1_Gender_Distribution.xlsx` → Pie chart of gender distribution  
- `Level2_Investment_Preferences.xlsx` → Bar chart of investment avenues + 4 stacked bar charts of reasons  

---

## Summary
This project demonstrates how Excel can be used to clean, summarize, and visualize survey data, providing actionable insights on gender distribution and investment preferences of participants.

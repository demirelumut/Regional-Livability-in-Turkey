# Housing Data Analysis and Living Conditions Evaluation

This project analyzes housing data from Turkey to evaluate living conditions across different regions. By processing Excel datasets, the project visualizes housing issues and provides an interactive tool that allows users to assess conditions based on region, income, and housing size.

## 🔍 Project Overview

- **Data Sources:** `Q2housingdata.xlsx` and `Q2explanation.xlsx`
- **Data Cleaning:** Selects relevant columns and maps variable codes to descriptive names
- **Data Visualization:** Creates a line graph showing the percentage of reported housing problems by region
- **User Interaction:** Accepts user input to assess living conditions in a selected region
- **Output:** Saves cleaned and labeled data to `Q2_final.xlsx`

## 🛠️ Libraries Used

- `pandas`
- `matplotlib`

## 📊 Key Variables

| Code   | Description                                |
|--------|--------------------------------------------|
| HB030  | Province Code                               |
| HB031  | Region Code                                 |
| HH070  | Housing Area (square meters)               |
| HS010-070 | Housing Problems (e.g., Dampness, Heating issues) |
| HE050  | Net Household Income                        |

## 📈 Visualization

The project includes a line chart that displays the percentage of housing problems rated as “poor” (value `1`) across various regions.

## 💡 Features

- Region selection from a predefined list
- Displays valid income range based on selected region
- Filters suitable housing areas based on income
- Evaluates living conditions using a problem ratio and categorizes the result (e.g., "very good", "poor", etc.)

## 🧪 How to Run

1. Place the Excel files in the project directory:
   - `Q2housingdata.xlsx`
   - `Q2explanation.xlsx`
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib openpyxl

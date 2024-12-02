# 🛒 Retail Sales Performance Analysis

## 🎯 **Goal**
Analyze retail sales data to summarize performance metrics by counties and products, categorize sales volumes, and derive actionable insights for decision-making.

---

## 📋 **Description**
This project involves analyzing retail sales data in **Excel** to:
- Summarize performance across counties and product categories.
- Apply Excel tools like PivotTables, SWITCH functions, and aggregate functions for analysis.
- Categorize sales volumes into High, Medium, and Low using logical formulas.
- Visualize key insights with charts and tables for actionable takeaways.

---

## 💡 **Skills Demonstrated**
- **Data Analysis and Visualization**
- Advanced Excel Functions:
  - SWITCH
  - SUM
  - AVERAGE
  - VLOOKUP/XLOOKUP
  - Data Validation and Concatenation
- **Pivot Table Creation and Manipulation**
- **Data Categorization**

---

## 💻 **Technology Used**
- **Microsoft Excel**:
  - PivotTables
  - Functions
  - Charts

---

## 🚀 **Steps/Process Followed**

### 1. **Dataset Exploration and Preparation**
   - Imported the retail sales dataset into Excel.
   - Structured the dataset into tables for easy filtering and analysis.
   - Reviewed key fields such as county, product, and sales volume.

### 2. **Data Cleaning and Validation**
   - Checked for missing or inconsistent values.
   - Applied data validation to ensure accurate entries and consistency.

### 3. **Pivot Table Analysis**
   - Created PivotTables summarizing sales data by county and product categories.
   - Analyzed performance trends and patterns.

### 4. **Categorization Using SWITCH Function**
   - Added a column categorizing sales into:
     - **High**: Sales > 600
     - **Medium**: Sales between 300 and 600
     - **Low**: Sales < 300
   - Automated categorization for all rows in the dataset.

### 5. **Data Analysis Using Excel Functions**
   - Applied:
     - `SUM` to calculate total commissions.
     - `AVERAGE` to determine average sales.
     - `VLOOKUP`/`XLOOKUP` for efficient data retrieval.

---

## 📊 **Sample Visualizations**
###Extracted Date Components from Data Column 📊
## Visualization:
![image](https://github.com/user-attachments/assets/3c5765ef-5975-4f22-b21b-44cfeb8c67c6)

### sorting, filtering, and analysis of transaction details.  
## Visualization:
![image](https://github.com/user-attachments/assets/0ed8272f-ccc8-4ca9-818f-00de9807b455)

### Commission Total Using Excel SUM Function 💹
In this table, the **SUM** function was used to calculate the total commission for the year 2023, displaying the result in cell **L10**.
## Visualization:
![image](https://github.com/user-attachments/assets/812ec98f-8bc8-4ff6-a4d5-1dae48852e3d)

### Average Commission Using Excel AVERAGE Function 📊
In this table, the **AVERAGE** function was used to calculate the average commission for the year 2023, with the result displayed in cell **L11**.
## Visualization:
![Average Commission](path_to_your_image_file_in_repo.png)

### Aggregate Functions for Sales Data Analysis 📊
In this analysis, key aggregate functions were applied to the sales dataset to summarize and derive insights from the data.
- **SUM**: Calculated the total commission for the dataset, resulting in **£6,840.00**.
- **AVERAGE**: Determined the average commission value, which is **£6.84**.
- **MIN**: Found the lowest commission value, **£0.38**.
- **MAX**: Identified the highest commission value, **£30.00**.
- **COUNT**: Counted the total transactions, reaching **1,000** entries.
- **SUMIFS**: Applied conditional summation for specific product categories like Beauty, Clothing, and Electronics.
- **AVERAGEIFS**: Calculated the average for filtered data subsets.
- **COUNTIFS**: Counted entries meeting specific conditions for each category.
## Visualization:
![Aggregate Functions](path_to_your_image_file_in_repo.png)

### VLOOKUP and XLOOKUP Functions for Data Retrieval 🔍
This analysis utilized the **VLOOKUP** and **XLOOKUP** functions in Excel to retrieve and analyze sales data effectively.
## Visualization:
![VLOOKUP and XLOOKUP Functions](path_to_your_image_file_in_repo.png)

### Concatenation and Data Validation 🎯
This analysis employed the **CONCATENATE** function for combining strings and **Data Validation** for controlled inputs in Excel.
### Visualization:
![Concatenation and Data Validation](path_to_your_image_file_in_repo.png)


## Categorization and Data Summary 📊
This step categorizes products based on sales volume and summarizes the data using a pivot table.
- **SWITCH Function**:
  - Added a new column categorizing sales as "High," "Medium," or "Low" based on sales volume thresholds.
  - Example Formula: `=SWITCH(TRUE, [Sales Volume]>=600, "High", [Sales Volume]>=300, "Medium", "Low")`.
- **Pivot Table**:
  - Summarized data by county (rows) and product types (columns).
  - Sales Volume used as the aggregated value.
### Visualization:
![image](https://github.com/user-attachments/assets/b6a76ea6-9df6-45cf-bcd2-4de1d434e277)



## 💡 **Impact**
This project strengthened skills in **Excel-based data analysis**, advanced functions, and data visualization. It demonstrated the ability to extract actionable insights and support decision-making through structured analysis.



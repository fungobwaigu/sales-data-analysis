# Sales Data Cleaning and Regional Analysis  
*A Data Analytics Project by Fungo Bwaigu*  

## Overview  
This project demonstrates a structured approach to cleaning and analyzing sales data to derive actionable insights. 
The dataset, initially fraught with duplicates, invalid entries, and missing values, was rigorously processed
 to ensure accuracy and reliability for downstream analysis.  

---

## Project Objectives  
1. **Remove Duplicate IDs**: Ensure each entry is uniquely identified.  
2. **Handle Invalid Values**: Eliminate rows with infinite ("inf") entries in the Price Per Unit column.  
3. **Regional Sales Analysis**: Calculate total quantity sold and total sales value (Quantity × Price Per Unit) per region.  

---

## Data Cleaning Process  
1. **Removed Duplicate IDs**:  
   - 3 duplicates removed using Excel’s "Remove Duplicates" tool.  
2. **Filtered Infinite Values**:  
   - Excluded rows with "inf" in the Price Per Unit column.  
3. **Addressed Missing/Invalid Regions**:  
   - Removed entries with missing regions (ID 14) and invalid regions ("Asgard" for IDs 25 & 26).  
4. **Added Calculated Fields**:  
   - Created a "Value" column (`= Quantity * Price Per Unit`) for total sales calculations.  

---

## Repository Structure 

sales-data-analysis/
	Assets > Screenshots > data-cleaning.png; cleaned-data.png; regional-summary.png		
├── Original_Data >  Original_Data.xlsx : Raw dataset preserved for reference. 
├── Solution > Cleaned_Data_and_Report.xlsx(4 sheets - Raw_Data, Data_Instructions,Working_Sheet, Solution_Sheet )  
└── README.md Documentation of methodology and insights.
  

---

## Insights  
- Generated a summary table of **total quantity sold** and **total sales value** per region.  
- The South Region had the highest and sales value, accounting for 39% of Total Revenue. 
- The North had the least sales and Revenue. 

---


## Skills Applied  
- **Data Cleaning**: Duplicate removal, handling missing/invalid data.  
- **Excel Proficiency**: Filters, formulas, tables.  
- **Exploratory Data Analysis (EDA)**: Aggregation, summarization.  
- **Data Validation**: Ensuring consistency in Regions fields .  
- **Reporting**: Clear documentation of processes and outcomes.  

---

## Acknowledgments  
This *mini_project* was completed as part of the **3MTT Data Analytics and Visualization Fellowship**,
 aimed at building practical data skills for real-world applications.  

---

*For questions or feedback, contact https://www.linkedin.com/in/fungobe/.*  

---  

**🔍 follow the this link *https://tinyurl.com/ycp3pynx*  view the cleaned dataset, summary table, and full report! in google sheets**  


  
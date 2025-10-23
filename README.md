# Retail-sales-and-customer-analysis
RETAIL SALES AND CUSTOMER ANALYSIS
Project Name: Retail Sales Date Dashboard                                                                                    
Student Name: Joseph Kwame Ofori                                                                                             
Date: October 23,2025                                                                                                                     
Instructor: Francisca                                                                                                      


 
Executive Summary
The purpose of this analysis is to provide actionable insights into the revenue performance of various product categories and to understand customer demographics in relation to revenue generation. The dataset includes key fields such as Date, Transaction ID, Gender, Age, Customer ID, Quantity, and Revenue.
Comprehensive data cleaning was performed to eliminate duplicates, blank entries, and errors, ensuring data accuracy and consistency. A structured data table was then created, with an additional column to categorize Age into three groups: Youth, Young Adult, and Adult.
Three pivot tables were developed to analyze:
•	Revenue by product category
•	Revenue by gender
•	Revenue by age group
To conclude, an interactive dashboard was designed to visualize the findings and effectively communicate the insights derived from the analysis.


Introduction
The objective of this project is to analyze retail sales data for the year to determine which product category generated the highest revenue, and to understand the customer dynamics and demographics that influenced sales performance.
This analysis aims to transform raw data into meaningful insights that can guide decision-making, enhance marketing strategies, and improve overall business performance.


Data Understanding
The data is a retail sales data sets from a retail shops for the year.The data was in excel format and has 1000 transactions with nine key fields. The fields include;
•	Date
•	Transaction number
•	Customer ID
•	Gender
•	Age
•	Product Category
•	Quantity
•	Price per unit
•	Total Amount

Methodology
A comprehensive data cleaning process was conducted to remove duplicates, correct formatting issues, and fill in missing values. The following steps were applied:
•	The autofit function was used to adjust all column headings for clarity, with font size increased to 14 and bolded.
•	The Remove Duplicates feature was applied to ensure data integrity.
•	The Find and Replace (Ctrl + G → Special) function was used to identify and remove blank spaces.
•	The cleaned data was formatted into an Excel table for easier analysis.
To achieve the project’s objective of identifying top-performing products and understanding customer demographics, a descriptive analysis approach was adopted.
Three pivot tables were created to analyze:
•	Total revenue by product category
•	Total revenue by gender
•	Total revenue by age group
Two types of charts were developed for visualization:
•	Bar Chart: To display revenue by product category and by age group.
•	Doughnut (Pie) Chart: To show revenue distribution by gender.
Additionally, four Excel formulas were used during analysis:
•	DATE function — to extract year, month, and day:
=DATE(year, month, day)
•	IF(AND) function — to categorize ages into groups:
=IF(AND(E2>=18,E2<=29),"Youth",IF(AND(E2>=30,E2<=49),"Young Adult",IF(AND(E2>=50,E2<=64),"Adult","")))
•	AVERAGE function — to calculate average values.
•	Multiplication formula — to calculate revenue:
=Quantity * Price per Unit
Finally, an interactive dashboard was created using rectangular shapes and cards to display:
•	Total Revenue
•	Total Stock Sold
•	Number of Transactions
•	Average Customer Age
Three charts (by product, gender, and age group) were inserted into the dashboard, with gridlines and unnecessary labels removed. Customized colors were applied for clear data visualization.
 
Findings
1. Revenue by Product Category
•	Electronics generated the highest revenue of GHS 156,905 (34.40%).
•	Clothing followed closely with GHS 155,580 (34.11%).
•	Beauty products generated the least revenue of GHS 143,515 (31.47%).
2. Revenue by Gender
•	Female customers contributed 51% of total revenue.
•	Male customers accounted for 49% of total revenue.
3. Revenue by Age Group
•	Young Adults generated the highest revenue — GHS 189,690 (41%).
•	Adults contributed GHS 143,155 (31.39%).
•	Youth generated GHS 123,155 (27%) of total revenue.
 
Recommendation
Based on the findings, the company should consider developing marketing strategies that target the Youth demographic, as they currently generate the least revenue.
This may include introducing products and promotions tailored to younger consumers, as well as youth-centered advertising campaigns to increase engagement and sales within this segment.
 
Conclusion
In conclusion, this analysis highlights that Electronics is the top-performing product category, and Young Adults represent the most profitable customer group. While the business performs well across all demographics, opportunities exist to expand market share among Youth customers through targeted marketing initiatives.
The findings from this analysis can help management make data-driven decisions regarding inventory planning, product promotion, and customer segmentation, ultimately improving overall sales performance and profitability.
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
																	
<img width="1521" height="577" alt="image" src="https://github.com/user-attachments/assets/ba48dec4-3d55-431c-975e-f74f9ad704e5" />


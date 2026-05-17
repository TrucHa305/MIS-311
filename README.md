Exploratory Data Analysis (EDA) – Electric Vehicle Dataset
1.	Data Overview
This analysis is conducted using the dataset that includes information on electric vehicles (EVs). The data contains vehicle identification numbers, city location, postal code, model year, manufacturer and model. The dataset seems to be about the number of EV cars registered in various cities.
•	Number of rows: 190
•	Number of columns: 6
•	Source of data: Electric Vehicle dataset provided for analysis
Variables Included
Variable                               	 Description
Vehicle Identification Number (object) 	 Unique identifier of the vehicle
City (object)	                           The city where the vehicle is registered
Postal code (object)                     The postal code associated with the vehicle's registration                                            address
Model year (int)                         The year the vehicle model was manufactured
Make (object)                            Manufacturer’s name
Model (object)                           The specific model of the vehicle

2. Data Cleaning
Data quality was enhanced by cleaning the data in Power Query in Excel before analysis.

Missing Values
The data set was identified as having blank cells and missing values. To ensure consistency and accuracy of the analysis, records with missing values were removed using Power Query.

Duplicate Rows
The ‘Remove Duplicates’ function in Power Query was used to identify and remove duplicate rows. This procedure enabled no more than one record to be repeated, thus avoiding its influencing the descriptive statistics and visual analysis.

Additional Cleaning
Also, data was formatted and consistency checks were performed to verify that variables like Model Year and Postal Code were correctly formatted for analysis.

3. Descriptive Statistics
Descriptive statistics were conducted to summarise the main characteristics of the electric vehicle dataset and identify important patterns and trends. The following two key insights were identified from the electric vehicle dataset.
3.1 Distribution of Electric Vehicles by Model Year
The following chart illustrates the number of electric vehicles based on their model year.
<img width="965" height="585" alt="image" src="https://github.com/user-attachments/assets/131978e0-e0b7-44a0-83a4-0155b9908cbf" />
Insight 1
The overall trend in the number of EVs generally rose over the past 5 years, reaching the peak count in 2020. This suggests that during this time period EV use has increased significantly, as there has been an increase in environmental awareness as well as technological progress in the EV industry. Also, the year-over-year drop in 2021 could indicate a change in market demand or missing data from recent years.
3.2 Distribution of Electric Vehicles by Manufacturer
The following bar chart shows the number of electric vehicles made by each of the companies in the data.
<img width="956" height="587" alt="image" src="https://github.com/user-attachments/assets/28a6328a-fba3-4c66-a648-2b96583fc1ed" />
Insight 2
Among the data, Tesla has the largest number of electric vehicles, suggesting that it dominates the electric vehicle market. This indicates that Tesla is a brand that consumers are very popular, likely because of its advanced technology, high brand recognition, and variety of EV models.
Also, the significant gap between Tesla and other manufacturers has shown the disparity in market share among EV brands. Although multiple companies are involved in the EV industry, several appear to be dominating the consumer market in this data set.

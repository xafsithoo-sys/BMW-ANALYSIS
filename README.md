# BMW Sales Data Analysis (2010-2024)

## Dataset Overview and Initial Data Inspection

This analysis is based on a dataset containing BMW sales information from 2010 to 2024. The dataset includes various attributes such as Model, Year, Region, Color, Fuel Type, Transmission, Engine Size, Mileage, Price, Sales Volume, and Sales Classification.

The data was loaded into a pandas DataFrame for analysis. Initial inspection revealed that the dataset contains 50,000 entries and 11 columns. The data types of the columns were checked, and it was confirmed that there are no missing values or duplicate rows in the dataset, ensuring data integrity for further analysis.

## Key Findings and Visualizations

Based on the analysis of the BMW sales data from 2010 to 2024, the following key findings were observed:

*   **Correlation Matrix:** The correlation matrix of the numerical columns (Year, Engine_Size_L, Mileage_KM, Price_USD, Sales_Volume) showed very weak correlations between all pairs of variables. This suggests that there is no significant linear relationship between these numerical attributes in the dataset.

*   **BMW Sales Over Time (2010–2024):** The line plot showing the total number of BMW vehicles sold each year from 2010 to 2024 indicates fluctuations in sales volume over this period. While there isn't a clear upward or downward trend, there are noticeable peaks and dips in certain years, suggesting variability in sales performance year-on-year.

*   **Top-Selling BMW Model by Year and Model Sales Heatmap:** The bar plot highlighting the top-selling BMW model for each year reveals that the most popular model varied from year to year, including models like the i3, M5, 5 Series, 7 Series, X1, and X6. The heatmap provides a more comprehensive view of sales volume for each model across all years, illustrating the relative popularity and sales trends of different models over time.

*   **Electric vs. Hybrid Sales Volume:** The comparison of total sales volume between electric and hybrid cars shows that hybrid cars had a slightly higher cumulative sales volume (64,532,097) compared to electric cars (63,157,665) over the analyzed period.

*   **Average BMW Sale Price Over Time (2010–2024):** The line plot illustrating the average sale price of BMW vehicles over the years shows that the average price has remained relatively stable between 2010 and 2024, hovering around $75,000 USD with minor fluctuations. There is no strong increasing or decreasing trend in the average price.

*   **Top-Selling BMW Model per Region:** The analysis of top-selling models by region shows that the most popular models vary across different geographical areas. For instance, the 5 Series was the top seller in Africa, the X1 in Asia, the i8 in Europe and South America, and the 7 Series in the Middle East and North America. The bar plot visually represents these regional preferences.

*   **Sales Classification Distribution:** The `sales_classification_counts` series indicates that a larger proportion of sales fall into the "Low" sales classification (34,754) compared to the "High" classification (15,246).

*   **Fuel Type Adoption Trends:** The `fuel_type_adoption` DataFrame shows the number of cars sold for each fuel type (Diesel, Electric, Hybrid, Petrol) across the years. The data suggests that sales for all fuel types have remained relatively consistent over the years, without a dramatic shift towards one specific fuel type.

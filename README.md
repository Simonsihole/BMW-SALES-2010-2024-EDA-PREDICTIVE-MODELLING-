## Summary:

### Data Analysis Key Findings

*   Overall Sales Trend: The total sales volume of BMW cars over the years   (2010-2024) shows fluctuations, with notable peaks and dips, 2022 has the highest sales volume.

*   Sales by Model: The total sales volume is relatively evenly distributed across different BMW models in this dataset, with no single model significantly outselling the others.

*   Sales by Region: The distribution of total sales volume by region is also quite balanced, with each of the listed regions contributing a similar percentage to the total sales.

*   Sales Trends by Region Over Time: While overall sales fluctuate, the trends within each region show some variations over the years. Some regions might experience peaks or dips in certain years that differ from the global trend.
*   Relationship with Price and Mileage: The correlation analysis and scatter plots suggest that there is a very weak or no linear relationship between Sales 

*   Volume and Price (USD) or Mileage (KM) in this dataset. This means that changes in price or mileage do not appear to have a strong direct linear impact on sales volume based on this data.

*   **Categorical Features:** Sales volume is relatively evenly distributed across different Fuel Types (Diesel, Electric, Hybrid, Petrol), Transmission types (Automatic, Manual), and Colors. No single category in these features significantly dominates sales.
*   **Engineered Feature (Car_Age):** A new feature, 'Car\_Age', was created. Visualizing 'Car\_Age' against 'Sales\_Volume' did not show a clear linear or non-linear pattern.
*   **Non-linear Relationships:** Scatter plots of 'Car\_Age' and 'Engine\_Size\_L' against 'Sales\_Volume', along with previous correlation analysis, did not reveal strong non-linear relationships between these or other numerical variables ('Price\_USD', 'Mileage\_KM') and 'Sales\_Volume'.

### Insights or Next Steps

*   The lack of strong linear or non-linear relationships identified suggests that other factors or more complex interactions might be driving sales volume.
*   Further analysis could involve exploring interactions between features or applying more advanced modeling techniques to uncover potential complex relationships not visible through simple visualizations.

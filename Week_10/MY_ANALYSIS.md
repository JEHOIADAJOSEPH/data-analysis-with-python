Problems found:
1. inner join loses data
2. incorrect calculation of total price
3. invalid quantities and unit costs
4. missing product information
5. average sale value calculated instead of total
6. incorrect bar chart parameters
7. no monthly representation for total sales value

Solutions:
1. use left join to preserve
2. multiply cost by quantity instead of adding
3. drop invalid quantities from table
4. drop records with missing product information as specified
5. calculate total sales
6. change parameters to fit title
7. create line plot for total monthly sales value

Impact:
The dataset became easier to understand and logical errors were corrected.

Insights:
The regional analysis revealed that the North had the highest total sale value, while the West had the lowest total sale value.

The time-series analysis revealed that the highest total sale value was achieved in July, and the lowest total sale value in was achieved in October.

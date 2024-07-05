# Challenge 5 - Athletic sales analysis
--------------
## Overview and agenda for analysis
1. Import dependencies
- pandas
  - Used for all data related tasks (ex. data manipulation)
2. Combine and clean the data
- Import CSVs
  - Display 2020 and 2021 sales DF
- Check data types of each DF
- Combine the sales data by row
- Check for null values
- Convert necessary columns to DateTime format
  - Confirm the change
3. Determine which region sold the most products
- Using groupby and/or pivot table
  - Show the number of products sold for region, state, and city
  - Rename and necessary columns
  - Show results
4. Determine which region had the most sales
- Using groupby and/or pivot table
  - Show the total sales for the number of products sold for region, state, and city
  - Rename any necessary columns
  - Show results
5. Determine which retailer had the most sales
- Using groupby and/or pivot table
  - Group the data by retailer, region, state, and city and calculate the sum of total_sales
  - Rename any necessary columns
  - Sort the DataFrame by Total_sales in descending order
  - Show results
6. Determine which retailer sold the most Women's athletic footwear
- Filter the sales data to get the women's athletic footwear sales data
- Using groupby and/or pivot table
  - Show the total number of women's athletic footwear sold for each retailer, region, state, and city
  - Rename any necessary columns
  - Show results
7. Determine the day with the most women's athletic footwear sales
- Create a pivot table with the invoice-date columns as the index and the total_sales as the values
- Rename any necessary columns
- Show the table
- Resample the pivot table into daily bins, and get the total sales for each day
- Sort the resampled pivot table in descending order on Total_sales
8. Determine the week with the most women's athletic footwear sales
- Resample the pivot table into weekly bins and get the Total_sales for each week
- Sort the resampled pivot table in descending order on Total_sales
---------
### Additional sources
#### Sources like ChatGPT, Xpert Learning Assistant, AskBCS, YouTube, and Columbia provided tutoring were used for clarification and debugging if/where needed.

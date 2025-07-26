Assumptions													
The dataset primarily contains Airbnb listings in the Manhattan vacation rental market.													
The vast majority of listings are for Entire home/apt room types.													
													
													
Change Log													
version 1.1 – Cleaned the neighborhood column labels. Removed inconsistent capitalization and trailing spaces. Stored clean values in a separate column called neighborhood_clean													
													
version 1.2 – Added pivot table and bar chart to summarize top of 10 neighborhoods are most attractive for vacation rentals													
version 1.3 – Cleaned the bedrooms column of any empty cells (the empty cells represent listings with zero bedrooms (studio apartments)). Stored the clean values in a new column called bedrooms_clean. Used the IF function for this.													
													
version 1.4 – Added pivot table to determine the number of bedrooms that are most popular for rentals.													
version 1.5 –Updated the pivot table, to be ab recommend specific property sizes for each of the top 10 neighborhoods.													
version 1.6 – Added a new column in listings called top_listing that has a value of 1 if a listing matches these criteria, else 0. Used the function =IF(OR(AND(													
version 1.7 – Added a new column to the processed calendar data called revenue_earned, representing the revenue earned each night. If available is "f" (indicating the property was rented), set revenue_earned to the adjusted_price; otherwise, set it to $0.													
													
version 1.8 –Created a new column on the Processed Data sheet also called revenue_earned. Used the SUMIF() function to bring over the total revenue_earned from the 30-day calendar data													
version 1.9 – Added pivot table that orders all our top listings according to revenue. Used top_listing as a filter													
version 1.10 –Created a new column on the Processed Data sheet called annual_revenue_earned. Used the revenue_earned column * 12 months.													
version 1.11 – Added pivot table to determine the average price of the 3 most popular sized property listings													
version 1.12– Added pivot table to determine the prices range from a minimum to a maximum													
version 1.13– Added pivot table to determine the revenue_earned (30 days) and the annual_revenue_earned for the top 10 neighborhoods and the count of the properties of the neighborhoods.	

<img width="2094" height="1098" alt="image" src="https://github.com/user-attachments/assets/29881283-e949-4807-b1a2-529f7cc99530" />

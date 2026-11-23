# data-analysis-project-using_seaborn_pandas_matplotlib

Zomato Exploratory Data Analysis (EDA)

Project Overview
This project explores a Zomato restaurant dataset using Python to analyze restaurant categories, customer votes, ratings, online-ordering availability, table booking, and approximate cost for two people. Pandas is used for data preparation and summaries, while Matplotlib and Seaborn are used for visualizations.

Objectives
- Inspect the dataset structure and summary statistics.
- Prepare ratings and column names for analysis.
- Check missing values and duplicate records.
- Compare restaurant types by votes, count, average rating, and estimated cost.
- Explore ratings in relation to votes and online ordering.
- 
Tools and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- 
Dataset
The dataset contains 148 restaurant records and 7 columns:
Column	Description
Restaurant Name	Restaurant name
Online_Order	Online-order availability
Book_Table	Table-booking availability
Rate	Restaurant rating (initially in x/5 format)
Votes	Number of customer votes
Approx_Cost(For Two People)	Approximate cost for two people
Listed_In(Type)	Restaurant category


Data Cleaning
- Converted ratings from x/5 text format to numeric values.
- Standardized column names to lowercase.
- Renamed the approximate-cost column to approx_cost.
- Checked for missing values and duplicate records.
- The report found no missing values and no fully duplicated rows.

  
Exploratory Data Analysis
The project investigates these questions:
1. How many customer votes has each restaurant type received?
2. How many restaurants offer table booking?
3. Which five restaurants have the highest number of votes?
4. Is there a relationship between restaurant ratings and customer votes?
5. What is the average rating for each restaurant type?
6. Which restaurant type is most common in the dataset?
7. What ratings do restaurants most commonly receive?
8. Which restaurant type has the highest average cost for two people?
9. Do restaurants offering online ordering have higher ratings?
10. Which restaurant types have more records without online ordering?


Key Findings
- Dining restaurants account for 74.3% (110 of 148) of the records.
- Dining restaurants received the highest total votes, with 20,363.
- Table booking is available in 8 records (5.4%); 140 records (94.6%) do not offer it.
- Empire Restaurant has the highest vote count (4,884), followed by Meghana Foods (4,401).
- Ratings and votes show a moderate positive correlation (approximately 0.49).
- The other category has the highest average rating (approximately 3.91).
- The most frequently occurring rating is 3.8; the overall average rating is approximately 3.63.
- Buffet restaurants have the highest average approximate cost for two (671.43).
- Restaurants with online ordering have a higher average rating (3.86) than those without online ordering (3.49).
- Dining has the most records without online ordering (77).


Conclusion
The analysis shows that Dining is the largest restaurant category and has the highest total votes, while Buffet has the highest average approximate cost for two. The other category has the highest mean rating, though it contains relatively few records. Table booking is uncommon, and online-ordering availability is associated with higher ratings in this sample. These findings describe the 148 records in the supplied dataset and should not be generalized to all Zomato restaurants.



#author
meshva

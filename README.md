# Pandas
This contains 2 folders 
1. Heroes of PyMoli
   - Contain pymoli.ipynb file, a doc file with data analysis and related CSV file.
2. PyCity Schools
   - Contain pyschools.ipynb file, a doc file with data analysis and related CSV files.
    README.md
PyCity Schools Introduction
For this report, a data set of district wide standardized test results was analyzed to search for trends or actionable insights with the goal of approving student success overall.

Overview of the Data
The analyzed data set includes information on 15 highschools with a total of 39,170 students. Parameters included are budget per school, student names & IDs, math & reading scores and school size. Below is a high level summary for the entire District.

District Summary
Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing Rate
0	15	39,170	$24,649,428.00	78.98	81.87	74.98%	85.81%	80.43%
Methods
Jupyter notebooks with the pandas python library was used to merge, parse and aggregate the data. (see 'PyCity Schools.ipynb')

Analysis
The data was first grouped by school to find total students, per student budget, average scores and school population passing rate for both math and reading.

Results of Analysis
Charter schools were observed to have higher scores than district schools. When all schools are ranked, places 1-8 are occupied by Charter Schools and places 9-15 are occupied by District Schools. (Top Performing Schools)

Per student spending did not correlate with higher scores, in fact the data shows the opposite to be true with schools spending less than $615 per student achieving a 95% passing rate, schools spending $615-$645 per student find passing rates drop to 80% and schools in the highest bracket of spending suffering a further drop in passing rates to 74%. (Scores by School Spending)

Both school size and school type were shown to have an effect on student math and reading scores. Schools with less than 2000 students have an average 95% passing rate while schools above 2000 students average only 76% passing rate. This trend is especially pronounced in math scores, with above and below 2000 students showing 93.5% and 70% passing rate, respectively. Charter schools had an overall passing rate of 95% while District schools show only a 73% passing rate. Again this is most dramatic in math scores with a 93.5% passing rate for Charter schools and 66.5% passing rate for District schools. (Scores by School Size/Type)

Conclusions
This analysis suggests that the District should invest in building more schools to reduce number of students per school, as increasing a school's budget alone has not been shown to increase math or reading scores.

More analysis should be done on differences between Charter and District schools so that the District schools can identify changes to be implemented so that Charter school success can be emulated.

LIMITATIONS:
1. The data set specifically relies on math and reading scores but completely ignored or limited to science/other scores. If most of the students from district schools are science champions, overall performance rates could change to prove our current analysis wrong.
2. Also, we know that all District schools are large sized, it could be highly possible that these schools provide a wide range of many other courses in Arts (which holds many sub category courses), Technology etc. In this case district schools could be performing well with all scores included.



Heroes of Pymoli Introduction
With free to play games such as Heroes of Pymoli, in game purchases are an important source of revenue. This analysis is intended to identify action steps to both increase profitability and improve user experience.

Overview of the Data
The data set analyzed is a total of 780 purchases that included age and gender demographics for the purchasers as well as price, item ID and item name for the purchased items.

Methods
Jupyter notebooks with the pandas python library was used to parse and aggregate the data.

Analysis
The data was grouped by sign name to identify the number of unique players making purchases. Next a high level summary of total items, purchases and average price per item was done as a starting point.

Item Overview
Number of Unique Items	Average Price	Number of Purchases	Total Revenue
0	183	$3.05	780	$2,379.77
Sign names were next grouped by age and gender an analyze trends in purchase count, average purchase price, total purchase value and average purchase per person for each demographic.

Results of Analysis
This dataset was comprised of 780 purchases made by 576 unique players. Of the 576 players, 84% identified as male, 14% as female and 2% were other or non-disclosed. (Gender Demographics)

When reviewing purchases by gender it can be observed that while purchase counts were proportionate to the share of the population(84% male, 14% female and 2% other), females and non-disclosed players tended to purchase higher priced items and have a higher average purchase per player than the male players. (Purchasing Analysis(Gender))

The peak age demographic for Heroes of Pymoli is 15-29 with ages 20-24 representing approximately 45% of players and revenue and ages 15-29 representing approximately 75%. (Age Demographics and Purchasing Analysis)

A review of top spenders shows that no single player spent over $20 within this dataset. (Top Spenders)

Conclusions
This analysis suggests that a key part of revenue generation is having a wide range of players and items available to purchase. This is because players are not found to spend a great deal of money individually. Recruitment of new players should be focused on males aged 15-29 but in a way designed not to exclude females from becoming interested. While males are more likely have a larger total purchase, females appear to be drawn to higher priced items which can drive profitability.

	Limitations
•	Though we are notified that the game Heroes of Pymoli is a most recent game, the data set is limited to providing the details on how many months/weeks of dataset we are analyzing. If the dates of purchase were included, it could have been helpful to analyze effectively.
•	And in case, we are analyzing data of very short span, our analysis could go wrong with the addition of more data. So, it is important to know if we are doing an early analysis on the limited set of data.

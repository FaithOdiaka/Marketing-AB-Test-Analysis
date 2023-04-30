# Marketing-AB-Test-Analysis
This project analyzes the effectiveness of two different marketing strategies, A and B, using A/B testing techniques in Python. By conducting a hypothesis test on sales data from two groups of randomly selected customers, we determine which marketing strategy is more effective and provide a recommendation to the marketing firm.


Working with a marketing firm that was trying to determine the best marketing strategy to increase sales. The firm had two different marketing strategies, A and B, and wanted to know which one was more effective. They randomly selected a sample of customers and divided them into two groups: Group A, who received marketing strategy A, and Group B, who received marketing strategy B. The firm tracked the sales for each group over a period of time and wanted to analyze the data to determine which strategy was more effective.

To approach this problem, i used Python to conduct a hypothesis test on the data. First calculating the numerical description of each group. I then assumed that the null hypothesis was that there was no difference in the effectiveness of the two marketing strategies, and the alternative hypothesis was that there was a significant difference.

Based on This analysis, I was able to provide the marketing firm with a recommendation on which strategy to use, backed up by statistical evidence.


* STEPS INVOLVED

Imported relevant modules for data analysis and visualization

Read and checked the data from control_group.csv and test_group.csv files

Filled missing values in the control_data using the mean value of each column

Merged the control_data and test_data datasets using outer join

Plotted scatter plots to compare different marketing strategies based on various metrics such as Number_of_impressions, Purchases, Content_Viewed, Website_Clicks, etc.

Created pie charts to compare total searches, content viewed, amount spent, and purchases from control and test campaigns.

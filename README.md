# Megaline Phone Plans Project

You work as an analyst for the telecom operator Megaline. The company offers its clients two prepaid plans, Surf and Ultimate. The commercial department wants to know which of the plans brings in more revenue in order to adjust the advertising budget. Carry out a preliminary analysis of the plans based on a relatively small client selection. You'll have the data on 500 Megaline clients: who the clients are, where they're from, which plan they use, and the number of calls they made and text messages they sent in 2018. Your job is to analyze clients' behavior and determine which prepaid plan brings in more revenue. 

For this project you will have to complete the following tasks:
1. **Data Import & Inspection**  
   - Import the five datasets (`calls`, `internet`, `messages`, `plans`, `users`) and review their structures. This initial step helps confirm rows, columns, and missing values.

2. **Standardize the Data**  
   - Rename and format columns as necessary; Convert string dates to datetime objects for analysis.
   - Extract 'month' and create a new column wherever applicable. 

3. **Merging & Aggregating**
   - Aggregate per user-month for total calls and total minutes.
   - Aggregate per user-month for total messages.
   - Aggregate MB usage per user-month, then converted to total GB usage.
   - Merge all usage data into a master dataset for both plans


4. **Calculating Monthly Revenue**
   - Compute extra usage for minutes, messages, and data, clipping below zero for usage within plan limits.
   - Compure Overage Costs by calculating the the per-unit cost
   - Compute Total Cost for plan profitability comparisons.

5. **Exploratory Data Analysis** 
   - Plot distributions comparing average monthly call durations, messages, internet usage and revenue per plan. Explain your results.
   - Plot the distributions and explain your results.

6. **Conclusions & Recommendations**
   - Present Key Findings
   - Conduct Hypothesis testing
   - Acknowledge any Regional Differences

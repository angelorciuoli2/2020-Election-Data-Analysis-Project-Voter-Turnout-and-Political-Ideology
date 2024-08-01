# 2020 Election Data Analysis Project: Voter Turnout and Political Ideology

# 1. Voter Turnout Analysis


### Project Description


This project involves analyzing voter registration and participation patterns using data from the Current Population Survey (CPS) Voting and Registration Supplement and the Cooperative Election Study (CES) 2020 extract. The objective is to understand the factors influencing voter turnout and registration, particularly focusing on the discrepancies between different age groups and the self-reported versus validated voting behavior.

### Objective


The primary objectives of this project are to:

1. Identify the key variables that determine if an individual voted or was registered to vote.
2. Calculate the percentage of adults and adult citizens who voted in the 2020 election.
3. Analyze how voter turnout varies by age.
4. Examine discrepancies between self-reported voting behavior and validated voting data.
5. Calculate different measures of voter turnout.
6. Provide recommendations to an organization aiming to increase voter turnout among younger voters based on the analysis.



### Summary of Results


Step 1: Identifying Voter Registration and Participation


• Combined variables from the CPS to create a new variable representing registered voters accurately.

• Verified consistency in responses to exclude logically inconsistent data.


Step 2: Calculating Voter Participation Percentages


• Used the weight variable to calculate the percentage of all adults and adult citizens who voted in the 2020 election.

• Compared results with the Census Bureau's summary document table04c.xlsx.


Step 3: Calculating Voter Registration Percentages


• Calculated the percentages of all adults and adult citizens who were registered to vote.

• Confirmed results with the Census Bureau's summary document.


Step 4: Analyzing Voter Turnout by Age


• Produced graphs showing voter turnout variation across different age groups.

• Found that younger voters had lower turnout compared to older voters.


Step 5: Creating a Binary Voting Variable


• Created a binary variable indicating whether individuals reported voting in 2020.

• Calculated the percentage of individuals who reported voting.


Step 6: Comparing Reported Voting to Validated Voting

• Compared self-reported voting data to validated voter file data.

• Identified discrepancies between self-reported voting and validated voting behavior.


Step 7: Calculating Turnout Measures


• Calculated three different measures of voter turnout.


• Examined the differences in turnout rates based on various methodologies.


Step 8: North Carolina Voter Analysis


• Analyzed North Carolina State Board of Elections data to calculate the total number of voters in the 2020 election.

• Calculated turnout using the Citizen Voting Age Population from the 2020 American Community Survey.


Step 9: Comparing Turnout Rates Across Surveys


• Compared voter turnout rates in North Carolina from the voter file, CPS, and CES.

• Found higher turnout rates in academic surveys like the CES compared to official records.


Step 10: Recommendations for Increasing Voter Turnout Among Younger Voters


• Identified that younger voters often cited 'lack of interest' or 'feeling of insignificance' as reasons for not voting.

• Recommended strategies such as increasing accessibility, running awareness campaigns, simplifying registration, and engaging with technology to increase voter turnout among younger voters.


### Main Analysis

The main analysis is detailed in the accompanying Jupyter Notebook (Voter_Turnout_Analysis.ipynb). This notebook contains all the data processing, calculations, and visualizations used to derive the results and insights summarized above.


# 2. Political Ideology and Politician Assessment Analysis


### Project Description


This project explores the relationship between individuals' self-assessed political ideology and their assessments of politicians' ideologies using data from the 2020 Cooperative Election Study (CES). The goal is to understand how personal ideology influences perceptions of political figures and entities.

### Objective


The primary objectives of this project are to:

1. Visualize the distribution of self-assessed political ideology.
2. Analyze respondents’ ideological ratings of Joe Biden and Donald Trump.
3. Explore the relationship between personal ideology and the perceived ideology of these politicians.
4. Compare the evaluations of Biden and Trump and understand the differences in perceptions.
5. Examine the ideological ratings of other political entities.
6. Provide insights into how self-assessed ideology influences political perceptions.



### Summary of Results


Step 1: Visualizing Self-Assessed Ideology


• Loaded the CES data and visualized the distribution of self-assessed political ideology.


• Found that the most common response was identifying as middle of the political spectrum, while extreme ideologies were less common.


Step 2: Analyzing Ideological Ratings of Biden and Trump


• Created plots showing the distribution of respondents' ideological ratings of Joe Biden and Donald Trump.


• Visualized how respondents perceived the ideologies of these politicians.


Step 3: Predicting Biden’s Ideology Rating


• Performed a linear regression analysis with Biden's ideology rating as the dependent variable and self-assessed ideology as the independent variable.

• Found that individuals’ ratings of Biden's ideology became more liberal as their own ideology became more conservative.


Step 4: Predicting Trump’s Ideology Rating


• Conducted a linear regression analysis with Trump's ideology rating as the dependent variable and self-assessed ideology as the independent variable.

• Found that individuals’ ratings of Trump’s ideology became more conservative as their own ideology became more liberal.


Step 5: Comparing Evaluations of Biden and Trump


• Compared the intercepts and coefficients of the linear regressions for Biden and Trump.

• Observed that respondents tend to view opposing party figures as more extreme, with significant differences in how Biden and Trump are perceived.


Step 6: Analyzing Ideological Ratings of Other Entities

• Chose a variable from the CES data (e.g., GOP ideology rating) and visualized the relationship between self-assessed ideology and the rating of this entity.

• Performed a linear regression and interpreted the results, finding similar trends where personal ideology influenced perceptions of political entities.


### Main Analysis

The main analysis is detailed in the accompanying Jupyter Notebook (Political_Ideology_Analysis.ipynb). This notebook contains all the data processing, visualizations, and statistical analyses used to derive the results and insights summarized above.





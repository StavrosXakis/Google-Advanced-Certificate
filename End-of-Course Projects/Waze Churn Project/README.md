# End-of-Course Projects Waze dataset

## Project goal:   
Waze leadership has asked your data team to develop a machine learning model to predict user churn. Churn quantifies the number of users who have uninstalled the Waze app or stopped using the app. This project focuses on monthly user churn. An accurate model will help prevent churn, improve user retention, and grow Waze’s business.

## Background: 
Waze’s free navigation app makes it easier for drivers around the world to get to where they want to go. Waze’s community of map editors, beta testers, translators, partners, and users helps make each drive better and safer. 

## Jupyter Notebooks:
There is one Jupyter Notebook per Module. In each module, we develop our project according to the milestones outlined at the project proposal I conducted in Module 1 (Foundations of Data Science). Inside the Jupyter Notebooks, you will find my coding in combination along with step-by-step annotations as well as my answers to several key questions of the procedure. At the end of each Jupyter Notebook, there are my conclusions and key insights with which the relevant stakeholders should be informed.

## Executive Summaries:  
There is one PDF file accompaning each Jupyter Notebook. This file contains an Executive Summary. An Executive Summary, is an one-page format document designed to respect teammates and stakeholders who may not have time to read and understand an entire report. There, I present briefly the project overview, the details and key insights of my findings, as well as the next steps that the project should proceed.

### Project per Module:

#### **`Get Started with Python (Module 2)`:**

**Module's Scenario:**  
"Your team is in the early stages of their user churn project. Your project proposal has been approved and your team has been given access to Waze’s user data. To get clear insights, the data must first be inspected, organized, and prepared for analysis."

**My assignment:**  
"You will build a dataframe for the churn data. After the dataframe is complete, you will organize the data for the process of exploratory data analysis, and update the team on your progress and insights."

**Procedure Summary:**  
For the cause of my analysis, I used the Libraries Pandas and NumPy. Firstly, I imported the provided data to a data frame for inspection. Then, I summarized my data reviewing the available data types, number of variables/observations, and summary statistics while I also checked for Null Values. As the next step, I isolated the data frame of the revealed null values to a second data frame and compared it with the initial trying to find the cause of the missing values. After dealing with null values, I continued by exploring my dataset with respect to my main  variable (label) which labels the users as retained or churned. Placed in the early stages of an analytical procedure, my goal was to explore the data, identify relationships between the available variables, and acknowledge the representative percentage of categorical variables, to understand the reasons that led a user to churn.

#### **`Go Beyond the Numbers Translate Data into Insights (Module 3)`:**

**Module's Scenario:**  
"Your team is still in the early stages of their user churn project. So far, you’ve completed a project proposal, and used Python to inspect and organize Waze’s user data. Now, the data is ready for exploratory data analysis (EDA) and further data visualization."

**My assignment:**  
"You will conduct exploratory data analysis on data for the churn project. You’ll also use tools to create visuals for an executive summary to help non-technical stakeholders engage and interact with the data."

**Procedure Summary:**  
For the cause of my analysis, I used the Libraries Pandas, NumPy, Matplotlib.pyplot, and Seaborn. The project's goal was to dive deeper into the dataset, apply EDA practices, and use visualizations that would help me to identify relationships between variables, and trends leading me to conclusions about what caused a user to churn. During my analysis, I mainly used box plots and histograms to examine the spread and distribution of important variables, highlight significant points of users' behavior, and spot data abnormalities. I also combined variables to examine relationship rules that would help me form the right questions for further analysis. Of course, I had to perform other coding actions such as creating additional KPIs, filtering out problematic values, as well as handling outliers.

#### **`The Power of Statistics (Module 4)`:**

**Module's Scenario:**  
"Your team is nearing the midpoint of their user churn project. So far, you’ve completed a project proposal, and used Python to analyze and visualize Waze’s user data. Now, leadership has a new request for your team: use hypothesis testing to analyze the relationship between mean amount of rides and device type."  

**My assignment:**  
"You will conduct hypothesis testing on the data for the churn data. The data team has asked you to investigate Waze's dataset to determine which hypothesis testing method best serves the data and the churn project."  

**Procedure Summary:**  
For the cause of my analysis, I used the Library Pandas and the module stats from SciPy. My analysis begins by computing the mean number of drives with respect to each device type. Computing descriptive statistics helps me quickly compare the average number of drives for the two samples (Android & iPhone users). Then, I begin the Hypothesis testing process to determine if the difference between the two population means is due to sample variability or if it is statistically significant. My goal is to conduct a two-sample t-test. Firstly, I state the null hypothesis. Secondly, I state a 95% significance level. Thirdly I compute the p-value and finally, according to my results, I fail to reject the null hypothesis meaning that the observed difference between the two sample means is indeed due to chance.

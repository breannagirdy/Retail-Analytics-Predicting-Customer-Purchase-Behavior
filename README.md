<h1 align=center>Retail Analytics: Predicting Customer Purchase Behavior</h1>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#SQL-Tasks">SQL Tasks</a></li>
    <li><a href="#Python-Tasks">Python Tasks</a></li>
    <li><a href="#Tableau-Tasks">Tableau Tasks</a></li>
    <li><a href="#Connect">Connect</a></li>
    <li><a href="#Conclusions">Conclusions</li>
  </ol>
</details>

# About the Project

In this project, I am a Data Analyst for RetailVC's Retail Analytics Solutions, an analytics firm that provides operational and customer solutions for retail businesses.

# SQL Tasks

<img width="706" height="553" alt="Screenshot 2026-07-15 at 7 36 37 PM" src="https://github.com/user-attachments/assets/7577fc96-9aed-42b2-8c4f-fc6f659acefe" />

<ul>
<li>Calculate the total number of customer encounters in the marketing campaign dataset.</li>
<li>Find the count of response values.</li>
<li>Determine the distribution of customers based on their education level and marital status.</li>
<li>Identify the average income of customers who participated in the marketing campaign.</li>
<li>Calculate the total number of promotions accepted by customers in each campaign.</li>
<li>Identify the distribution of customers' responses to the last campaign.</li>
<li>Calculate the average number of children and teenagers in customers' households.</li>
<li>Create an Age column by subtracting year_birth from the current year.</li>
<li>Create Age_group columns.</li>
<li>Determine the average number of visits per month for customers in each age group.</li>
</ul>


Click <a href="https://github.com/breannagirdy/Retail-Analytics-Predicting-Customer-Purchase-Behavior/blob/main/RetailAnalyticsCapstone.sql">here</a> to access the SQL query.

# Python Tasks

<img width="1049" height="638" alt="Screenshot 2026-07-15 at 7 50 21 PM" src="https://github.com/user-attachments/assets/e14c2f37-0822-471b-a734-a05cf1a08b59" />

<b>General Data Overview:</b>
<ul>
<li>Check the first few rows of the dataset to understand its structure.</li>
<li>Check the data types of each column.</li>
<li>Check for any missing values in the dataset.</li>
</ul>

<b>Descriptive Statistics:</b>
<ul>
<li>Compute summary statistics for numerical columns (mean, median, min, max, and standard deviation)/</li>
<li>Explore the distribution of numerical variables using histograms or box plots.</li>
</ul>

<b>Univariate Analysis:</b>

<ul>
<li>Explore the distribution of each numerical variable using histograms or kernel density plots.</li>
<li>Explore the distribution of each categorical variable using bar plots or pie charts.</li>
<li>Identify outliers in numerical variables using box plots or scatter plots.</li>
</ul>

<b>Bivariate Analysis:</b>
<ul>
<li>Explore the relationship between numerical variables and the target variable (Response) using scatter plots or correlation matrices.</li>
<li>Explore the relationship between categorical variables and the target variable using bar plots or chi-square tests.</li>
<li>Explore the relationship between numerical and categorical variables using box plots or violin plots.</li>
</ul>

Click <a href="https://github.com/breannagirdy/Retail-Analytics-Predicting-Customer-Purchase-Behavior/blob/main/RetailAnalyticsCapstone.ipynb">here</a> to access Python.

# Conclusions

We begin our analysis with a summary. According to the data collected, our average customer is 58 years of age, earns approximately $53,000 a year, spends the least amount of dollars on Fruits and the most amount of dollars on Wine. Overall, this customer shops in store with the second most frequented avenue of purchase being online. If we were to create historgrams of the most important Numerical Variables, we can observe that the amount spent on various products is consistently postivevly skewed. In other words, the customer base typically spends a small amount of money at a time on various products, however Wines is skewed more heavily to the right, indicating the occasional large, but outlier, purchase.

Regarding our outreach, most customers did not respond to the last campaign offer or complain. At most, 7.5% of customers responded to campaigns (Campaign #5). In other words, if we are interested in reaching customers it would be within our best interest to be specific on who we are targeting, and how we can reach them. 

For example, we have identified Fruits as the product category seeing the least amount of dollars spent. If we explore these numbers on a box plot related to Marital Status, we can see that the group spending the least amount of Fruits are those categorized under the “YOLO” Marital Status.

We can explore this same question as it relates to Education and we can see that those with a Basic level of education spend the least on Fruits.

In order to target these demographics specifically, it would be within our best interest to explore outreach via the most effective avenues. Those with Marital Status “YOLO” make the most amount of purchases via Web while those with a Basic Education make the most amount of purchases in Store. Therefore, it would be most effective to launch produce promotions in those areas to reach those specific groups.

# Connect
<a href="https://www.linkedin.com/in/breanna-girdy">Visit me on LinkedIn!</a>

# Spotify Penetration Analysis Solution
## Tableau Development

## Overview  
This project involves analyzing Spotify's market penetration rate in different countries to assess its performance and growth potential. The task is based on calculating the active user penetration rate, using specific criteria for defining active users and leveraging SQL for data analysis and Tableau for visualization.

Unlocking insights into Spotify's market reach with a comprehensive penetration analysis.

StrataScratch offers SQL practice questions, including those tailored for Meta (formerly Facebook) interview preparation. These questions focus on real-world business scenarios, requiring analytical skills and SQL proficiency. Common topics include:

User engagement analysis
Revenue and growth metrics
Ad performance evaluation
Behavioral trend analysis
---

## Task Details  

### **Problem Statement**  
You are part of the analytics team at Spotify and need to calculate the active user penetration rate for specific countries.  

### **Active User Criteria**  
A Spotify user is classified as "active" if they meet the following conditions:  
1. **`last_active_date`**: The user must have interacted with Spotify within the last 30 days.  
2. **`sessions`**: The user must have engaged with Spotify for at least 5 sessions.  
3. **`listening_hours`**: The user must have spent at least 10 hours listening on Spotify.  

---

### **Formula**  
The Active User Penetration Rate is calculated using the formula:  


---

## Output Requirements  
The result of the analysis should include the following columns:  
1. **`country`**: Name of the country.  
2. **`active_user_penetration_rate`**: Rounded to 2 decimal places.

---

## Tools and Technologies  
- **Database**: Microsoft SQL Server  
- **Visualization**: Tableau  

---

## Steps to Solve  
1. **Define Active Users**:  
   Use SQL queries to filter users based on the provided active user criteria:  
   - Interaction date within 30 days.  
   - At least 5 sessions.  
   - Minimum of 10 hours spent listening.  

2. **Calculate Active User Penetration Rate**:  
   Use the defined formula to compute the penetration rate for each country.

3. **Output the Results**:  
   Ensure the output includes the `country` and `active_user_penetration_rate` rounded to two decimal places.

4. **Visualize the Results**:  
   Import the SQL output into Tableau to create a dashboard visualizing penetration rates by country.  

---

## Interview Context  
This task is designed for StrataScratch interview preparation for roles like:  
- **Data Engineer**  
- **Data Scientist**  
- **BI Analyst**  
- **Data Analyst**  
- **ML Engineer**  
- **Software Engineer**  

Difficulty Level: **Hard**  
Task ID: **10369**  

---

## Date and Preparation  
**Interview Practice Date**: January 2024  

Good luck with your analysis and visualization! 🚀

# Exploratory-Data-Analysis-on-Employee-performance
---

**Introduction**
# *Objective of the Analysis*
The **objective of the analysis** is to explore the **Employee Performance dataset**  to understand factors influencing employee performance, satisfaction, and salary trends by examining distributions, relationships, and correlations across departments and demographics, and visualizing insights to help HR and management make data-driven decisions for optimizing workforce performance and improving employee satisfaction.

# **Descriptive Statistics **

1. Performance_Rating
Mean: ~3.0,
Median: 3.0,
Standard Deviation: ~1.4,
Range: 1 to 5,

Interpretation: Performance ratings are evenly distributed around the median, with most employees rated between 2 and 4.


2. Salary
Mean: ~$65,000,
Median: ~$65,000,
Standard Deviation: ~$20,000,
Range:30,000 to 100,000,

Interpretation: Salaries are evenly distributed, with no significant skewness.

3. Satisfaction_Score
Mean: ~6.5,
Median: 7.0,
Standard Deviation: ~2.5,
Range: 1 to 10,

Interpretation: Most employees have a satisfaction score between 5 and 8, indicating moderate to high satisfaction.

4. Age
Mean: ~40 years,
Median: ~40 years,
Standard Deviation: ~10 years,
Range: 22 to 60 years,

Interpretation: Employee ages are evenly distributed, with no significant skewness.

5. Years_At_Company
Mean: ~10 years,
Median: ~10 years,
Standard Deviation: ~5 years,
Range: 1 to 20 years,

Interpretation: Most employees have been with the company for 5 to 15 years.

---

**Univariate Analysis**

---

The gender distribution in the company is nearly balanced, with 253 female employees and 247 male employees. This indicates a well-maintained gender ratio in the workforce, which can contribute to a diverse and inclusive work environment.  

Looking at the distribution of employees by department, Marketing has the highest number of employees (112), followed closely by Sales (109). HR, Finance, and Engineering have slightly fewer employees, with Engineering having the least at 91. This suggests that the company places a strong focus on marketing and sales, possibly due to business needs or company strategy.  

When it comes to performance ratings, the most common rating is 5, received by 111 employees, while 101 employees received the lowest rating of 1. The distribution across other ratings (2, 3, and 4) is relatively even. This indicates that while some employees perform exceptionally well, there are also a significant number of employees who may need improvement or support.

---
**Bivariate Analysis**
---
The average salary varies across departments, with Sales employees earning the highest average salary of approximately $68,376, followed by Finance at $65,419. HR and Marketing have similar average salaries, around $64,129 and $65,009, respectively, while Engineering has the lowest average salary at about $61,315. This suggests that Sales roles might offer higher incentives or commissions compared to other departments.  

Employee satisfaction scores also differ slightly by department. Finance employees have the highest average satisfaction score of 5.70, followed by Sales at 5.60, and Marketing at 5.53. Engineering employees report the lowest satisfaction, with an average score of 5.35. While the differences are not drastic, they may indicate variations in work culture, workload, or job expectations across departments.  

Regarding tenure, Finance employees have the longest average years at the company (10.41 years), closely followed by HR (10.40 years). Sales and Marketing employees have slightly shorter tenures, averaging around 10 years, while Engineering employees have the shortest tenure at 9.66 years. This could mean that Finance and HR roles offer more stability, while Engineering might experience higher turnover rates.  

When comparing performance ratings by gender, males have a slightly higher average performance score (3.09) compared to females (2.98). While the difference is minor, it raises questions about potential factors influencing performance assessments, such as job roles, workload distribution, or evaluation criteria.


---
***Group analysis***
---
 The average age by gender shows that males are slightly older on average (41.26 years) compared to females (40.15 years). While the difference is minimal, it might reflect variations in hiring trends or career progression between genders.  

Across departments, Engineering has the highest average age (41.87 years), followed closely by Marketing (41.63 years) and HR (40.81 years). Finance and Sales have slightly younger employees, with averages of 39.35 and 39.81 years, respectively. This suggests that technical roles in Engineering might require more experience, leading to an older workforce.  

When analyzing salary based on years at the company, there is no clear upward trend. Employees with 17 years of experience earn the highest average salary ($71,810), while those with 9 years earn the lowest ($58,221). Salaries fluctuate at different tenure levels, possibly due to promotions, role changes, or variations in company pay structures over time.  

Finally, when looking at tenure by gender, males have a longer average stay at the company (10.51 years) compared to females (9.68 years). This may suggest differences in career longevity, turnover rates, or workplace retention factors between genders.


---

### Correlation Analysis  
---
The correlation matrix reveals weak relationships among the numerical variables in the dataset. Performance rating has a very slight positive correlation (0.07) with satisfaction score, suggesting that employees with higher performance ratings may be slightly more satisfied, though the effect is minimal.  

Salary shows almost no correlation with performance rating (-0.009) and a very weak negative correlation with satisfaction score (-0.03), indicating that higher salaries do not necessarily lead to better performance or higher satisfaction. Similarly, salary has a weak negative correlation with age (-0.06), meaning older employees do not necessarily earn more.  

Years at the company has a near-zero correlation with salary (0.007) and performance rating (0.03), which suggests that tenure does not strongly impact salary growth or performance assessment. Satisfaction score also shows little to no correlation with age (0.01) and years at the company (0.03), indicating that employee satisfaction does not significantly change with experience or age.  

Overall, the dataset does not show strong linear relationships between most numerical variables, implying that other non-numerical factors may play a more significant role in influencing employee performance, satisfaction, and salary.

---

### **Key Insights**

---
1. **Employee Performance:** Most employees have an average performance rating of **3**, with fewer high or low performers. Higher performance is linked to higher salaries and satisfaction scores.
2. **Salary Trends:** Salaries range widely from **$30,000 to $100,000**, reflecting diverse roles and experience levels. Higher salaries are associated with better performance and longer tenure.
3. **Employee Satisfaction:** Satisfaction scores are generally moderate to high (between **5 and 8**), with higher satisfaction correlating with better performance.
4. **Departmental Insights:** Departments like **Engineering** and **Finance** tend to have higher average salaries and performance ratings compared to others, indicating potential disparities in role expectations or rewards.
5. **Demographics:** The workforce is evenly distributed in age (peaking around **40 years**) and gender, with most employees having **5 to 15 years** of tenure, reflecting a stable and experienced workforce.

---

### **Conclusion**
---
The **Employee Performance Analysis** provides valuable insights into the factors influencing employee performance, satisfaction, and salary trends. Key findings reveal that most employees perform at an average level, with higher performance linked to greater satisfaction and higher salaries. Departments like **Engineering** and **Finance** tend to outperform others, while the workforce is stable, with many employees having mid-level tenure.

To leverage these insights, actionable recommendations include rewarding high performers, improving employee satisfaction, addressing departmental disparities, and investing in employee development. By implementing these strategies, organizations can enhance productivity, foster a positive workplace culture, and ensure long-term employee retention and success. This analysis underscores the importance of data-driven decision-making in optimizing workforce performance and achieving organizational goals.

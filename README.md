# Analyzing the Data Science Salaries

### Problem context
The data science industry is rapidly developing, leading to a high demand for skilled professionals. Therefore, understanding factors that influence their salaries is crucial for individuals making career choices and for organizations offering employment.
### Scientific question
We want to analyse what factors influence the salaries of IT specialists, and what is the impact of different factors on salaries compared between machine learning (ML) specialists, data scientists (DS), and data analysts (DA). We focus on the following questions:
- Does experience level impact the salary?
- Does remoting of worker impact the salary?
- Does size of company impact the salary?
- Does employment type impact the salary?
- Does country impact the salary?
- Does job (DS, DA, ML) impact the salary?
- Does experience level impact the salary of job (DS, DA, ML)?

### Statistical Techniques:
1. Descriptive Statistics: Measures like mean, median, mode and visualizations (histograms) were used to explore the salary within each category (experience level, job title, country, employment type, year).
2. Non-Parametric Tests:
   1. **Kruskal-Wallis test** was used because it assumes no particular distribution of the data and allows to compare several groups.
   2. **The Shapiro-Wilk test** was used to check the null hypothesis that the data was drawn from a normal distribution.
4. Post-Hoc Tests: Dunn test is used if Kruskal-Wallis test reject the null hypothesis and comparisons between groups are required to determine which groups are different.
### Statistical tools
Our code is written in Python, including the following libraries:
- Pandas - to import, clean, and organize our dataset;
- Numpy - to perform basic numerical operations and statistical analyses;
- Matplotlib - to create visualizations of data using bars and pies;
- Scipy - to perform hypothesis testing using statistical analyses, namely the Kruskal-Wallis test;
- Scikit posthocs - to use post hoc tests after conducting the Kruskal-Wallis test;

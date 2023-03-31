# pandas-challenge
Pandas Challenge Assignment

# PyCity Schools Analysis

In this project, I analyzed school and standardized test data. To do so, I used Pandas and Jupyter Notebook in VSCode to analyze district-wide standardized test results. 

To begin the analysis, I created a district summary that includes the total number of unique schools, total students, total budget, average math score, average reading score, % passing math, % passing reading, and % overall passing. I then created a summary of key metrics about each school, including school name, school type, total students, total school budget, per student budget, average math score, average reading score, % passing math, % passing reading, and % overall passing.

* I also determined the highest and lowest performing schools based on % overall passing and displayed the top 5 and bottom 5 rows in DataFrames called "top_schools" and "bottom_schools", respectively.

* To further analyze the data, I calculated the average math and reading scores for students of each grade level (9th, 10th, 11th, 12th) at each school and created a DataFrame for each. 

* I then created a table that breaks down school performance based on average spending ranges (per student), using provided code to create four bins with reasonable cutoff values. The table includes the average math score, average reading score, % passing math, % passing reading, and % overall passing.

* Next, I binned the per_school_summary DataFrame based on school size and created a DataFrame that breaks down school performance based on school size (small, medium, or large).

* Finally, I created a new DataFrame that shows school performance based on Public District vs District Charter Schools.

## 3 Analysis Findings

* As a whole, schools with higher budgets, did not yield better test results. By contrast, schools with higher spending 645-675 per student actually underperformed compared to schools with smaller budgets (585 per student).

* As a whole, smaller and medium sized schools dramatically out-performed large sized schools on passing math performances (89-91% passing vs 67%).

* As a whole, charter schools out-performed the public district schools across all metrics. However, more analysis will be required to glean if the effect is due to school practices or the fact that charter schools tend to serve smaller student populations per school. 

---

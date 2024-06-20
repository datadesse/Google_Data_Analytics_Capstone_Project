# web-scraping-of-data-analyst-jobs-analysis-

-This project is a showcase for Scrape and Analyze data analyst job requirements with Python
Coursera Project which is part of the Google Data Analytics Professional Certificate course I completed.

**The Objectives of this Analysis**

- The recruitment agency where I work as a data analyst has asked me to create a web scraping tool that can automatically extract details of Data Analyst jobs in England from a job posting site & make recommendations from my findings.

**Problems to Solve**
- the employer advertised the most jobs,  the best time to use the scrapping tool, the highest and least paid roles,  the average salary & any other findings useful for the agency to consider. 

**Data source and Tools used** 
- I used Python's libraries-BeautifulSoup, Requests and Pandas to scrape details of Data Analyst jobs advertising- titles, dates, salaries, locations, employers and working hours from [REED UK website](www.reed.co.uk) to answer the problems


**Tools used for Analysis**
- Python's libraries-Pandas, NumPy 
- Matplotlib, Seaborn and Tableau Public are used to create tables, charts and dashboard to visualise the results. 

**Challenges**
- I had problems changing the date column to the DateTime format. It took me a long time to find out that the [REED UK website](www.reed.co.uk) misspelt 'Feburary' instead of 'February' 
- The date columns have multiple formats such as 'days ago', 'yesterday' and months
- Similarly, the salary column has figured salaries - range (minimum and maximum), per year, per hour, and per day, There is three string  salaries 'Competitive salary', ' Training Course' & 'Salary negotiable'   and one value contains wrong currency Euro (€) sign instead of £. I spent so much time cleaning the data than I expected.  






Acknowledgements to:
- [Google](https://www.google.com/) & [Coursera](www.coursera.org) for providing the [Google Data Analyst Professional Certificate course.](https://www.coursera.org/professional-certificates/google-data-analytics)
- [ChatGPT](https://chatgpt.com/auth/login) and
- [Stackoverflow](https://stackoverflow.com/)

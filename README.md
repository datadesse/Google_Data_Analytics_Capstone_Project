# Google Data Analytics Capstone: Complete a Case Study
## Web Scraping of Data Analyst Jobs Analysis

-This project is a showcase for Scrape and Analyze data analyst job requirements with Python
Coursera Project which is part of the Google Data Analytics Professional Certificate course I completed.

**The Objectives of this Analysis**

- The recruitment agency where I work as a data analyst has asked me to create a web scraping tool that can automatically extract details of Data Analyst jobs in England from a job posting site & make recommendations from my findings.

**Problems to Solve**
- the employer advertised the most jobs,  the best time to use the scrapping tool, the highest and least paid roles,  the average salary & any other findings useful for the agency to consider. 

**Data source and Tools used** 
- I used Python's libraries-BeautifulSoup, Requests and Pandas to scrape details of Data Analyst jobs advertising- titles, dates, salaries, locations, employers and working hours from [REED UK website](www.reed.co.uk) to answer the problems
- I experimented with my line of codes on the first page of the website before applying it to all pages then I created a single function that can automatically extract the required information from all pages and saved the data as a CSV file. 


**Tools used for Analysis**
- Python's libraries-Pandas, NumPy 
- Matplotlib, Seaborn and Tableau Public are used to create tables, charts and dashboard to visualise the results. 

**Challenges**
- I had problems changing the date column to the DateTime format. It took me a long time to find out that the [REED UK website](www.reed.co.uk) misspelt 'Feburary' instead of 'February' 
- The date column has multiple formats such as 'days ago', 'yesterday' and months. Similarly, the salary column has figured salaries - range (minimum and maximum), per year, per hour, and per day, There are three strings  salaries 'Competitive salary', ' Training Course' & 'Salary negotiable'   and one value contains wrong currency sign Euro (€) instead of £. I spent a considerable amount of time cleaning the data than I expected.  

** Coursera Project Network**
- The scrapping tool I created is also available on Coursera Project Network and can be accessed  using the following link: [Scrape and analyze data analystjob requirements with Python](https://sharedxfmjqibr.labs.coursera.org/notebooks/web_scraping_of%20data_analyst_jobs_23_06_24.ipynb)



Acknowledgements to:
- [Google](https://www.google.com/) & [Coursera](www.coursera.org) for providing the [Google Data Analyst Professional Certificate course.](https://www.coursera.org/professional-certificates/google-data-analytics)
- [ChatGPT](https://chatgpt.com/auth/login) and
- [Stackoverflow](https://stackoverflow.com/)

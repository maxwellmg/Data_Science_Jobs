# Data_Science_Jobs
Compiling data on available jobs in the data science field 

For my final project in my Data Science course at American University (DATA-613), I endeavored to address the following hypothesis: 

Do incoming data scientists working in the public sector enjoy a better quality of life when compared to their STEM colleagues?  

To address this question, I used RSelenium to scrape the (free to access) USAJOBS portal for all open positions matching the key terms: data scientist, data engineer, and data analyst. After compiling a discreet list of jobs (n = 2,108), I defined the "true data scientist" positions as the jobs that matched for each of the search terms (n = 74). Choosing to define quality of life as a product of a. salary, and b. telework eligibility, I found the following:

a. Salary was given as ranges on the job portal, thus, I could utilize two-tailed unpaired t-tests on the two groups (data scientists vs. non-data scientists) to determine if there is a statistical difference. The difference of the means of both the minimums (p = 0.034) and the maximums (p < 0.0001) are statistically significant. The difference of the means between the salary minimums is $7,704.21, (95% CI: $565.70 - $14,842.72) and the maximums is $17,591.80 (95% CI: $9031.71 – $26,151.88). With Data Scientists listed with higher minimum and maximum salary ranges at statistically significant levels, it is highly improbable that the difference in salary ranges is not due to chance based on sample selection.

b. 17% of jobs listed for data scientists and their counterparts are exclusively in-office positions. However of the remaining 83% of telework eligible jobs, Data Scientists enjoy 6% more fully remote jobs compared to non-data scientists.

These two points indicate a higher quality of life for open data scientist positions, though the scope of inference for this data is incredibly narrow. The data was obtained through observational means, and only collected in one scrape. (December 2024) The terms used for searching USAJOBS are likely not inclusive of all open STEM positions.

Inside this repository you'll find my R code for collecting and cleaning the data. The findings given above are a small subsection of the 21 distinct fields I collected data from. More analysis is available when time and interest allows.
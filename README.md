# Employment-data_challenge
### About Dataset
Our Dataset is about Job Vacancies, Payroll Employees, Job Vacancy rate and Avg Offerd Hourly Wage. This employment data is provided by the UNB as a part of Data challenge.
Data is collected by Job Vacancy and Wage Survey, every year on a calendar quarter basis, apart from Q2 and Q3 due to the pandemic.
Survey participation is made mandatory under the statistics act. We have also used population estimates on a quarterly basis.

### Problem Statement
- What patterns have emerged for job vacancies, payroll employees and average offered hourly wages?
- Which Canadian province(s) has maintained the most stable number of payroll employees since 2015?
- Is there a Correlation between the number of job vacancies, payroll employees, and hourly wages in Canada?

### EDA
- For Data processing, We started with 11,072 rows and ended up with 442 rows,after Removing missing values, unreliable data as per the source and duplicates and pivoting the rows.
- We used Province level information as our challenge objective is to compare amongst provinces.
- Filled the missing data of Q2 and Q3 for the year 2020 using average values of Q1 and Q4.
- Tableau was used to generate visuals, plot regression line and conduct correlation analysis.
- Statistical measures such as mean, standard deviation and percentage change/difference are used in the analysis.
- Tested Hypothesis for correlation between job vacancies, payroll employees and average offered hourly wage rate.

### Visualization 1 - Job Vacancy across provinces and Percentage difference
![image](https://github.com/vidd01/Employment-data_challenge/assets/122332733/8f4b5ea1-27fd-4d19-b562-f000254133b6)

![image](https://github.com/vidd01/Employment-data_challenge/assets/122332733/a272258a-824e-44eb-86b9-83e4bd3322ed)

### Visualization 2 - Payroll Employees across provinces and percentage difference
![image](https://github.com/vidd01/Employment-data_challenge/assets/122332733/ca9bfc1a-1fae-4927-b281-37e41b2dac88)

![image](https://github.com/vidd01/Employment-data_challenge/assets/122332733/7031db3c-4385-4774-ad28-333384418986)

### Visualization 3 - Hourly wages across provinces and percentage difference
![image](https://github.com/vidd01/Employment-data_challenge/assets/122332733/04b2f1e9-1236-4302-9bca-74270551460e)

![image](https://github.com/vidd01/Employment-data_challenge/assets/122332733/9a800f65-c65f-450e-ae36-f0bc201679ee)

### Visualization 4 - Population Vs Job vacancy rate across provinces
![image](https://github.com/vidd01/Employment-data_challenge/assets/122332733/ea5c776d-d616-4e03-a5ee-93d69552eb85)

### Hypothesis Testing
H0  = There Is A Strong Correlation Between Job Vacancies, Employment And Hourly Wages.
HA  = There Is No Strong Correlation Between Job Vacancies, Employment And Hourly Wages.

![image](https://github.com/vidd01/Employment-data_challenge/assets/122332733/7eec14e6-d062-453a-a846-7052ba94ebdf)
![image](https://github.com/vidd01/Employment-data_challenge/assets/122332733/964b513f-b325-439b-b88e-4a0a59c77361)
![image](https://github.com/vidd01/Employment-data_challenge/assets/122332733/1e190881-9609-4765-be1b-8907e885fbfb)

We reject our null hypothesis as it failed the test of significance for two pairs and accept the alternate hypothesis. 
There is no strong correlation between Job Vacancies, Employment and hourly wages.












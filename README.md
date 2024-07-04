<div align='center'> <h1> HR ANALYSIS </div>
  
<div align='center'> 

  ![pngwing com](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/dad77aa5-0652-4510-9710-01db40f48569)


</div>

____


__Tools used : Tableau, Power BI, MS SQL Server__

[Dataset used](https://github.com/KARTIKEYASWAMI/HR_Analysis/blob/main/files/HRdata%20(2).csv)

__Tableau Dashboard__    
[click here to view](https://github.com/KARTIKEYASWAMI/HR_Analysis/blob/main/HR%20Tableau%20Dashboard.pdf)   
[click here to interact with the Dashboard](https://public.tableau.com/views/HRANALYSISDASHBOARD_17106039712990/HRAnalyticsDashboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link) 

__Power BI Dashboard__   
[Power BI Dashboard](https://github.com/KARTIKEYASWAMI/HR_Analysis/blob/main/HR_Analytics_BI_Dashboard.pdf)   
[click here to interact with the Dashboard](https://app.powerbi.com/view?r=eyJrIjoiODBhYzY1ZGEtMmM0OS00YjkwLTkxYzYtZTBiNWEzYjMyZDE4IiwidCI6IjZmMTFlMWQzLTEyMTAtNDk5YS1iMjY0LTU2NzA0NTY4OGUyNyJ9)

__<h1>BUSINESS PROBLEM</h1>__
A Company faces a challenge in efficiently analyzing and monitoring employee data, with around 12k rows of data to make informed decisions regarding retention, development, and recruitment strategies. This lack of comprehensive data analysis inhibits the ability to track progress in reducing attrition rates effectively. Furthermore, without detailed insights into employee demographics such as gender, age group, job satisfaction, and education field, it becomes difficult to identify trends and patterns that could inform targeted interventions.It is also required to test the Dashboards developed on Tableau and Power BI for QA. Thus, there is a pressing need for a solution that provides robust analytics capabilities, including trend analysis and demographic segmentation to empower HR managers and business leaders in making data-driven decisions for optimizing workforce management practices.

__<h1>SOLUTION</h1>__

__<h2>STEPS OVERVIEW:</h2>__
+ Dataset collection.  
+ Understanding the Data.  
+ Loading Libraries.  
+ Data Cleaning & Finding Missing values.  
+ Data Visualization.
+ QA Testing(Quality Assurance)- Data Validation & Functional validation.

__<h2>DATA CLEANING:</h2>__
+ Opening Dataset in Excel and Make a Copy of Dataset for security purpose.
+ Removing Duplicates.
+ Formatting of columns wherever necessary.
+ Spelling Check.
+ Changing Case - Lower/Upper/Proper.
+ Trimming unwanted spaces.
+ Removing null values wherever necessary.
+ Finding & Replacing values.

__<h2>Data Visualization</h2>__

__1) Tableau Dashboard__

![1](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/d6c226d8-3a2c-41a7-aa34-a79b0cd842f3)

__2) Power BI Dashboard__

![2](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/fb7fc3c4-b46f-4bfd-9b5b-aa75259e6b77)


__<h2>Dashboard Contents</h2>__

__KPI:__

__1. Employee Count:__

![3](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/6a79359b-64df-4bf2-8cfe-2fc54cbc60f0)

This metric helps the department to assess workforce size and plan for future growth or downsizing effectively.

__2. Attrition Count:__

![4](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/50009540-36f0-4697-9e7a-de9bef07a628)


Gives a complete and reliable data on the number of employees who have left the organization.

__3. Attrition Rate:__

![5](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/c414da15-1e37-4930-8764-f13d7e820b66)


Gives a clear measure of attrition rate, such that the organization can assess the overall turnover level or compare it with industry benchmarks, improving the ability to gauge employee satisfaction and engagement.

__4. Active Employees:__

![6](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/8df42d28-26fa-4416-914a-3b023fe0191b)


This metric differentiate between active and inactive employees, thus aids in accurately assessing the current workforce's productivity and capacity.

__5. Average Age:__

![7](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/fb468bb8-cf31-4e2c-a22c-ca1a056bb1c7)


Gives insight into the average age of employees, making it easy to evaluate workforce demographics, succession planning, and the organization's ability to attract and retain younger talent.

__Charts:__

__1) Attrition by Gender:__

![8](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/cc5ab43c-1850-47e3-ac58-9398c41c8ce9)


Gives insight into the attrition patterns based on gender, making it difficult to identify any gender-related disparities and implement targeted retention strategies.

__2) Department-wise Attrition:__

![9](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/a997cd00-770b-43c7-a927-3cfbd99b8227)


This visualization showcases attrition rates across different departments. This boosts their ability to identify departments with higher attrition rates and address any underlying issues or concerns effectively.

__3) Number of Employees by Age Group:__

![10](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/697b2f38-9199-4f9c-a118-970ede4823d1)


The HR department requires visual representations to analyze the distribution of employees across various age groups. This helps in assessing workforce demographics, identifying any age-related gaps or imbalances, and implementing targeted HR policies or programs.

__4) Job Satisfaction Ratings:__

![11](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/98d77a10-2b62-4ce9-ae7d-e4f94f5a91bf)


This visualization is used to represent job satisfaction ratings, improving their ability to measure employee engagement and overall job satisfaction levels effectively.

__5) Education Field-wise Attrition:__

![12](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/6dfb2105-6ed1-4e29-bdcb-c13914efa645)

This visual representations can be used to analyze attrition rates based on education fields. This helps identify specific educational backgrounds that may be associated with higher attrition, enabling the organization to tailor retention strategies accordingly.

__6) Attrition Rate by Gender for Different Age Groups:__

![13](https://github.com/KARTIKEYASWAMI/HR_Analysis/assets/84394140/604d32f4-217b-4392-8f8a-65b3dfd60c22)


This visualizations displays attrition rates based on gender and different age groups making it easy to identify any age and gender-related attrition trends, aiding the organization in implementing targeted retention strategies for specific employee segments.

__<h2>QA Testing (Quality Assurance)</h2>__
1) __Functional Validation -__ Testing if each feature works as per the requirement and verifying if all the filters and Action Filters on the report work as per the requirement.

2) __Data Validation -__ Checking accuracy and quality of data and to match the values in Tableau and Power BI report with the SQL queries.

[SQL Queries for Analyzing/Testing Reports](https://github.com/KARTIKEYASWAMI/HR_Analysis/blob/main/SQL%20Analysis-%20Testing%20Tableau%20%26%20Power%20BI%20Reports)

__<h1>CONCLUSION</h1>__

The HR Analytics Dashboard project utilizing Tableau, Power BI and SQL aims to offer comprehensive insights into essential HR metrics and trends within an organization. By employing visualizations and data analysis techniques, the dashboard facilitates HR professionals in discerning patterns and making informed, data-driven decisions. It encompasses key visualizations presenting an overarching view of HR-related metrics, including turnover rate, headcount, and employee engagement levels. Additionally, it provides insights into recruitment metrics such as time-to-fill and cost-per-hire.

Moreover, the dashboard delves into employee performance metrics, including training and development, performance appraisals, and career progression, aiding HR professionals in identifying areas for enhancement and formulating strategies to bolster employee engagement and productivity.

Featuring interactive functionalities enabling users to filter and drill down into specific data subsets like department, location, or job level, the dashboard facilitates a more granular analysis, simplifying the identification of patterns and trends.

In essence, this project serves as a vital tool for HR professionals seeking deeper insights into their organization's HR data. Leveraging these robust data visualization and analysis tools, HR professionals can make informed decisions pivotal in driving organizational success. Furthermore, the project entailed thorough QA/testing of Tableau and Power BI reports using SQL queries to ensure accuracy and reliability.








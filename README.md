Project: Data Analysis of Job Postings

This project involved performing a series of five data analysis tasks on a job descriptions dataset. The analysis was conducted using Tableau, with each task focusing on a different set of business questions and filtering criteria. 
The final results were charts and maps that provided insights into job postings, with several tasks yielding a finding that no data matched the specified conditions.

Methodology :

The following is a step-by-step procedure for how the data analysis for each task was conducted:

Data Connection: The first step for each task was to connect to the raw data source, which was a job descriptions file.
Visual Building: For each task, a new worksheet was created. The process involved dragging and dropping the primary fields, such as Company, Job Title, Country, or Latitude and Longitude, to the Rows, Columns, or Marks shelves to form the base of a bar chart, text table, or map.
Calculated Fields: A time-based calculated field, named 'Show Chart', was created for all tasks to handle the specific time-of-day filtering requirement. This field was used as a filter on each worksheet.
Applying Filters: All filters specified in each task's problem statement were applied sequentially. This included a mix of standard filters (e.g., filtering for a specific Job Title), custom filters (e.g., excluding countries that start with a certain letter), and range-based filters (e.g., for Salary, Company Size, or Experience).
Customization and Verification: Any visual requirements, such as color coding for Task 5, were applied. The final chart was then examined to determine the outcome. For Tasks 2, 3, and 4, the combination of highly specific filters resulted in a blank chart, which was confirmed to be the correct finding after cross-checking the raw data

Task 1: Analysis of Intern Roles

Objective: The goal was to create a chart showing the relationship between job preference and work type for intern roles.
Filters Applied:
* Work type was filtered to 'Intern'.
* Latitude was filtered to be below 10.
* Countries were filtered to not start with A, B, C, or D.
* Job title length was limited to a maximum of 10 characters.
* Company size was filtered to be below 50000.
* A time-based filter was applied for 3 PM IST to 5 PM IST.
Final Result: A chart was successfully created, showing the distinct count of jobs for each preference (Female, Male, and Both) that met all the criteria.

Task 2: Analysis of Mechanical Engineer Jobs

Objective: The goal was to create a chart of company size versus company name for Mechanical Engineer jobs.
Filters Applied:
* Company size was filtered to be below 50000.
* Job title was filtered to 'Mechanical Engineer'.
* Experience was filtered to more than 5 years.
* Country was set to Asian countries.
* Salary was set to more than $50k.
* Work type was filtered to both 'part time' and 'full time'.
* Preference was filtered to 'male'.
* Job portal was filtered to 'idealist'.
* A time-based filter was applied for 3 PM IST to 5 PM IST.
Final Result: After applying all the filters, the chart was blank. This finding was confirmed through manual testing, which indicated that no job postings matched all the specific criteria.

Task 3: Analysis of Data Engineer and Data Scientist Jobs

Objective: The goal was to find the top 10 companies hiring for Data Engineer roles with a Data Scientist job title.
Filters Applied:
* Role was filtered to Data Engineer and Job Title to Data Scientist.
* Country was filtered to exclude Asian countries and those starting with 'C'.
* Preference was set to Female only.
* Job Posting Date was filtered to be between January 1, 2023, and June 1, 2023.
* Qualification was filtered to B.Tech.
* Latitude was filtered to be below 10.
* A time-based filter was applied for 3 PM IST to 5 PM IST.
Final Result: The final chart was blank. This result was confirmed by cross-checking the raw data, which showed that no job postings met all the conditions.

Task 4: Analysis of Full-time Jobs in Africa

Objective: The goal was to create a map displaying job locations for full-time roles in Africa with very specific requirements.
Filters Applied:
* Qualification was filtered to B.tech, M.tech, and PhD.
* Work type was filtered to Full time.
* Country was filtered to the African continent.
* Job title was filtered to titles starting with 'D'.
* Preference was set to Male.
* Company size was filtered to more than 80,000.
* Contact person was filtered to names starting with 'A'.
* Job portal was set to 'indeed'.
* A time-based filter was applied for 3 PM IST to 6 PM IST.
Final Result: The map chart was blank. This outcome was validated by a raw data cross-check, which confirmed the absence of any job postings that satisfied all the criteria.

Task 5: Analysis of Full-time B.Tech Jobs in India and Germany

Objective: The goal was to compare job postings in India and Germany for B.tech graduates in specific full-time roles.
Filters Applied:
* Countries were filtered to India and Germany.
* Qualification was filtered to B.tech.
* Work type was set to Full time.
* Experience was filtered to more than 2 years.
* Job title was filtered to 'Data Scientist', 'Art Teacher', and 'AeroSpace Engineer'.
* Salary range was filtered to more than $10k.
* The job portal was set to 'indeed' and preference to 'female'.
* Job posting date was filtered to be before August 1, 2023.
* A time-based filter was applied for 3 PM IST to 5 PM IST.
Final Result: The final chart shows the count of jobs for each country that met all the criteria. Given the number of specific filters, it is possible the chart may be blank, which would be a valid finding.

Conclusion:
This project demonstrated a comprehensive approach to data analysis, from setting up individual charts in Tableau to applying highly specific and restrictive filters.
A key finding was that for several tasks (2, 3, and 4), the data did not contain any job postings that satisfied all the combined criteria. 
This highlights the importance of thorough data filtering and validation to accurately represent the insights within a given dataset.

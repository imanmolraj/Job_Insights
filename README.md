# Job_Insights

This repository contains the code and documentation for a data analysis and visualization project focused on building an interactive job market trends dashboard. The project leverages a comprehensive dataset of job postings to provide key insights into various job roles, company demographics, and geographical trends.

Tech Stack
Data Analysis: Python with the Pandas library for all data cleaning, filtering, and transformation tasks.

Data Visualization: Tableau for creating interactive dashboards and reports.

Front-End Integration: HTML and JavaScript for embedding the dashboard on a webpage and implementing time-based display logic.

Dashboard Features
The final dashboard is a culmination of five distinct tasks, each designed to answer a specific business question. The dashboard is fully interactive and provides the following features:

Task 1: Intern Preference Analysis
Purpose: Visualizes preference trends for internship roles.

Data Filters: work_type = 'Intern', latitude < 10, county_name not starting with A, B, C, or D, job_title max 10 characters, company_size < 50000.

Visual: Bar chart showing Preference vs. Number of Records.

Time-Based Logic: Visible between 3 PM and 5 PM IST.

Task 2: Mechanical Engineer Insights
Purpose: Analyzes trends for Mechanical Engineer roles in specific countries.

Data Filters: company_size < 50000, job_title = 'Mechanical Engineer', experience > 5 years, country is Asian, salary_range > $50k, work_type = 'Part-time' or 'Full-time', preference = 'Male', job_portal = 'indeed'.

Visual: Bar chart of Company Name vs. Company Size.

Time-Based Logic: Visible between 3 PM and 5 PM IST.

Task 3: Top 10 Data Roles
Purpose: Identifies the top 10 companies hiring for data-related roles in non-Asian countries.

Data Filters: job_title is 'Data Engineer' or 'Data Scientist', country is not Asian and does not start with 'C', preference = 'Female', job_posting_date between 01/01/2023 and 06/01/2023, qualification = 'B.Tech', latitude < 10.

Visuals: Bar chart of the top 10 companies and an interactive map.

Time-Based Logic: Visible between 3 PM and 5 PM IST.

Task 4: African Job Insights
Purpose: Explores job trends in African countries based on specific qualifications and experience.

Data Filters: qualification is 'B.tech', 'M.tech', or 'PhD', work_type = 'Full time', country is African, job_title starts with 'D', preference = 'Male', company_size > 80,000, contact_person starts with 'A', job_portal = 'indeed'.

Visuals: Bar chart of Company Name vs. Number of Records and an interactive map.

Time-Based Logic: Visible between 3 PM and 6 PM IST.

Task 5: India & Germany Job Trends
Purpose: Compares job market trends for specific roles in India and Germany.

Data Filters: country is 'India' or 'Germany', qualification = 'B.tech', work_type = 'Full time', experience > 2 years, job_title is 'Data Scientist', 'Art Teacher', or 'Aerospace Engineer', salary_range > $10k, job_posting_date before 08/01/2023, job_portal = 'indeed', preference = 'Female'.

Visual: Bar chart with distinct color-coding for India (Orange) and Germany (Green).

Time-Based Logic: Visible between 3 PM and 5 PM IST.

How to Use the Repository
Clone the Repository: git clone [repository_url]

Run the Python Scripts: Execute the Python files to generate the filtered CSV data for each task.

Open the Tableau Workbook: Use the filtered data to work with the Tableau visualizations.

View the Live Dashboard: Open the index.html file in your browser to see the combined dashboard.

📊 Job Market Trends Dashboard

This repository contains the code and documentation for a data analysis and visualization project focused on building an interactive job market trends dashboard. The project leverages a comprehensive dataset of job postings to uncover insights into job roles, company demographics, and geographical hiring patterns.

🚀 Tech Stack

Data Analysis: Python (Pandas) → Data cleaning, filtering, and transformation

Data Visualization: Tableau → Interactive dashboards and reports

Front-End Integration: HTML + JavaScript → Embedding Tableau dashboards with time-based logic

📌 Dashboard Features

The final interactive dashboard answers five distinct business questions, each with custom filters, visuals, and time-based logic.

Task 1: Intern Preference Analysis

Purpose: Visualizes internship preference trends.

Filters:

work_type = Intern

latitude < 10

county_name not starting with A, B, C, or D

job_title max 10 characters

company_size < 50,000

Visual: Bar chart (Preference vs. Number of Records)

Time Visibility: 3 PM – 5 PM IST

Task 2: Mechanical Engineer Insights

Purpose: Analyzes Mechanical Engineer roles in specific Asian countries.

Filters:

company_size < 50,000

job_title = Mechanical Engineer

experience > 5 years

country = Asian

salary_range > $50k

work_type = Part-time / Full-time

preference = Male

job_portal = indeed

Visual: Bar chart (Company Name vs. Company Size)

Time Visibility: 3 PM – 5 PM IST

Task 3: Top 10 Data Roles

Purpose: Identifies top companies hiring for Data Engineer/Data Scientist roles in non-Asian countries.

Filters:

job_title = Data Engineer / Data Scientist

country ≠ Asian and does not start with "C"

preference = Female

job_posting_date = 01/01/2023 → 06/01/2023

qualification = B.Tech

latitude < 10

Visuals:

Bar chart (Top 10 companies)

Interactive map

Time Visibility: 3 PM – 5 PM IST

Task 4: African Job Insights

Purpose: Explores job trends in African countries.

Filters:

qualification = B.Tech / M.Tech / PhD

work_type = Full time

country = African

job_title starts with "D"

preference = Male

company_size > 80,000

contact_person starts with "A"

job_portal = indeed

Visuals:

Bar chart (Company Name vs. Number of Records)

Interactive map

Time Visibility: 3 PM – 6 PM IST

Task 5: India & Germany Job Trends

Purpose: Compares hiring trends in India vs. Germany.

Filters:

country = India / Germany

qualification = B.Tech

work_type = Full time

experience > 2 years

job_title = Data Scientist / Art Teacher / Aerospace Engineer

salary_range > $10k

job_posting_date < 08/01/2023

job_portal = indeed

preference = Female

Visual: Bar chart (Orange = India, Green = Germany)

Time Visibility: 3 PM – 5 PM IST

🛠️ How to Use

Clone the Repository

git clone [repository_url]
cd job-market-dashboard


Run Python Scripts

Execute the Python files to generate filtered CSV datasets for each task.

Open Tableau Workbook

Load the filtered datasets into Tableau.

Explore or customize the interactive dashboards.

View Live Dashboard

Open index.html in your browser.

Dashboards will automatically display based on the configured time-based logic.

📂 Repository Structure

job-market-dashboard/
│── data/                 # Raw & filtered datasets
│── scripts/              # Python scripts for data filtering & cleaning
│── tableau/              # Tableau workbooks (.twb / .twbx)
│── index.html            # Web integration with time-based logic
│── README.md             # Project documentation

📸 Sample Dashboard Preview

(Add a screenshot of your Tableau dashboard here)

✨ Key Highlights

✔️ Fully interactive Tableau dashboard
✔️ Data-driven insights tailored to specific roles & regions
✔️ Smart time-based visibility logic
✔️ Easy integration into a website

📜 License

This project is licensed under the MIT License – feel free to use and modify.

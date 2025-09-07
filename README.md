# 📊 Job Market Trends Dashboard

An interactive **job market analysis and visualization project** built using **Python, Tableau, HTML, and JavaScript**.  
The dashboard provides insights into job roles, company demographics, and geographical hiring patterns with **time-based logic** for dynamic display.

---

## 🚀 Tech Stack

- **Python (Pandas)** → Data cleaning, filtering, transformation  
- **Tableau** → Interactive dashboards & reports  
- **HTML + JavaScript** → Front-end integration & time-based logic  

---

## 📌 Dashboard Features & Tasks

### **Task 1: Intern Preference Analysis**
- **Purpose:** Visualize internship preference trends  
- **Filters:**  
  - Work type = `Intern`  
  - Latitude < 10  
  - County name not starting with A, B, C, or D  
  - Job title ≤ 10 characters  
  - Company size < 50,000  
- **Visual:** Bar chart (Preference vs. Records)  
- **Time Visibility:** ⏰ 3 PM – 5 PM IST  

---

### **Task 2: Mechanical Engineer Insights**
- **Purpose:** Analyze Mechanical Engineer roles in Asian countries  
- **Filters:**  
  - Company size < 50,000  
  - Job title = `Mechanical Engineer`  
  - Experience > 5 years  
  - Country = Asian  
  - Salary range > $50k  
  - Work type = Part-time / Full-time  
  - Preference = Male  
  - Job portal = `indeed`  
- **Visual:** Bar chart (Company Name vs. Company Size)  
- **Time Visibility:** ⏰ 3 PM – 5 PM IST  

---

### **Task 3: Top 10 Data Roles**
- **Purpose:** Find top companies hiring for Data roles outside Asia  
- **Filters:**  
  - Job title = `Data Engineer` or `Data Scientist`  
  - Country ≠ Asian and not starting with "C"  
  - Preference = Female  
  - Job posting date: 01/01/2023 → 06/01/2023  
  - Qualification = `B.Tech`  
  - Latitude < 10  
- **Visuals:**  
  - Bar chart (Top 10 Companies)  
  - Interactive map  
- **Time Visibility:** ⏰ 3 PM – 5 PM IST  

---

### **Task 4: African Job Insights**
- **Purpose:** Explore job trends in African countries  
- **Filters:**  
  - Qualification = B.Tech / M.Tech / PhD  
  - Work type = Full-time  
  - Country = African  
  - Job title starts with "D"  
  - Preference = Male  
  - Company size > 80,000  
  - Contact person starts with "A"  
  - Job portal = `indeed`  
- **Visuals:**  
  - Bar chart (Company Name vs. Records)  
  - Interactive map  
- **Time Visibility:** ⏰ 3 PM – 6 PM IST  

---

### **Task 5: India & Germany Trends**
- **Purpose:** Compare hiring trends in India vs. Germany  
- **Filters:**  
  - Country = India / Germany  
  - Qualification = B.Tech  
  - Work type = Full-time  
  - Experience > 2 years  
  - Job title = Data Scientist / Art Teacher / Aerospace Engineer  
  - Salary range > $10k  
  - Job posting date < 08/01/2023  
  - Job portal = `indeed`  
  - Preference = Female  
- **Visual:** Bar chart (Orange = India, Green = Germany)  
- **Time Visibility:** ⏰ 3 PM – 5 PM IST  

---

## 🛠️ How to Use

1. **Clone the Repository**
   ```bash
   git clone [repository_url]
   cd job-market-dashboard

2. Run Data Processing Scripts

    Execute Python scripts in /scripts/ to generate filtered CSVs.

3. Open Tableau Workbook

    Load datasets into Tableau (/tableau/)

    Explore or modify the dashboards.

4. Launch Dashboard

    Open index.html in your browser.

    Time-based logic will control which tasks appear.



job-market-dashboard/
│── data/                
│── scripts/            
│── tableau/            
│── index.html            
│── README.md          

📸 Sample Preview


✨ Highlights

✔️ Fully interactive Tableau dashboard
✔️ Region & role-specific job insights
✔️ Smart time-based dashboard visibility
✔️ Easy to integrate into any webpage

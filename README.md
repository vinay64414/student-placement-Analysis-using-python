# student-placement-Analysis-using-python

# 🎓 Student Placement & Career Success Analytics

> **Turning student profiles into career insights — from academic performance and technical skills to employability and salary outcomes.**

## 📌 Project Overview

**Student Placement & Career Success Analytics** is a data analytics project designed to explore the factors associated with students' career preparation, employability, and salary outcomes.

The project analyzes a dataset of **20,000 student records** with **20 attributes**, covering academic performance, technical skills, coding activity, internships, certifications, projects, communication abilities, aptitude scores, GitHub contributions, hackathons, resume quality, mock interviews, placement status, and salary.

The goal is to transform raw student-level data into meaningful insights that can help answer questions such as:

* Which student characteristics are associated with higher salary outcomes?
* How do internships, projects, certifications, and coding activity relate to career outcomes?
* Does academic performance alone explain career success?
* How do communication, aptitude, resume, and mock-interview scores contribute to employability analysis?
* How do different college tiers and specializations compare?
* Which technical and professional skills deserve greater attention during career preparation?

---

## 🎯 Business Problem

Students often focus on individual factors such as CGPA, coding, certifications, or internships without understanding how these factors collectively relate to career outcomes.

This project approaches the problem from a **data-driven perspective** by bringing multiple dimensions of student development together.

### Key Analytical Areas

| Area                | Examples                             |
| ------------------- | ------------------------------------ |
| 📚 Academic         | CGPA, College Tier                   |
| 💻 Technical        | DSA, LeetCode, AI/ML, System Design  |
| 🚀 Experience       | Internships, Projects, Hackathons    |
| 🏆 Profile Building | Certifications, GitHub Contributions |
| 🗣️ Employability   | Communication & Aptitude             |
| 📄 Career Readiness | Resume Score, Mock Interview Score   |
| 💰 Outcome          | Salary (LPA)                         |
| 🎓 Placement        | Placement Status                     |

---

## 📊 Dataset

**Records:** 20,000
**Features:** 20

### Dataset Features

* `Age`
* `Gender`
* `College_Tier`
* `Specialization`
* `CGPA`
* `DSA_Problems_Solved`
* `Internships`
* `Certifications`
* `Projects_Count`
* `Communication_Skills`
* `Aptitude_Test_Score`
* `LeetCode_Rating`
* `GitHub_Contributions`
* `Hackathons_Participated`
* `AI_ML_Skill_Level`
* `System_Design_Knowledge`
* `Resume_Score`
* `Mock_Interview_Score`
* `Placement_Status`
* `Salary_LPA`

---

## 🔍 Analytical Approach

### 1️⃣ Data Understanding

* Explore dataset structure
* Identify numerical and categorical variables
* Review distributions and unique categories
* Check data quality and consistency

### 2️⃣ Data Cleaning

* Check missing values
* Identify duplicates
* Validate data types
* Review potential outliers
* Standardize categorical values where required

### 3️⃣ Exploratory Data Analysis

The analysis explores relationships between:

**Academic Performance**
→ CGPA
→ College Tier
→ Specialization

**Technical Development**
→ DSA Problems
→ LeetCode Rating
→ AI/ML Skill Level
→ System Design Knowledge

**Career Preparation**
→ Internships
→ Projects
→ Certifications
→ Hackathons
→ GitHub Contributions

**Employability**
→ Communication Skills
→ Aptitude Score
→ Resume Score
→ Mock Interview Score

**Career Outcome**
→ Salary in LPA

---

## 📈 Key Dashboard Ideas

The project can be presented through an interactive analytics dashboard containing:

### 🧑‍🎓 Student Profile Overview

* Total Students
* Average CGPA
* Average Certifications
* Average Projects
* Average Internship Experience

### 💻 Technical Skill Analysis

* DSA vs Salary
* LeetCode Rating vs Salary
* AI/ML Skill Level distribution
* System Design Knowledge distribution
* GitHub Contributions vs Career Outcome

### 🚀 Career Readiness

* Internship Experience
* Project Experience
* Certifications
* Hackathon Participation
* Resume Score
* Mock Interview Score

### 💰 Salary Analytics

* Average Salary
* Salary distribution
* Salary by specialization
* Salary by college tier
* Salary vs experience/skill indicators
* High-salary student profile characteristics

---

## 🧠 Example Business Questions

This project is designed around practical analytics questions rather than simply creating charts.

**Q1.** Is higher CGPA associated with higher salary?

**Q2.** Does internship experience show a relationship with salary outcomes?

**Q3.** How does project experience compare with certification count?

**Q4.** Is coding activity reflected in salary differences?

**Q5.** How do LeetCode ratings and DSA problem-solving activity compare?

**Q6.** How do communication and aptitude scores relate to career readiness?

**Q7.** Which specialization has different salary patterns?

**Q8.** How do students from different college tiers compare?

**Q9.** What characteristics are common among students with stronger salary outcomes?

**Q10.** Which combination of technical and professional skills creates a stronger career profile?

---

## 🛠️ Tools & Technologies

| Technology          | Purpose                     |
| ------------------- | --------------------------- |
| 🐍 Python           | Data cleaning & analysis    |
| 🐼 Pandas           | Data manipulation           |
| 🔢 NumPy            | Numerical analysis          |
| 📊 Matplotlib       | Data visualization          |
| 📈 Seaborn          | Statistical visualization   |
| ⚡ Power BI          | Interactive dashboard       |
| 🗃️ SQL             | Data querying & analysis    |
| 📓 Jupyter Notebook | Analysis workflow           |
| 🐙 GitHub           | Version control & portfolio |

---

## 📂 Suggested Project Structure

```text
student-placement-career-success/
│
├── data/
│   └── student_placement_career_success_dataset_2026.csv
│
├── notebooks/
│   └── student_placement_analysis.ipynb
│
├── dashboard/
│   └── student_placement_dashboard.pbix
│
├── visuals/
│   ├── salary_analysis.png
│   ├── skill_analysis.png
│   └── career_readiness.png
│
├── README.md
└── requirements.txt
```

---

## 💡 Project Highlights

### 🔹 Multi-dimensional Career Analysis

Instead of analyzing placement using a single metric, the project combines **academic, technical, professional, and employability indicators**.

### 🔹 Student Career Profiling

The dataset allows students to be analyzed across multiple dimensions such as coding, internships, projects, certifications, communication, and interview readiness.

### 🔹 Salary-Oriented Analytics

`Salary_LPA` provides an opportunity to investigate how different student attributes are associated with compensation outcomes.

### 🔹 Interactive Decision Support

The final dashboard can transform complex student-level information into easy-to-understand insights for students, educators, and placement teams.

---

## ⚠️ Data Quality Note

An important characteristic of the supplied dataset is that `Placement_Status` is recorded as **1 across all 20,000 observations**.

Therefore, this project does **not** treat `Placement_Status` as a meaningful classification target. Instead, the analysis emphasizes **salary patterns, career-readiness indicators, skill development, and student profile comparisons**.

This validation step is important because blindly using a constant target variable could produce misleading conclusions.

---

## 🚀 Future Enhancements

* Build a **Power BI career-readiness dashboard**
* Add correlation and statistical analysis
* Develop salary prediction models
* Create student segmentation using clustering
* Build an interactive **Career Profile Score**
* Compare skill combinations across salary bands
* Add SQL-based analytical queries
* Create an automated student analytics report
* Explore explainable machine-learning models for salary estimation

---

## 📌 Expected Outcome

The final outcome is a **career analytics solution** that converts student data into actionable insights.

Instead of asking:

> **"Who got placed?"**

the project explores a broader question:

> **"What does a career-ready student profile look like, and how are different academic, technical, and professional factors associated with career outcomes?"**

---

## 👨‍💻 Author

### **Vinay Kumar Chatla**

**MBA Graduate | Data Analytics & Business Analytics**

**Core Skills:**
`Excel` · `SQL` · `Power BI` · `Python` · `Data Analysis` · `Data Visualization` · `Business Analytics`

### 🔗 Connect With Me

* 💼 **LinkedIn:** [Vinay Kumar Chatla](https://www.linkedin.com/in/chatlavinaykumar1)
* 🐙 **GitHub:** [vinay64414](https://github.com/vinay64414)

---

## ⭐ If You Find This Project Useful

If this project helped you understand student career analytics, feel free to **⭐ star the repository** and explore the analysis.

**Built with data, curiosity, and a focus on turning numbers into career insights.**

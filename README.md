# AI AND SOCIAL MEDIA IMPACT: STUDENT HEALTH

<div align="center">

  <p><b>An Exploratory Data Analysis (EDA) of 16,000 student records examining the impact of AI tools, social media, sleep, and physical activity on overall student health and well-being.</b></p>
  
  <p>
    <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">
    <img src="https://img.shields.io/badge/Libraries-Pandas%20%7C%20Seaborn%20%7C%20Matplotlib-orange?style=for-the-badge" alt="Libraries">
    <img src="https://img.shields.io/badge/Power%20BI-Desktop-yellow?style=for-the-badge&logo=powerbi&logoColor=white" alt="Power BI">
    <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status">
  </p>

</div>

---

## 🚀 Interactive Dashboard Preview
> *Here is a quick walkthrough of the Power BI dashboard integrating our Python-generated visualizations and dynamic slicers.*

<!-- Replace the link below with your actual GIF or image file name once uploaded to your repo -->
<div align="center">
  <img src="path_to_your_dashboard_animation.gif" alt="Power BI Dashboard Demo" width="800px">
</div>

---

## 📌 Project Overview
This project investigates the dual-edged nature of digital technology in modern student life. By analyzing a comprehensive dataset of **16,000 student records**, this repository provides deep statistical insights and data-driven documentation on how daily screen time, AI tool adoption, and lifestyle habits shape student health outcomes.

---

## 📊 Key Analytical Findings & Visualizations

1. **Physical Activity vs. Physical Health (Scatter Plot):**
   * Proves that increasing physical activity from 0 to 5 hours elevates minimum physical health baselines significantly across all academic tiers.
2. **Correlation Heatmap:**
   * Uncovers a notable negative correlation between daily social media hours and mental/physical health scores, alongside positive relationships between sleep duration and well-being.
3. **Screen Time Across Academic Levels (Violin Plot):**
   * Shows consistent median screen times (4–5 hours daily) across High School, College, and University students.
4. **AI Tool Adoption by Gender (Strip Plot):**
   * Demonstrates equitable technology adoption across all gender categories, with students typically logging usage in full-hour increments.
5. **Age Distribution & KDE:**
   * Highlights core sample uniformity across ages 15 to 23 with clear boundary spikes at ages 14 and 24.
6. **High School Vulnerability & Social Media Overuse:**
   * Confirms the critical need to avoid social media overuse, highlighting that **high school students are particularly vulnerable** to its negative mental health impacts.

---

## 🛠️ Tech Stack & Tools
* **Programming Language:** Python[cite: 3]
* **Data Manipulation & Analysis:** Pandas, NumPy[cite: 3]
* **Data Visualization:** Seaborn, Matplotlib[cite: 3]
* **Business Intelligence & Reporting:** Power BI Desktop (Static image integration & layout alignment)[cite: 3]

---

## 📁 Repository Structure
```text
├── data/
│   └── AI_SocialMedia_Student_Dataset.csv
├── notebooks/
│   └── student_health_eda.ipynb
├── outputs/
│   └── saved_charts/ (High-resolution .png plots)
├── power_bi/
│   └── student_health_dashboard.pbix
└── README.md

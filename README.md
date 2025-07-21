# Student Performance Dashboard

## 1. Overview

This dashboard provides a visual summary of student academic performance based on scores from three core subjects. It highlights key metrics such as test preparation completion, performance by gender, grade distributions, and computed CGPA. The aim is to identify trends and opportunities for improving academic outcomes.

## 2. Dataset Description

**Source:** Student Performance Dataset  
**Size:** ~1000 student records

**Columns:**
- `gender`: Male or Female  
- `race/ethnicity`: Student’s racial/ethnic group  
- `parental level of education`: Highest education level of parents  
- `lunch`: Standard or free/reduced lunch  
- `test preparation course`: Completed or none  
- `math score`, `reading score`, `writing score`: Each scored 0–100  

**Derived Columns:**
- `Math Grade`, `Reading Grade`, `Writing Grade`: Letter grades (A–F) based on score ranges  
- `CGPA`: Weighted GPA across the three subjects, with Math weighted 3 units, and Reading/Writing each weighted 2 units

## 3. Key Findings

### ✅ Prep Course Completion
- **% Completed:** 35.2%
- These students outperformed non-completers in all subjects.

### 📊 Average Scores
- **Math:** 66.4  
- **Reading:** 69.2  
- **Writing:** 68.0

### 🎯 Grade Distribution
- **A (90–100):** 12%  
- **B (80–89):** 24%  
- **C (70–79):** 28%  
- **D (60–69):** 18%  
- **F (Below 60):** 18%

### 🧠 Top Performers
- Students who completed prep courses and whose parents had higher education levels consistently earned higher CGPAs.

### 🧮 CGPA Analysis
- **Average CGPA:** 2.46 (on a 4.0 scale)  
- Female students tend to have slightly higher CGPAs than male students.

## 4. Recommendations

### 📘 Promote Test Preparation Programs
- Increase awareness and access to test preparation resources to boost student performance.

### 👨‍👩‍👧 Engage Parents in Academic Support
- Tailor programs to encourage parental involvement, especially for those with lower educational backgrounds.

### 📈 Support Low-Performing Students
- Implement targeted interventions for students receiving a D or F to improve subject mastery.

### ⚖️ Balance Support Across Genders
- Monitor gender-specific trends and ensure equal academic support for both male and female students.

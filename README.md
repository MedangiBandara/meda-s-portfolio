# 🎓 AI-Assisted Learning and Academic Performance Analysis

## Overview

Artificial Intelligence is transforming how students learn, research, complete assignments, and solve problems. As AI becomes increasingly embedded within higher education, universities face new challenges in ensuring assessments accurately measure student capability.

This project analyses student AI usage and academic performance data to investigate whether AI-assisted learning influences academic outcomes and whether traditional assessment methods remain effective in evaluating genuine student competence.

---

## Business Problem

Should universities redesign traditional assessment systems to more accurately evaluate students' capabilities in AI-assisted learning environments?

The decision-makers include:

- Course Coordinators
- Unit Coordinators
- Academic Staff
- Learning Quality Assurance Teams

The objective is to provide evidence-based insights that support future assessment design decisions.

---

## Project Objectives

- Analyse the impact of AI usage on academic performance
- Evaluate the relationship between study effort and grades
- Understand how students utilise AI tools
- Provide recommendations for assessment redesign
- Demonstrate practical data analytics techniques

---

## Dataset

**Source:** Kaggle - Students AI Usage and Academic Performance Dataset

The dataset contains information relating to:

- Student study habits
- AI usage behaviour
- Academic performance
- Screen time engagement

### Variables Used

| Variable | Description |
|-----------|------------|
| Study Hours Per Day | Daily study effort |
| Purpose of AI Usage | Research, Homework, Coding |
| Grades Before AI Usage | Academic performance before AI adoption |
| Grades After AI Usage | Academic performance after AI adoption |
| Daily Screen Time | Student digital engagement |

---

## Tools Used

| Tool | Purpose |
|--------|---------|
| Excel | Data Cleaning & Statistical Analysis |
| Power BI | Dashboard & Visualisation |
| Python | Data Processing |
| GitHub | Portfolio Documentation |

---

## Data Preparation

The following preprocessing steps were performed:

- Removed duplicate records
- Checked missing values
- Filtered college student records
- Removed non-applicable AI usage observations
- Selected variables relevant to the business problem

Final dataset size: **20 observations**

---

## Analysis Performed

### 1. Hypothesis Testing (Paired T-Test)

Purpose:
Determine whether student grades changed significantly after AI adoption.

### 2. Correlation Analysis

Purpose:
Examine the relationship between study hours and academic performance.

### 3. Descriptive Analytics

Purpose:
Identify the most common uses of AI among students.

---

## Dashboard & Visualisations

### Grade Comparison Before and After AI Usage

![Grade Comparison](visuals/grade_comparison.png)

### Correlation Analysis

![Correlation Analysis](visuals/correlation_analysis.png)

### AI Usage Distribution

![AI Usage Distribution](visuals/ai_usage_distribution.png)

---

## Key Findings

### Academic Performance Improved

| Metric | Result |
|----------|---------|
| Average Grade Before AI | 64.35 |
| Average Grade After AI | 75.00 |
| P-value | 0.00000038 |

A statistically significant increase in grades was observed following AI adoption.

---

### Study Hours Are Not the Only Driver of Performance

| Relationship | Correlation |
|--------------|------------|
| Study Hours vs Grades Before AI | 0.11 |
| Study Hours vs Grades After AI | 0.32 |

The weak correlations suggest that factors beyond study effort may influence academic outcomes.

---

### AI Is Embedded in Student Learning

| Purpose | Percentage |
|----------|-----------|
| Research | 40% |
| Homework | 35% |
| Coding | 25% |

Research was the most common use case for AI tools.

---

## Business Recommendations

Based on the analysis, universities should consider complementing traditional assessments with:

- Project-based assessments
- Industry case studies
- Oral presentations
- Reflective assessments
- Digital portfolios
- Viva examinations

A phased pilot implementation is recommended before institution-wide adoption.

---

## Limitations

- Small sample size (20 observations)
- Findings indicate association, not causation
- Student motivation and prior ability were not measured

---

## Project Structure

```text
AI-Usage-Academic-Performance-Analysis/
│
├── data/
├── visuals/
├── reports/
├── README.md
└── requirements.txt
```

---

## Author

### Medangi Bandara

Master of Management Information Systems (MMIS)
Edith Cowan University

**Interests**
- Data Analytics
- Business Analysis
- Project Management
- Data-Driven Decision Making

### Connect With Me!

- LinkedIn: [(https://www.linkedin.com/in/medangi-bandara/)]

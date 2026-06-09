# AI Usage and Academic Performance Analysis

## Project Overview
This data analytics portfolio project explores whether universities should redesign traditional assessment systems to better evaluate student capability in AI-assisted learning environments.

The analysis investigates how AI usage is associated with academic performance, study effort, and student learning practices using a student AI usage and academic performance dataset from Kaggle.

**Dataset:** [Students AI Usage and Academic Performance](https://www.kaggle.com/datasets/aminasalamt/students-ai-usage-and-academic-performance/data)

---

## Managerial Problem
**Should universities redesign traditional assessment systems to more accurately evaluate students' capabilities in AI-assisted learning environments?**

The key decision-makers are course coordinators, unit coordinators, and lecturers responsible for assessment design, grading, academic integrity, and learning quality assurance.

As generative AI tools become increasingly integrated into higher education, universities need to assess whether traditional exams and written assignments still provide valid evidence of independent learning, critical thinking, and student competence.

---

## Business Context
AI tools can improve learning efficiency and academic performance, but they may also change how students study, complete assignments, and demonstrate knowledge. If assessment systems do not adapt, academic results may not accurately reflect students' real skills, graduate readiness, or ethical learning practices.

This project uses data analysis to support evidence-based decisions about assessment redesign in AI-assisted learning environments.

---

## Tools and Technologies
- Microsoft Excel
- Power BI
- Python
- GitHub

---

## Data Preparation
The dataset was cleaned and filtered to align with the managerial problem. The preparation process included:

- Checking missing values
- Removing duplicate records
- Filtering college students who actively used AI tools
- Removing non-applicable values in `purpose_of_ai_usage`
- Selecting variables relevant to AI-assisted learning and academic performance

The final analysis focused on 20 valid observations.

### Key Variables
| Variable | Purpose |
|---|---|
| `study_hours_per_day` | Measures student study effort |
| `purpose_of_ai_usage` | Identifies how students use AI tools |
| `grades_before_ai_usage` | Academic performance before AI adoption |
| `grades_after_ai_usage` | Academic performance after AI adoption |
| `daily_screen_time` | Student digital engagement indicator |

---

## Analytical Methods

### 1. Paired t-Test
A paired t-test was used to compare students' grades before and after AI usage.

### 2. Correlation Analysis
Pearson correlation analysis was used to examine the relationship between study hours and academic performance before and after AI adoption.

### 3. Descriptive Analysis
Frequency distribution was used to identify the most common purposes of AI usage among students.

---

## Key Findings

### Grade Improvement After AI Usage
The average grade increased from **64.35 before AI usage** to **75.00 after AI usage**.

The paired t-test produced a p-value of **0.00000038258**, which is below the 0.05 significance level. This indicates a statistically significant difference between grades before and after AI usage.

### Study Hours and Academic Performance
| Relationship | Correlation Coefficient | Interpretation |
|---|---:|---|
| Study hours vs grades before AI | 0.11 | Very weak positive relationship |
| Study hours vs grades after AI | 0.32 | Weak positive relationship |

The relationship between study hours and academic performance became slightly stronger after AI adoption. However, both correlations remain weak, meaning study hours alone do not strongly explain academic performance.

### AI Usage Purpose
Students used AI tools mainly for:

- Research: 40%
- Homework: 35%
- Coding: 25%

This suggests that AI is embedded in multiple learning activities, not just used as a supplementary tool.

---

## Visualisations
Suggested visualisations for this project:

1. Comparison of grades before and after AI usage
2. Correlation between study hours and grades before AI usage
3. Correlation between study hours and grades after AI usage
4. Distribution of AI usage purposes

Place exported Excel or Power BI visuals inside the `visuals/` folder and link them in this README.

Example:

```markdown
![Grade Comparison](visuals/grade_comparison.png)
```

---

## Decision Implications
The analysis suggests that universities should not eliminate AI usage. Instead, they should redesign assessment strategies to ensure academic outcomes continue to reflect genuine student capability, critical thinking, and graduate readiness.

Recommended assessment approaches include:

- Project-based assessments
- Industry case studies
- Oral presentations
- Reflective assessments
- Portfolio-based assessments
- Viva examinations

A phased pilot approach is recommended before implementing large-scale assessment changes.

---

## Limitations
This analysis is based on a small sample of 20 valid observations. The findings should not be interpreted as proof that AI usage directly causes grade improvement.

Other factors such as motivation, prior academic ability, digital literacy, learning strategies, and student engagement may also influence academic performance.

---

## Recommendation
Universities should adopt a balanced assessment framework that combines traditional assessment methods with practical, application-based, and reflective evaluation methods. This would help ensure assessment remains valid and reliable in AI-assisted learning environments.


---

## Author
**Medangi Bandara**  
Master of Management Information Systems Student  
Data Analytics | Business Analysis | Project Management

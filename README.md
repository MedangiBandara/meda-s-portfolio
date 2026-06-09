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

## Project Objectives

The main objectives of this project are to:

- Examine whether student grades changed after AI adoption
- Analyse the relationship between study hours and academic performance
- Identify the most common purposes of AI usage among students
- Provide evidence-based recommendations for university assessment redesign
- Demonstrate a complete data analytics workflow for a GitHub portfolio

---

## Tools and Technologies

- Microsoft Excel
- Power BI
- Python
- GitHub

---

## Repository Structure

```text
AI-Usage-Academic-Performance-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── visuals/
│
├── reports/
│
├── README.md
└── requirements.txt
```

---

## Dataset Explanation

The dataset contains student-level information about AI usage, academic performance, study habits, and digital engagement.

For this analysis, the dataset was filtered to focus on college students who actively used AI tools. This ensured the analysis was directly aligned with the managerial problem.

### Key Variables

| Variable | Purpose |
|---|---|
| `study_hours_per_day` | Measures student study effort |
| `purpose_of_ai_usage` | Identifies how students use AI tools |
| `grades_before_ai_usage` | Academic performance before AI adoption |
| `grades_after_ai_usage` | Academic performance after AI adoption |
| `daily_screen_time` | Student digital engagement indicator |

---

## Data Cleaning Workflow

The dataset was cleaned and prepared before analysis to improve reliability and relevance.

The cleaning workflow included:

1. Checking for missing values
2. Removing duplicate records
3. Filtering the dataset to include college students
4. Selecting only students who actively used AI tools
5. Removing non-applicable values in `purpose_of_ai_usage`
6. Selecting variables relevant to the managerial problem
7. Preparing the cleaned dataset for analysis and visualisation

The final analysis focused on **20 valid observations**.

---

## Analysis Steps

### 1. Descriptive Analysis

Descriptive analysis was used to understand how students use AI tools in their academic activities.

The analysis focused on the distribution of AI usage purposes, including research, homework, and coding.

### 2. Hypothesis Testing

A paired t-test was used to compare students' grades before and after AI usage.

This method was selected because the same students' grades were compared across two time points: before AI adoption and after AI adoption.

### 3. Correlation Analysis

Pearson correlation analysis was used to examine the relationship between study hours and academic performance.

The analysis compared:

- Study hours vs grades before AI usage
- Study hours vs grades after AI usage

### 4. Visualisation

Visualisations were created using Excel and Power BI to communicate the results clearly.

The key visualisations include:

- Average grades before and after AI usage
- Correlation between study hours and grades before AI usage
- Correlation between study hours and grades after AI usage
- Distribution of AI usage purposes

---

## Visualisations

Place exported Excel or Power BI visuals inside the `visuals/` folder and link them below.

### Grade Comparison Before and After AI Usage

```markdown
![Grade Comparison](visuals/grade_comparison.png)
```

### Study Hours vs Grades Before AI Usage

```markdown
![Study Hours vs Grades Before AI](visuals/study_hours_before_ai.png)
```

### Study Hours vs Grades After AI Usage

```markdown
![Study Hours vs Grades After AI](visuals/study_hours_after_ai.png)
```

### Distribution of AI Usage Purposes

```markdown
![AI Usage Purpose Distribution](visuals/ai_usage_distribution.png)
```

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

The relationship between study hours and academic performance became slightly stronger after AI adoption. However, both correlations remained weak, meaning study hours alone do not strongly explain academic performance.

### AI Usage Purpose

Students used AI tools mainly for:

| Purpose of AI Usage | Percentage |
|---|---:|
| Research | 40% |
| Homework | 35% |
| Coding | 25% |

This suggests that AI is embedded in multiple learning activities, not just used as a supplementary tool.

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

This analysis is based on a small sample of **20 valid observations**. Therefore, the findings should not be interpreted as proof that AI usage directly causes grade improvement.

Other factors such as motivation, prior academic ability, digital literacy, learning strategies, and student engagement may also influence academic performance.

---

## Recommendation

Universities should adopt a balanced assessment framework that combines traditional assessment methods with practical, application-based, and reflective evaluation methods.

This would help ensure assessment remains valid and reliable in AI-assisted learning environments.

---

## Reproducibility Instructions

To reproduce this analysis:

1. Download the dataset from Kaggle.
2. Save the raw dataset in the `data/raw/` folder.
3. Clean the dataset by removing duplicates, missing values, and non-applicable AI usage records.
4. Save the cleaned dataset in the `data/processed/` folder.
5. Create the required visualisations using Excel or Power BI.
6. Save exported charts in the `visuals/` folder.
7. Update the image links in this README file.

---

## Author

**Medangi Bandara**  
Master of Management Information Systems Student  
Edith Cowan University  

**Interests:** Data-Driven Decision Making | Business Analysis | Data Analytics

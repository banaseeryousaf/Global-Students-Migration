# Global-Students-Migration

PROJECT OVERVIEW

This project explores global student migration, focusing on how students move across countries for higher education. The dataset provides details on countries of origin and destination,scholarship received,enrollment reason and demographic patterns. By analyzing these trends, the project aims to uncover insights into international education flows.

TOOLS USED

- Python (Pandas, NumPy)
- Visualization Libraries (Seaborn, Matplotlib, Plotly)

DATASET

Source : https://www.kaggle.com/datasets/rehanliaqat17/global-student-migration

Key Columns: 'student_id', 'origin_country', 'destination_country',
       'destination_city', 'university_name', 'course_name', 'field_of_study',
       'year_of_enrollment', 'scholarship_received', 'enrollment_reason',
       'graduation_year', 'placement_status', 'placement_country',
       'placement_company', 'starting_salary_usd', 'gpa_or_score',
       'visa_status', 'post_graduation_visa', 'language_proficiency_test',
       'test_score'

STEPS FOLLOWED

1. Data Collection
- Gathered institutional datasets (enrollment, migration records, placement outcomes).
- Ensured sources included both origin and destination details.
2. Data Cleaning & Preparation
- Used Pandas to handle missing values, duplicates, and inconsistent country/institution names.
- Standardized categorical fields (e.g., migration reasons, program names).
3. Created unique identifiers for students.
- Defining Key Columns
- Selected essential fields: Student ID, Origin Country, Destination Country, Institution, Migration Reason, Year, Field of Study, GPA/Salary outcomes.
- Engineered new features (e.g., grouping destinations by region, categorizing reasons).
4. Exploratory Data Analysis (EDA)
- Ran descriptive statistics (counts, averages, percentiles).
- Checked distributions of GPA, salary, or enrollment numbers.
- Identified outliers using IQR and boxplots.
5. Visualization
- Heatmaps: Migration flows between countries.
- Boxplots: GPA/salary distributions of migrant students.
- Trend lines: Year-over-year migration growth.
- Interactive dashboards (Plotly): For dynamic exploration.
6. Interpretation & Insights
- Highlighted top destination countries and institutions.
- Analyzed reasons for migration (education, research, exchange).
- Connected migration trends to placement outcomes (employment, salaries).
7. Documentation & Reporting
- Summarized findings in Markdown reports for clarity.
- Structured insights into professional documentation (tables, charts, narrative).
- Presented actionable recommendations (e.g., which regions attract talent, policy implications).

FILES INCLUDED
- global_student_migration.csv
- project.ipynb

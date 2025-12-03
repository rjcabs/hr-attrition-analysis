# hr-attrition-analysis
A complete HR Attrition Analysis project using Excel, Power Query, and PivotTables.

This project analyzes employee attrition through systematic data preparation, structured grouping of HR metrics, and insightful visual summaries to uncover the key drivers influencing employee turnover.

1. Data Loading using Power Query
    - Imported the dataset into Excel using Power Query for efficient data handling, refreshing, and transformation.
    - Ensured the raw data source is connected for automated updates.
3. Data Transformation & Cleaning (Power Query)
    - Performed a structured data preparation process to improve consistency, reliability, and analytical value.

2.1 Standard Cleaning Steps
    - Trimmed leading/trailing spaces across all text fields.
    - Removed duplicate entries to eliminate redundant records.
    - Converted columns to appropriate data types (text, whole number, decimal, date).
    - Handled missing values:
        - Numerical fields → filled using mean imputation.
        - Text fields → replaced with "Not Provided".
        - Standardized casing by converting all text fields to Capital Case for consistency.
    - Added a new calculated column:
        - AgeStartedWorking = Age – TotalWorkingYears (used to detect early career patterns)
3. Outlier Detection & Data Integrity Check
    - Applied the Interquartile Range (IQR) method to identify:
        - Outliers in numeric variables
        - Potential data quality issues
        - Anomalies that may distort attrition insights
    - Outliers were reviewed for context and retained only when logically valid.
4. Attrition Overview using Pivot Tables
    - Generated a high-level summary of attrition:
        - Overall attrition rate
        - Number of employees leaving vs. staying
    - This served as the foundation for deeper analysis.
5. Strategic Grouping of Fields to Identify Attrition Drivers
Designed intuitive variable groupings to uncover patterns behind employee turnover.

5.1 Personal & Demographic Factors
    - Age
    - AgeStartedWorking
    - Categorical variables:
        - Gender
        - Marital Status
        - Education
        - Education Field

5.2 Compensation & Financial Factors
    - Monthly Income
    - Percent Salary Hike
    - Stock Option Level

5.3 Job-Specific & Role Factors
    - Department
    - Job Role
    - Job Level
    - Business Travel
    - Overtime

5.4 Tenure & Career Progression Factors
    - Years at Company
    - Years in Current Role
    - Years Since Last Promotion
    - Years With Current Manager
    - Total Working Years
    - Number of Companies Worked

5.5 Satisfaction & Environment (Psychological Factors)
    - Environment Satisfaction
    - Job Satisfaction
    - Relationship Satisfaction
    - Job Involvement
    - Work-Life Balance
    - Performance Rating
    - Distance From Home

Each group was analyzed using PivotTables to uncover trends, risk clusters, and correlations with attrition.

6. Consolidation of Results + Executive Summary
    - Combined all findings into a structured overview.
    - Created an executive summary highlighting:
        - Who is leaving
        - Why they are leaving
        - Strategic recommendations for HR and leadership
    - Ensured the final dashboard and summary are aligned with stakeholder needs.


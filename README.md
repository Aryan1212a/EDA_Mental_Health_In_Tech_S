# Mental Health Survey EDA Analysis

**Project Type:** EDA  
**Contribution:** Individual

## Project Overview

This project involves performing an exploratory data analysis (EDA) on a mental health survey dataset focused on the tech industry. The goal is to uncover patterns, trends, and insights related to mental health awareness, treatment-seeking behavior, workplace attitudes, and the impact of company policies on employee mental health.

The analysis utilizes a dataset containing survey responses from tech industry employees, including details about demographics, company characteristics, mental health treatment history, workplace attitudes, and perceived stigma.

## Problem Statement

Mental health issues in the workplace, particularly in the tech industry, have become increasingly recognized as a significant concern affecting employee well-being and productivity. There is a need to understand the factors that influence mental health treatment-seeking behavior, workplace attitudes toward mental health, and the effectiveness of company policies in supporting employee mental health.

The challenge is to analyze survey data to identify patterns and barriers that prevent employees from seeking mental health treatment and to understand how workplace culture and policies impact mental health outcomes.

## Business Objectives

The key business objectives of this analysis are:

* **Identify factors influencing mental health treatment-seeking behavior** in the tech industry
* **Understand the impact of company size, remote work, and workplace policies** on mental health attitudes
* **Analyze demographic patterns** in mental health awareness and treatment
* **Examine workplace stigma and its consequences** on employee mental health
* **Evaluate the effectiveness of current mental health benefits and programs**
* **Provide data-driven recommendations** for improving workplace mental health support

## Dataset

The dataset used for this analysis is a mental health survey focused on the tech industry.

**Source:** Mental Health in Tech Survey  
**Format:** CSV file

### Dataset Characteristics

* **Number of Rows:** [To be filled based on your dataset]
* **Number of Columns:** [To be filled based on your dataset]
* **Survey Focus:** Mental health attitudes and experiences in the tech workplace

### Key Variables

* **Demographics:**
  * `Age`: Age of the respondent
  * `Gender`: Gender identity of the respondent
  * `Country`: Country of residence
  * `state`: State/province (if applicable)

* **Employment Information:**
  * `self_employed`: Whether the respondent is self-employed
  * `no_employees`: Company size (number of employees)
  * `remote_work`: Whether the respondent works remotely
  * `tech_company`: Whether the respondent works for a tech company

* **Mental Health Treatment:**
  * `treatment`: Whether the respondent has sought mental health treatment
  * `family_history`: Family history of mental illness
  * `work_interfere`: How mental health issues interfere with work

* **Workplace Policies and Attitudes:**
  * `benefits`: Whether the company provides mental health benefits
  * `care_options`: Knowledge of care options provided by employer
  * `wellness_program`: Whether the company has discussed mental health in wellness programs
  * `seek_help`: Resources for learning about mental health options
  * `anonymity`: Whether anonymity is protected when using mental health resources
  * `leave`: Ease of taking medical leave for mental health
  * `mental_health_consequence`: Perceived consequences of discussing mental health with employer
  * `phys_health_consequence`: Perceived consequences of discussing physical health with employer
  * `coworkers`: Comfort level discussing mental health with coworkers
  * `supervisor`: Comfort level discussing mental health with supervisor
  * `mental_health_interview`: Would discuss mental health in an interview
  * `phys_health_interview`: Would discuss physical health in an interview
  * `mental_vs_physical`: Views on how employer treats mental vs physical health
  * `obs_consequence`: Observed consequences for coworkers with mental health issues

* **Additional Information:**
  * `comments`: Additional comments from respondents

## Data Wrangling

Initial data preprocessing steps included:

1. **Missing Value Treatment:**
   * Handled missing values in key columns (`state`, `self_employed`, `work_interfere`)
   * Addressed high percentage of missing values in `comments` column
   * Applied appropriate imputation strategies based on variable types

2. **Data Quality Checks:**
   * Verified no duplicate rows were present
   * Cleaned and standardized inconsistent entries in `Gender` column
   * Filtered unrealistic values in `Age` column for accurate analysis

3. **Feature Engineering:**
   * Created categorical groupings for better analysis
   * Standardized response formats across survey questions

## Exploratory Data Analysis (EDA)

The comprehensive EDA revealed several key insights:

### Mental Health Treatment Patterns
* Analysis of treatment-seeking behavior across different demographics
* Correlation between family history and personal treatment decisions
* Impact of age and gender on mental health awareness

### Workplace Environment Impact
* Relationship between company size and mental health support
* Effect of remote work on mental health attitudes
* Influence of tech vs non-tech company environments

### Policy Effectiveness Analysis
* Evaluation of mental health benefits and their utilization
* Assessment of anonymity protections and their impact
* Analysis of wellness program effectiveness

### Stigma and Workplace Culture
* Examination of perceived consequences for discussing mental health
* Comparison of mental health vs physical health treatment in workplace
* Analysis of comfort levels with supervisors and coworkers

### Demographic Insights
* Geographic patterns in mental health attitudes
* Age and gender distribution analysis
* Cross-cultural differences in mental health perception

## Key Findings

[This section should be populated with your specific findings from the analysis, such as:]

* **Treatment Seeking:** X% of respondents have sought mental health treatment
* **Workplace Impact:** Companies with Y characteristics show better mental health outcomes
* **Demographics:** Specific age groups or genders show different patterns
* **Policy Impact:** Certain policies correlate with improved mental health attitudes

## Tools and Libraries Used

* **Python** - Primary programming language
* **pandas** - Data manipulation and analysis
* **numpy** - Numerical computing
* **matplotlib** - Data visualization
* **seaborn** - Statistical data visualization
* **plotly** - Interactive visualizations
* **scipy** - Statistical analysis

## Visualizations Created

The analysis includes various types of visualizations:
* Distribution plots for demographic variables
* Bar charts for categorical variable analysis
* Correlation heatmaps for relationship analysis
* Box plots for comparing groups
* Line charts for trend analysis
* Pie charts for proportion analysis
* 
## How to Run the Analysis

1. **Setup Environment:**
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scipy
   ```

2. **Data Preparation:**
   * Ensure the dataset file is accessible
   * Update file paths in the notebook as needed

3. **Execution:**
   * Open the notebook in Jupyter or Google Colab
   * Run cells sequentially
   * Ensure all dependencies are installed

## Future Work

* Longitudinal analysis to track changes over time
* Comparison with other industry sectors
* Development of predictive models for mental health outcomes
* Integration with additional datasets for deeper insights

## Contribution

This project was completed as an individual contribution for exploratory data analysis practice and mental health awareness in the tech industry.
```
*This analysis is intended for educational and awareness purposes. For professional mental health support, please consult qualified healthcare providers.*

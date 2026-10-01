# Social Media Usage and Student Academic Performance

## Project Overview

This project explores the relationship between students' social media usage patterns and their academic performance.

The dataset includes information about students' demographics, academic level, social media usage patterns, device type, sleep, stress, mental health, and academic performance.

The purpose of this project is to document the dataset clearly and systematically using a README-style metadata format and to provide enough information for other researchers to understand, interpret, and potentially reuse the data.


## Research Question

How is social media usage associated with students' academic performance and well-being?

Possible sub-questions include:

- Does higher daily social media usage correspond to lower GPA?
- Is late-night social media usage associated with sleep duration or sleep quality?
- Is social media usage related to perceived stress or mental health?
- Do usage patterns differ across academic levels or social media platforms?


## Dataset Description

The dataset contains 4,500 student records and 16 variables. Each row represents one student, while each column represents a demographic, behavioral, academic, or well-being-related characteristic.

The dataset includes variables related to:

- Demographic information
- Academic level
- Social media usage
- Primary social media platform
- Device type
- Sleep duration and quality
- Late-night social media use
- Social comparison behavior
- Perceived stress
- Mental health
- Academic performance
- Overall perceived impact of social media


## Data Dictionary

| Variable | Description | Data Type | Measurement Level |
|---|---|---|---|
| Student_ID | Unique identifier for each student | Text | Nominal |
| Age | Age of the student | Numeric | Ratio |
| Gender | Gender of the student | Categorical | Nominal |
| Academic_Level | Student's current academic level | Categorical | Ordinal |
| Primary_Platform | Main social media platform used | Categorical | Nominal |
| Daily_Usage_Hours | Average daily social media usage | Numeric | Ratio |
| Weekend_Extra_Hours | Additional social media usage during weekends | Numeric | Ratio |
| Device_Type | Primary device used for social media | Categorical | Nominal |
| Sleep_Duration_Hours | Average sleep duration | Numeric | Ratio |
| Sleep_Quality_Score | Self-reported sleep quality score | Numeric | Ordinal |
| Late_Night_Usage | Whether the student uses social media late at night | Boolean | Nominal |
| Social_Comparison_Frequency | Frequency of comparing oneself with others on social media | Categorical | Ordinal |
| Perceived_Stress_Score | Student's perceived stress score | Numeric | Scale |
| Mental_Health_Index | Overall mental health index | Numeric | Scale |
| Academic_Performance_GPA | Student's GPA | Numeric | Scale |
| Overall_Impact | Student's perceived overall impact of social media | Categorical | Ordinal |


## Data Source

**Dataset:** Impact of Social Media on Life    
**Source:** Kaggle  
**Creator/Publisher:** Harish Yadav  
**Original URL:** https://www.kaggle.com/datasets/harishyadav0506/impact-of-social-media-on-life
**Accessed:** October 2026  

The dataset contains 4,500 observations and 16 variables related to students' demographics, social media behavior, sleep, stress, mental health, and academic performance.


## Metadata Standard

This project uses the **Data Documentation Initiative (DDI)** as the primary metadata standard.

DDI is designed for documenting research data in the social, behavioral, and economic sciences. It was selected because this dataset includes student demographics, behavioral measures, academic outcomes, and well-being indicators.

Using DDI principles helps describe the dataset in a structured way, including the study context, variables, measurement information, and data characteristics. This makes the dataset easier for other researchers to understand and reuse.

## Data Processing

Before analysis, the dataset was reviewed to understand its structure, variables, and measurement types.

The following steps were considered:

- Reviewing variable names and definitions
- Identifying numerical and categorical variables
- Checking for missing values
- Examining the measurement level of each variable
- Comparing variables measured on different scales
- Normalizing selected numerical variables when appropriate

For some analyses, variables such as Age, Daily_Usage_Hours, Late_Night_Usage, and Academic_Performance_GPA can be normalized to make variables with different measurement scales easier to compare.

## Ethical Considerations

This dataset is used for educational purposes.

Because the data concerns students and includes information about academic performance, stress, mental health, and social media behavior, privacy should be carefully considered.

Personally identifiable information should not be included when sharing or analyzing the dataset. The Student_ID variable should only be treated as an anonymous identifier.

## Limitations

Several limitations should be considered when interpreting this dataset:

- Some variables may be based on self-reported information.
- Self-reported social media usage may not perfectly reflect actual behavior.
- Academic performance can be influenced by many factors beyond social media use.
- Associations between variables do not necessarily indicate causal relationships.
- The dataset may not be representative of all student populations.


## Reflection

### Which metadata standard did you choose and why?

I chose the Data Documentation Initiative (DDI) as the metadata standard. I chose DDI because it is commonly used for social science and behavioral research data, and it fits this dataset well because the data includes students' social media use, academic performance, sleep, stress, and well-being.

### Which template/software did you use?

I used GitHub and Markdown to create the README file. I also used Excel to check the dataset, identify missing values, review different variable types, and normalize selected numerical variables for comparison.

### What was the most challenging part of creating a README file? How did you overcome these obstacles?

The most challenging part was organizing a relatively large dataset and clearly describing all the variables. I overcame this by first reviewing the dataset in Excel, checking the variable types and missing values, and then creating a structured data dictionary in the README file.


## Researcher Information

**Researcher:** Bohan Li  
**Institution:** Teachers College, Columbia University  
**Program:** Learning Analytics  
**ORCID:** https://orcid.org/0009-0007-1807-236X

## DOI

DOI: Not currently assigned.

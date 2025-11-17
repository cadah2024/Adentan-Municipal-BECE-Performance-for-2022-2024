# Adentan-Municipal-BECE-Performance-for-2022-2024
# Table of Content
-  [Overview](https://github.com/cadah2024/Adentan-Municipal-BECE-Performance-for-2022-2024/blob/main/README.md#overview)

-  [Project Objectives](https://github.com/cadah2024/Adentan-Municipal-BECE-Performance-for-2022-2024/blob/main/README.md#project-objectives)

-  [Data Description](https://github.com/cadah2024/Adentan-Municipal-BECE-Performance-for-2022-2024/blob/main/README.md#dataset-description)

-  [Tools Used & Data Cleaning](https://github.com/cadah2024/Adentan-Municipal-BECE-Performance-for-2022-2024/blob/main/README.md#tools-used)

-  [Dashboard](https://github.com/cadah2024/Adentan-Municipal-BECE-Performance-for-2022-2024/blob/main/README.md#dashboard)

-  [Key Features](https://github.com/cadah2024/Adentan-Municipal-BECE-Performance-for-2022-2024/blob/main/README.md#key-features)

-  [Policy Projection & Re-sit Impact](https://github.com/cadah2024/Adentan-Municipal-BECE-Performance-for-2022-2024/blob/main/README.md#policy-projection--re-sit-impact)

-  [Strategic Recommendations](https://github.com/cadah2024/Adentan-Municipal-BECE-Performance-for-2022-2024/blob/main/README.md#strategic-recommendations)

-  [Conclusion](https://github.com/cadah2024/Adentan-Municipal-BECE-Performance-for-2022-2024/blob/main/README.md#conclusions)

-  [Future Improvements](https://github.com/cadah2024/Adentan-Municipal-BECE-Performance-for-2022-2024/blob/main/README.md#future-improvements)

# Overview
The BECE is a major national exam in Ghana that determines student placement into Senior High School (SHS). In recent years, performance challenges especially in Mathematics, Science, and English have sparked national concern.
The new re-sit policy introduced by WAEC allows candidates to retake the BECE, which could reshape performance trends and SHS transition rates.
The project seeks to analyse and predict number of candidates likely to benefit from the re-sit policy 
Our focus for the project is on candidates in Adenta Municipality.
# Project Objectives
The project focuses on the following objectives;
Type of school Comparism which is to identify performance variations in the 2 types of School (Public or Private).
The Gender Analysis also examine differences in performance between male and female candidates.
When it comes to Subject Analysis, it will highlight challenging subjects, focusing on Mathematics, Science, and English.
And finally, the Policy Projection will estimate how many candidates may benefit from the re-sit policy.
# Dataset Description
-  **Source of Data**: Dummy BECE dataset (because actual BECE data is sensitive and also for privacy policy purposes)
-  **Sample Data**: We sample 10 schools in the municipality for the analysis.
-  **Possible References**: GES and WAEC annual reports.
-  **Rows & Columns**: The dataset contains 13 columns and 15000 rows.
-  **Key Fields**: School Name, Year, School Type, Name of Candidate, Index Number, Subject, Gender, Grade per Subject, Aggregate Score, Interpretation, Grade Points, Municipality, Pass/Fail.
## Tools Used
-  Excel (For Data Cleaning)
-  Power BI (For Visualization and Chart Creation)
-  Git/GitHub (For Documentations)
### Data Cleaning
-  Remove duplicates

-  Handle missing values

-  Standardize school names, candidate names

-  Separate grade numbers from text (e.g., "1 - Excellent")

-  Create Pass/Fail column (1–5 = Pass, 6 = Fail)
# Dashboard 
<img width="1167" height="660" alt="Screenshot 2025-11-17 085058" src="https://github.com/user-attachments/assets/359a4a37-d689-4fe6-b2c4-822e5750d0c7" />

# Key Features 
### Overall Performance 

-  87% Passed, 13% Failed among 5,952 candidates.
  
-  Public Schools had 59% of total pass rate, slightly out-performed private schools.
  
-  Average Aggregate is 20, indicating moderate overall performance.

<img width="465" height="233" alt="Screenshot 2025-11-17 103736" src="https://github.com/user-attachments/assets/f96cd0db-7f7b-49a7-8c5c-865940498648" />
<img width="412" height="244" alt="Screenshot 2025-11-17 103757" src="https://github.com/user-attachments/assets/81ea2e2a-1149-4334-be44-62789f19874a" />

### Gender Trends

-  55% of Female candidates passed Slightly outperformed 45% of the Male candidates

-  In terms of STEM Subjects, there is gender gap with male candidates performing marginally better in Mathematics and Science.
   
<img width="479" height="244" alt="Screenshot 2025-11-17 104459" src="https://github.com/user-attachments/assets/7f9928df-ebaf-4aa8-9b54-9c47d8132b6d" /> 
<img width="542" height="323" alt="Screenshot 2025-11-17 104548" src="https://github.com/user-attachments/assets/276e2932-ceb5-4d3e-8fc0-ce63d6b99bb5" />

### Subject Analysis

-  **Top Performing Subjects(),** Religious and Moral Education and ICT (Information Communication Technology)

-  **Challenging Subjects(),** English, Science and Mathematics records highest failure which indicate foundational learning issues.

  <img width="559" height="314" alt="Screenshot 2025-11-17 105717" src="https://github.com/user-attachments/assets/2c8201d8-0b17-4783-bd5a-764bf3f64e39" />

# Policy Projection & Re-sit Impact

### Observations

-  Historical failure data suggests 13% of candidates could benefit from the resit policy.

-  Projected Resit Candidates : approximately 800 students annually in at least one subject.

### Implications

-  Focused support programs (tutorials, remedial classes) can significantly reduce failure rates in core subjects.

# Strategic Recommendations 

-  **Gender-Focused Interventions(),** Encourage female participation in STEM through mentorship and practical science.

-  **Strengthen Foundational Learning(),** Implement early literacy and numeracy intervention programs at the basic level starting JHS 1.
   
-  **Targeted Remedial Support(),**  Introduce extra tuition in Mathematics, English, and Science for students scoring below average.

-  **Teacher Capacity Building(),** Provide continuous professional development in STEM teaching techniques and digital tools for classroom engagement.     

# Conclusions 

BECE outcomes show steady performance but reveal persistent subject-based and gender disparities. Also, the data insights offer a roadmap for policy interventions and teacher training. Therefore, with focused strategies and consistent data monitoring, Adenta Municipal can achieve improved SHS transition rates and overall educational equity.

# Future Improvements 

#### 1. Collect More Detailed Data
To improve the depth of insight;

-  Analyze region e.g Greater Accra
  
-  Include age

#### 2. Include More Historical Data

Instead of analyzing data for only three years;

-  Performance accross 5-10 years

-  Year on year improvement or decline

#### 3. Add More Metrics

Enhance Analysis by calculating;

-  Pass/ Fail Rate per School

-  Mean, Mode & Median for each subject

#### 4. Add Predictive Analysis

If we collect enough data, we can begin predicting:

-  The probability of a student failing a subject

-  Schools likely to underperform in the next BECE

-  Subjects requiring extra teaching resources

#### 5.Perform Root Cause Analysis

After observing performance, investigate:

-  Teacher-to-student ratios

-  Availability of learning resources

-  Why certain schools are failing


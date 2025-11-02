# Student Engagement Insights Dashboard

Generated Data Sources: 
- `student_population.csv` — Student demographics and academic details  
- `research_survey.csv` — Student satisfaction survey data  
- `society_membership.csv` — Society membership and participation status  
- `election_data.csv` — Students’ Union election participation records  

Tools Used: Power BI | Power Query | DAX | Excel  

---

##Project Overview
This project integrates multiple datasets to analyse student engagement at the University of Manchester Students’ Union. It connects data on student demographics, society activity, satisfaction levels, and voting participation in the annual Students’ Union election.

Mock datasets containing 300 students were generated to represent realistic university data, including incomplete and inconsistent values to allow for practical data cleaning and modelling in Power BI. The datasets were modelled using star schema with Student ID as the bridging attribute.

---

##Key Insights

| Metric | Value | Interpretation |
|---------|--------|----------------|
| **Total Students** | 300 | Combined data from all participating schools. |
| **Total Voters** | 149 | 49.67% voter turnout across the student body. |
| **Total Non-Voters** | 151 | Slightly higher than voters, showing room for engagement growth. |
| **Voters Avg. Satisfaction** | 3.69 / 5 | Voters report moderate satisfaction with university life. |
| **Non-Voters Avg. Satisfaction** | 3.80 / 5 | Non-voters are slightly more satisfied overall. |
| **Program Level Split** | 52.33% Undergraduate, 47.67% Postgraduate | Almost equal representation of both groups. |
| **Voters in Societies** | 87 | Indicates stronger engagement among active society members. |
| **Non-Voters in Societies** | 93 | Suggests many socially active students still skip elections. |
| **Top Schools by Total Students** | Social Sciences (49), Computer Science (43), Business School (35), Natural Sciences (34) and Health Sciences (30) | These five schools represent the largest cohorts. |

---

##Summary
This analysis highlights how academic background, social involvement and satisfaction influence student engagement at the University of Manchester. While society membership is linked with higher voting rates, overall election participation remains just below 50%, suggesting opportunities for the Students’ Union to increase voter awareness and involvement.

By integrating and visualising multiple datasets in Power BI, this project demonstrates the value of data-driven insights for improving student participation and community engagement.

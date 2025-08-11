# Kickstarter Analysis-business analysis(interactive dashboard creation using MS Excel, Power Bi)
## Project Objective
A crowdfunding platform like Kickstarter, the objective is to analyze campaign performance, user behavior, and funding trends to provide actionable insights. The goal is to support data-driven decisions that enhance user experience, improve platform features, and increase successful project outcomes.

## Dataset used
- <a href="https://github.com/ashwinireddy09/Business-analysis-Dashboard/blob/main/Crowdfunding_Creator.xlsx">Dataset</a>
- <a href="https://github.com/ashwinireddy09/Business-analysis-Dashboard/blob/main/Crowdfunding_Location.xlsx">Dataset</a>
- <a href="https://github.com/ashwinireddy09/Business-analysis-Dashboard/blob/main/crowdfunding_Category.xlsx">Dataset</a>

## Questions (KPIs)
1. Convert the Date fields to Natural Time ( Currently the dates are in Epoch time Read the attached Artical for Reference on Epoch Time 
             https://www.epochconverter.com/ )
2. Build a Calendar Table using the Date Column Created Date ( Which has Dates from Minimum Dates and Maximum Dates)
  Add all the below Columns in the Calendar Table using the Formulas.

   A.Year

   B.Monthno

   C.Monthfullname

   D.Quarter(Q1,Q2,Q3,Q4)

   E. YearMonth ( YYYY-MMM)

   F. Weekdayno

   G.Weekdayname

   H.FinancialMOnth ( April = FM1, May= FM2  &. March = FM12)

   I. Financial Quarter ( Quarters based on Financial Month FQ-1 . FQ-2..)

4. Build the Data Model using the attached Excel Files.

5. Convert the Goal amount into USD using the Static USD Rate.

6. Projects Overview KPI :
     Total Number of Projects based on outcome 
     Total Number of Projects based on Locations
     Total Number of Projects based on  Category
     Total Number of Projects created by Year , Quarter , Month

7.  Successful Projects
     Amount Raised 
     Number of Backers
     Avg NUmber of Days for successful projects

8.  Top Successful Projects :
    Based on Number of Backers
    Based on Amount Raised.

9. Percentage of Successful Projects overall
   Percentage of Successful Projects  by Category
   Percentage of Successful Projects by Year , Month etc..
   Percentage of Successful projects by Goal Range ( decide the range as per your need )

- Dashboard Interaction <a href="https://github.com/ashwinireddy09/Business-analysis-Dashboard/blob/main/Screenshot%202025-03-04%20115647.png">View Dashboard</a>

   ## Process
   - Verify Data for any missing values and anomalies, and sort out the same.
   - Made sure data is consistent and clean with respect to data type, data format and values used
   - create pivot table according to the question asked.
   - merge all pivot tables into one dashboard and apply slicer to make dynamic.


## Dashboard

## Excel-Dashboard
<img width="1920" height="1080" alt="Screenshot 2025-03-04 115647" src="https://github.com/user-attachments/assets/91e99f64-9be5-4322-a35b-a1e139cd0412" />


## Power Bi
<img width="1279" height="702" alt="Screenshot 2024-12-04 101025" src="https://github.com/user-attachments/assets/6c03473b-c237-473c-80f4-15ece14d924f" />


## Tableau
<img width="1920" height="1080" alt="Screenshot 2025-08-09 222404" src="https://github.com/user-attachments/assets/67eea9ae-2a81-4a28-93da-e6ec97ad2503" />
<img width="1920" height="1080" alt="Screenshot 2025-08-09 222412" src="https://github.com/user-attachments/assets/06c5466e-e377-4964-8870-2a7a00c9d440" />





## Project Insight
- Redesign Platform : Incorporate best practices and user feedback to optimize the crowdfunding website's design and functionality.
- Enhance Campaign Tools : Provide creators with more powerful features to manage, promote, and analyze their crowdfunding initiatives.
- Improve User Experience : Streamline the user journey, from campaign discovery to pledge completion, to increase conversion and engagement.

## Final Conclusion:
This Excel dashboard provides a comprehensive overview of Kickstarter projects by converting epoch dates into a user-friendly calendar format and enriching it with fiscal and chronological insights. It enables interactive analysis of project success based on backers, amount raised, goal ranges, and time-based trends. Key performance indicators highlight project distribution across categories, outcomes, and regions. The dashboard also showcases top-performing projects and success rates by year, month, and financial periods. Currency conversion standardizes data, allowing clear and actionable insights for strategic decision-making.



## Analyzing Student Reading Growth to Evaluate Intervention Effectiveness**

## Project Overview:
Reading proficiency is a critical predictor of academic success. Understanding whether or not interventions drive growth helps schools allocate resources more equitably. 

The project analyzes student reading growth over the course of a school year to evaluate the effectiveness of Multi-Tiered System of Support (MTSS) in elementary education in grades 1-3. Using a simulated dataset, the analysis compares changings in reading level from fall to spring between students who received reading interventions and those who did not. 

This project then examines reading growth by intervention status, grade level, and student attendance to identify patterns that may inform instructional and resource-allocated decisions. Data cleaning, validation, analysis, and visualizations were conducted using Excel.

## Research Question
How effective are reading interventions in improving student reading levels across a school year? 

* How does reading growth vary by grade level?   
* What role does attendance play in reading growth? 

## Data Description 
This project uses a simulated student-level data set representing elementary school students’ reading progress throughout the course of a school year. This dataset includes 40 students across grade levels 1-3 and captures reading progress from Fall (beginning of the year) to Spring (end of the year), along with intervention participation and attendance.   
Variables Included: 

* **student\_id**: to identify each individual student  
* **grade\_level**: student grade level (1-3)  
* **intervention**: Whether or not the student was receiving intervention services.  
* **intervention\_type**: The type of intervention each student was receiving (Small Group, One-on-One, None)  
* **fall\_reading\_level**: The reading level of the student in the beginning of the school year. (1-10)  
* **spring\_reading\_level**: The reading level of the student at the end of the school year.(1-10)  
* **attendance\_rate**: The students rate of attendance over the course of the year in percentages.  
* **reading\_growth:** A calculated metric representing reading progress. Spring level \- Fall level.

**\*No real student data was used.** Values were designed to reflect realistic educational outcomes and variability.

## Data Cleaning/Prep
To ensure that the data was clean and ready for analysis I:

* Implemented Excel Dropdown menus and data validation rules to enforce consistent intervention classifications and reduce entry errors.  
* Applied conditional formatting to categorical variables to improve readability and reduce data entry errors.  
* Enforced intervention logic rules, handled missing values, and calculated reading growth metrics.


## Analysis and Visualizations
This analysis focused on evaluating student reading growth and identifying patterns related to intervention participation, grade level, and attendance.All analysis and visualizations were completed in Excel using pivot tables, calculated fields, and charts to support clear interpretations of results.   
### Average Reading Growth by Intervention Status
![Average Reading Growth by Intervention](charts/avg_reading_growth_by_intervention_status.png)
### Average Reading Growth by Grade Level
![Average Reading Growth by Grade Level](charts/avg_reading_growth_by_grade_level.png)
### Average Reading Growth by Grade Level and Intervention Status
![Average Reading Growth by Grade Level and Intervention Status](charts/avg_reading_growth_by_grade_level.png)
### Average Reading Growth by Attendance
![Average Reading Growth by Attendance](charts/reading_growth_by_attendance.png)

**Reading Growth Calculation:** In order to accurately measure student progress, a metric was created by subtracting the students beginning of the year reading level by their end of year level. This metric served as a primary outcome variable for all subsequent analysis. This project analyzes reading growth by 3 different variables.

* **Reading Growth by Intervention Status:** A pivot chart and column chart was used to compare average reading growth by those students who received reading interventions (either small group or one-on-one) and those who did not. This visualization highlights whether or not interventions are proving to be effective in increasing reading growth.  
* **Reading Growth by Grade Level:** To examine whether or not reading growth varied across grade levels, average reading growth was calculated by grade using a pivot table and a column chart. This helps identify grade level patterns and if intervention impacts are consistent across grade levels.  
* **Reading Growth by Attendance:** A scatter plot was created to explore the relationship between student attendance and reading growth. Attendance rate was plotted on the x-axis and reading growth on the y-axis. This visualization helps provide insight on whether or not attendance is associated with a stronger reading outcome.

## Key Insights

* Students receiving reading interventions demonstrated higher average reading growth than students who did not receive interventions. According to the data, those that received interventions grew an average of 1.6 reading levels whereas students who did not receive interventions grew an average of about 1 reading level. This suggests that MTSS may contribute to improved literacy outcomes over the course of the school year.  
* Reading growth varied by grade level. Earlier grades generally showed stronger gains. This aligns with research indicating that early literacy interventions may have a greater impact when implemented in lower elementary grades.   
* Attendance showed a positive relationship with reading growth. The scatter plot analysis indicates that students with higher attendance rates tended to demonstrate greater reading progress, highlighting attendance as an important contextual factor in literacy development.  
* Not all students receiving interventions experienced the same level of growth. This suggests that interventions may differ by student and some students may require additional or more individualized support.


## Recommendations

* Continue and expand targeted reading interventions, particularly in early elementary grades where growth appears strongest. Prioritizing resources for younger students may yield higher long-term literacy gains.   
* Incorporate attendance data into reading support decisions. Students with lower attendance may benefit from additional monitoring or supplemental strategies to mitigate missed instructional time.   
* Continuously monitor individual student response to intervention.  
* Use data to drive instructional planning. Consistent analysis of reading growth data can help educators and administrators evaluate intervention effectiveness and allocate resources more equitably. 

## Limitations
While this analysis provides useful insights into student reading growth, several limitations should be considered:

* Simulated data: the dataset used in this project is simulated and was designed for portfolio purposes. While values were structured to reflect realistic patterns in elementary education, the findings should be interpreted as illustrative rather than definitive.  
* Limited sample size: This analysis includes a relatively small number of students across three different grade levels. A larger dataset would allow for deeper statistical analysis.   
* Simplified reading level measure: Reading levels were represented using a numeric scale for ease of analysis.  
* Uncontrolled external factors: This analysis does not account for variables such as instructional quality, home literacy environment, English Language Learner status, or socioeconomic factors which can all influence reading outcomes.

## Data and Files**
[Download the Excel Dataset](data/reading_intervention_dataset.xlsx)

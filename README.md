# School_District_Analysis
--- 
## Overview
The client, Maria, has received student data from different school districts. We are tasked to clean and provide a comparative analysis for the different types of schools in the school board. 
---
## Purpose
To analyze student data for different school districts.
---
## Results and Analysis
[Student Data](Resources/new_full_student_data.csv) was used for analysis.
The original dataset was cleaned by removing any null and duplicate values. To simplify filtering, grades were converted from string to integer values by removing "th". Once cleaned, descriptive stats were run on the different numerical columns to gleen any potential insights. Different subsets were also created and compared (e.g. school types, grades) to provide further clarity on the dataset.

### Budget
Public schools tend to have a higher budget, on average, than Charter schools. Public schools had a budget of $911,915 versus $872,625 for Charter schools. 

### Student Enrollment
Some schools seem to have very high enrollment compared to others. Montgomery High School has the highest student enrollments at 2038, almost 12X the enrollment at Chang High School which has the lowest enrollment at 171. 

### Score
When comparing math scores between Charter and Public schools, the data suggests that Charter schools score higher on average than Public schools. This trend can also be seen when comparing grades 9 to 11. Grade 12 seems to be the exception, where Public students scored on average 63.6 compared to 63.8 for Charter students.
However, when comparing reading scores between Charter and Public schools, there does not seem to be a difference. The data shows that students at either school types score an average of 72.
The data also suggests that math scores tend to be lower than reading scores.
---
## Summary Analysis
Public schools tend to have higher budgets than Charter schools. There is great variability on enrollment across the different schools. A further subset to investigate would be enrollment in Public versus Charter schools. Math scores are lower in Public schools compared to Charter schools, but reading scores are on par. This suggests that budget does not have an impact on the education, but perhaps an investigation on the curriculum of Public vs Charter schools might prove insightful. Similarly, it might also be useful to compare math and reading scores by school to investigate if any differences exist at this level.
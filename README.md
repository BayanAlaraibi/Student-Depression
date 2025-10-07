# Student Depression
## Project Overview
This project involves the analysis of 28K student survey responses from different Indian institute, to identify key risk factors for depression among the student population, with a particular focus on academic, lifestyle, and financial stressors. The ultimate goal is to enable early detection and inform targeted mental health interventions.
## Problem Statement
Depression is a critical mental health issue globally, with an alarmingly high reported rate of 58.55% among the surveyed student population in India. This condition negatively impacts academic performance, concentration, and motivation, and in severe cases, can lead to suicidal ideation.
## Main Goal
To enable the early detection of depression in students by identifying significant warning signs and risk factors, forming the basis for effective mental health improvement strategies.
## Objective 
Demographic Analysis: How does depression prevalence vary across different age groups and genders?
Academic Indicators: Is there a relationship between depression status and factors like CGPA, Study Satisfaction, and Academic Pressure?
Student Lifestyle: How do factors such as Sleep Duration, Dietary Habits, and Work/Study Hours correlate with depression status?
Family & Stress Factors: What is the association between depression and Financial Stress, Family History of Mental Illness, and the presence of Suicidal Thoughts?
## Target Audience
Students/ Family/ Instructors 
## Data 
- Dataset taking from kaggle website 
The project utilizes a Student Depression Dataset comprising survey responses focusing on factors that correlate with depression.
Size: 27,901 entries and 18 columns
## Data Dictionary 
<img width="738" height="664" alt="image" src="https://github.com/user-attachments/assets/2cbec6b2-74fb-49c7-a3be-736850a4a54b" />

## Analysis Tools
- Python
- Power BI

## Key Findings 
### Demographics:
Depression by Gender: male were found to have a higher percentage of depression at 55.8%, compared to female at 44.2%.
Top 5 Cities with Depressed Students: The city of Kalyan had the highest number of depressed students (934), followed by Hyderabad (897).

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/87ade3b0-6a6c-4194-b229-9241faf74890" />

Most Affected Age Group: The 19–24 age group was the most affected by both depression (43.54%) and suicidal thoughts 37%. 
<img width="1919" height="1077" alt="image" src="https://github.com/user-attachments/assets/ad717b43-8da1-4ef6-b8c1-71427f3c181e" />


### Academic Indicators:
Study Satisfaction: (ranging from 0, indicating the lowest satisfaction, to 5, indicating the highest). For example, at satisfaction level 0, 60.00% were depressed, which means there is a strong relationship between unhappiness and depression. 

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/99cad793-2d7a-48bc-a4e6-49a583518255" />

Academic Pressure: Students who were "Depressed" represented the largest percentage of students at all levels of academic pressure (from 1 to 5). The highest percentage of depressed students (19.43% of all students) was found in the group reporting the highest academic pressure (level 5), which means a direct relationship here. 

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/cc913847-b036-4e75-91ea-eeed883017ef" />

Academic Pressure and Suicidal Thoughts: There is an increasing trend of suicidal thoughts as the level of academic pressure increases (from 1 to 5). The number of students who reported suicidal thoughts was highest at academic pressure level 5.

<img width="1916" height="1074" alt="image" src="https://github.com/user-attachments/assets/7a634c80-dd6c-4305-bbca-89cc5f38203d" />

### Student Lifestyle:

Study Hours Per Day: more depressed students who study 10-12 hrs. The average daily work/study duration for depressed students is 8 hours.

<img width="1919" height="1077" alt="image" src="https://github.com/user-attachments/assets/b483f91f-3904-4ea5-bae4-55cf93a59285" />

Relationship between Dietary Habits & Depression: The largest percentage of depressed students reported "Unhealthy" dietary habits (44.69%).

<img width="1916" height="1072" alt="image" src="https://github.com/user-attachments/assets/02f9df0f-7870-4952-8e9b-13d871e671f3" />

Sleep Duration: The majority of depressed students reported sleeping "Less than 5 hours" (32.82%).

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/21e0f42e-63de-4a90-9236-299468e80f4a" />

### Family History & Financial Stress:

Family History of Mental Illness: The distribution between students with and without a family history of mental illness was nearly even, with 50.64% of students having a family history of mental illness.

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/813af366-0ac0-4ad9-8c05-3f4ebf92d33a" />

Financial Stress: The highest percentage of depressed students (33.41%) reported the highest level of financial stress (level 5).
Financial Stress and Suicidal Thoughts: The percentage of students reporting suicidal thoughts increases with the level of financial stress. For students at financial stress level 5, 75.71% reported having suicidal thoughts.

<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/bc4e27c2-aef5-43d9-981e-65eafe09f13b" />

Depression Status and Suicidal Thoughts: Among students who reported having suicidal thoughts, 79.05% were also classified as depressed.

<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/8d415216-424a-46aa-80c9-5c121819eee1" />

## Recommendations
Based on the findings, targeted interventions are recommended for key stakeholders:

### For Students:
Prioritize Sleep: Aim for the recommended 7−8 hours of sleep, as insufficient sleep is strongly linked to depression.
Monitor Study Load: Be mindful of study/work hours to prevent burnout.
use a time managment skills: Balance is Key, Not Constant Work ,Long, unbalanced study hours are linked to depression. 

### For Families:
Emphasize the importance of a student's health and happiness over academic performance. 
Financial Dialogue: Proactively discuss and mitigate financial stress, given its strong link to suicidal ideation.
Create a Supportive Environment: Be aware of a family history of mental illness as a potential risk factor.

### For Institutions/Instructors:
Implement Early Screening: Use surveys or tools to monitor students' Study Satisfaction and Academic Pressure levels, which are strong indicators of mental distress.
Promoting sleep and health: Educating students about the importance of sleep and proper nutrition through workshops and campus events

## Limitations
absence of chronological progression of the condition, potential missing aspects of the student's full life complexity, and ignoring other significant factors like social support systems or prior traumatic experiences

## Assumption
The Work Pressure and Job Satisfaction columns are filled with zeros, it might mean the students are not working. 

## Conclusion
Warning Sign: The most powerful warning sign is suicidal thoughts, which are closely linked to depression.
Key Risk Factors:
Age: The 19-24 age group is most vulnerable to depression and suicidal thoughts.
Stress: High levels of academic stress, especially severe financial stress, significantly increase the risk of depression and suicidal thoughts.
Lifestyle: Harmful lifestyle factors include an average of 8 hours of work/study per day, poor sleep (less than 5 hours), and unhealthy eating habits.
By focusing on these specific indicators: age, lifestyle, and stress levels educational institutions and families can implement targeted support systems to intervene before the silent collapse behind success turns into tragedy.

## Resources 
[Student Depression Dataset](https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset)

[Prevalence of Depression Among Indian Population](https://www.ojhas.org/issue72/2019-4-12.html)

[video](https://youtu.be/vKpGddXSYik?si=7eSoacfQ2VD2I0c3)

[Associations Between Academic Stress and Depressive](https://pmc.ncbi.nlm.nih.gov/articles/PMC8906854/)

[Relationship between night-sleep duration and risk for depression](https://pmc.ncbi.nlm.nih.gov/articles/PMC10017495/)












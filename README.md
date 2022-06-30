# NY-Schools-Analyis
This repository contains all the data I used for my analysis on NY High Schools to figure out if there are any biases on standardised testing(SAT)

`ap_2010.csv` contains data of the AP scores for 259 high schools in the different NYC boroughs.

`class_size.csv` contains data of the class size for 27612 classes of the high schools in the different NYC boroughs. 

`demographics.csv` contains data for the different demographics in the high schools.

`graduation.csv` contains data about the graduation of different cohots in NY high schools.

`hs_directory.csv` contains data on the high schools' directory.

`sat_results.csv` contains data on the SAT performance of the high schools in the different NYC boroughs. 

`survey_all.txt` and `survey_d75.txt` contains responses to survey taken by students, teachers and parents.

Below a data dictionary for the survey data.
Field Name	Field Description
dbn	School identification code (district borough number)
sch_type	School type (Elementary, Middle, High, etc)
location	School name
enrollment	Enrollment size
borough	Borough
principal	Principal name
studentsurvey	Only students in grades 6-12 partipate in the student survey. This field indicates whether or not this school serves any students in grades 6-12.
rr_s	Student Response Rate
rr_t	Teacher Response Rate
rr_p	Parent Response Rate
N_s	Number of student respondents
N_t	Number of teacher respondents
N_p	Number of parent respondents
nr_s	Number of eligible students
nr_t	Number of eligible teachers
nr_p	Number of eligible parents
saf_p_10	Safety and Respect score based on parent responses
com_p_10	Communication score based on parent responses
eng_p_10	Engagement score based on parent responses
aca_p_10	Academic expectations score based on parent responses
saf_t_10	Safety and Respect score based on teacher responses
com_t_10	Communication score based on teacher responses
eng_t_10	Engagement score based on teacher responses
aca_t_10	Academic expectations score based on teacher responses
saf_s_10	Safety and Respect score based on student responses
com_s_10	Communication score based on student responses
eng_s_10	Engagement score based on student responses
aca_s_10	Academic expectations score based on student responses
saf_tot_10	Safety and Respect total score
com_tot_10	Communication total score
eng_tot_10	Engagement total score
aca_tot_10	Academic Expectations total score
Field Series	Field Series Description
Column AG through Column CA	These fields provide scores determined for each question based on responses from parents. Question scores are values on a scale of 1 to 10.
Column CB through Column LV	These fields provide percentages of responses from parents for each response option within a question.
Column LW through Column VQ	These fields provide counts of responses from parents for each response option within a question.
Column VR through Column YS	These fields provide scores determined for each question based on responses from teachers. Question scores are values on a scale of 1 to 10.
Column YT through Column AMY	These fields provide percentages of responses from teachers for each response option within a question.
Column AMZ through Column BBE	These fields provide counts of responses from teachers for each response option within a question.
Column BBF through Column BDD	These fields provide scores determined for each question based on responses from students. Question scores are values on a scale of 1 to 10.
Column BDE through Column BNB	These fields provide percentages of responses from students for each response option within a question.
Column BNC through BWZ	These fields provide counts of responses from students for each response option within a question.
Field Convention	Field Convention Description
p_q1	Indicates parent_question 1
p_q1a	Indicates parent_question 1a
p_q1a_1	Indicates parent question_1a_response option 1
p_N_q1_1	Indicates parent_Number of responses_question 1_response option 1
t_q1	Indicates teacher_question 1
t_q1a	Indicates teacher_question 1a
t_q1a_1	Indicates teacher question_1a_response option 1
t_N_q1_1	Indicates teacher_Number of responses_question 1_response option 1
s_q1	Indicates student_question 1
s_q1a	Indicates student_question 1a
s_q1a_1	Indicates student question_1a_response option 1
s_N_q1_1	Indicates student_Number of responses_question 1_response option 1
![image](https://user-images.githubusercontent.com/104331036/176583452-34c7fabe-d171-4d50-b80b-c8009e0ee1ed.png)


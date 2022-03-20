# Data_Analysis_CW
Educational projects

### Goal
The business task is to prepare an analytical report based on the available data, which will later help the producers of educational programs to effectively build a strategy for modernizing and improving courses.
### Tasks
1. Calculation of the potential load on teachers in order to assess the need to expand the staff.
2. Analysis of the quality of course content, where it is necessary to identify problematic modules that may need to be improved.
3. Determine if potential seasonality exists. 

### Codebook
courses.csv contains the following values:

     id - course ID
     title - course name
     field - the field to which the course belongs


students.csv contains the following values:

     id - student ID
     city   - student's city
     birthday - student's birthday


course_contents.csv contains the following values:

     course_id 
     module_number
     module_title
     lesson_number
     lesson_title 
     lesson_token 
     is_video – presence of video (true/false)
     is_homework - presence of homework (true/false)


progresses.csv contains the following values:

     id - progress ID
     student_id - student ID
     course_id - course ID


progress_phases.csv contains the following values:

     progress_id 
     module_number
     lesson_number
     status - the status of the lesson
     start_date 
     finish_date

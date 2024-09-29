# Timetable-Parser
This project involves building a timetable parser that leverages Python’s pandas library to efficiently extract and generate student-specific timetables for my university (JUIT) students.

## Introduction 
JUIT timetable comes in form of a complex excel book with multiple sheets for various senesters, which in turn have multiple lines pertaining to the same day for various batches of the semester. For a student looking for their schedule, this is often hectic and time-consuming. Thus the parser is a handy tool for students looking to simplify the process.

## Instructions
***Initial version 1.0.0***

1. Clone the repository:
 ```bash
    git clone (https://github.com/ekxhta/Timetable-Parser)
 ```
3. Follow the following steps for your copy
   
- For the first run, On execution of the <u>first cell</u>, you are presented with an upload button, wherein you can upload the timetable posted on the site. It must be by the name **ODDSEM2024.xls**.
- Then execute the second cell. (In case you want to see data loaded into the dataframe you can un-comment the last couple lines after the "Display Timetable comment')
- Input your **BTECH Semester** eg. 1, 3, 5, 7 and press enter.
- Following this step, the next step is relatively simple, You can directly jump to the second last cell containing the **batch_tt** function and execute it. To make it more visible you shall find the **Second Last Cell** markdoen above it.
- After the second last cell, execute the last cell.
- Input the day you are interested to see the timetable for and press enter.
- Enter your **Batch** in caps eg. CS311 and press enter.

Here you now have your timetable for the selected day.

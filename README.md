# Term-Project-Fronttable
term-project-fronttable created by GitHub Classroom


## Project Outline
--- 


## 1) Table Creation

### Created 6 tables that contain Fairfield University Course Catalog

   - Location
   
   - Course_Meeting
   
   - Program
   
   - Course
   
   - Instructor
   
   - Course_Offering
   
   
## Table Dictionary

**Location Table** 
  - Location_code- Combination of room and building 
  - Building- School/building in which the course is offered
  - Room- Classroom number

**Course_Meeting Table**
  - CatalogID- Program code and level for course
  - Location- Building and room number of the course
  - StartDateTime- Information on the date and time of first course meeting
  - EndDataTime- Information on the date and time of the last course meeting
  
**Program Table**
  - ProgramCode- Abbrevation of the program name 
  - ProgramName - Name of the program offered
  
**Course Table**
  - CourseTitle- Name of course offered 
  - Description- Description of the course
  - Attributes - Requirements the course fulfills
  - Credits - Number of credits earned in course
  - Coreqs - Classes that must be taken concurrently 
  - Prereqs- Classes that must be taken prior 
  - Fees - Any Fees incurred by the course
  
**Instructor Table**
  - InstructorName - Name of professor teaching the course
  
**Course Offering**
  - CatalogID - Program code and level for course
  - CourseTitle - Name of course offered
  - Section - Different section of the course
  - Meetings  - Day, time, location of where the course meets
  - TimeCodes - Day, time, location of where the course meets
  - Cap - Maximum amount of students that can be enrolled in the course
  - Term - Semester the course is offered 
  - Act - Number of students enrolled in the course
  - Rem - Spots remaining in the course
  - StartDay - Date and time of first class
  - End - Date and time of the last class
 
## 2) DataFrame Creation using Python
  
  - Created 3 dataframes Courses, Course_meeting, and CourseCatalog
  
  - Combined all csv files into one database to simplify data management 
  
  - Since there were duplicate information, decided to only use CourseCatalog data from 2017 to 2018
  
 
## 3) Load Dataframe into SQL Tables

  - Loaded DataSet from Python to SQL
  
  - Ran integrity checks on created tables
  
  
  
## 4) Created Datawarehouse with 5 Dimentional Tables and a Fact Table
  
 ### Tables Created
  
   - LOCATION1
   
   - INSTRUCTOR1
   
   - PROGRAM1
   
   - COURSE1
   
   - COURSE_MEETING1
   
   - Fact table: COURSE_FACTS
   
   
   
## 5) Integrity Checks on Database
   
   - Counted rows in dimention tables
   
   
   
## 6) Queries Answered from our Database
 
  - What is the biggest class enrollment of all available semesters?
  
  - What are all the World Diversity courses of all available semesters?
  
  - What is the average class size for Business Analytic courses?
  
  - What classroom had the most classes held?
  
 
 
 ## 7) Vacuum Data 
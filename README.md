# term-project-fronttable
term-project-fronttable created by GitHub Classroom



Table Dictionary

Location Table
  - Location_code- Combination of room and building 
  - Building- School/building in which the course is offered
  - Room- Classroom number

Course_Meeting Table
  - CatalogID- Program code and level for course
  - Location- Building and room number of the course
  - StartDateTime- Information on the date and time of first course meeting
  - EndDataTime- Information on the date and time of the last course meeting
  
Program Table
  - ProgramCode- Abbrevation of the program name 
  - ProgramName - Name of the program offered
  
Course Table
  - CourseTitle- Name of course offered 
  - Description- Description of the course
  - Attributes - Requirements the course fulfills
  - Credits - Number of credits earned in course
  - Coreqs - Classes that must be taken concurrently 
  - Prereqs- Classes that must be taken prior 
  - Fees - Any Fees incurred by the course
  
Instructor Table
  - InstructorName - Name of professor teaching the course
  
Course Offering
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

# Lab-2-RDM

#You are designing a database for an application that manages courses offered in a university. The program will handle information about the courses, students who take the courses, professors who teach the courses, and departments that offer the courses. The basic business rules for the data:
-	The university has multiple departments. Each department has a list of courses that they are offering for the students. 
    For example, the Information Technology department offers IT5413, IT5423, IT5433, and IT5443; the Computer Science department offers CS1323, CS3443, CS7153, etc.
-	The faculties work for the department will teach the offering courses. In each semester, there could be many sections for the same course that are taught by different faculty members. A section of a course can       only be taught by a single faculty.
For example, Alice Smith works for Information Technology. In Spring 2025 she teaches IT5433 01, IT5433 W01 (01 and W01 are the section codes), and IT7103 01. Also in Spring 2025, Bob Millers works for Information     Technology and teaches IT5433 W02 and IT5433 W03.
-	Each semester, the students take the courses through participating in the offering sections. At the end of the semester, the students will have a final grade assigned to the sections that they take.
For example, student Carol Brown takes IT7103 01 and IT7133 W01 in Fall 2024; and got an A in IT7103 01 and a B in IT7133 W01. Student Daniel Williams takes IT7103 01 and IT5433 W02 in Fall 2024; and got a B in       IT7103 01 and an I in IT5433 W02.
You have drafted a high-level E/R diagram as shown in the next page. Now, your task is to develop a Relational Data Model (RDM) diagram for this database.

[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9272650&assignment_repo_type=AssignmentRepo)
# Lab 1 - Conceptual Modeling using Draw.io
This lab will meet each of the objectives below:
1. Determine appropriate entity structure for relational databases

2. Apply the correct terminology to an ER Model

3. Design an ER model

## Instructions
For this lab, you will practice writing business rules that describe the relationship between entities.  Using the school ER diagram below, you will write out each of the relationships between the entities and recreate a conceptual ER diagram illustrating the relationships represented in the diagram below.

![alt text](https://instructorc.github.io/site/home/images/school_ERD.PNG)

You will record your relationships within this readme file.  When writing down the relationships, make sure to adhere to the following bullet points below.
- Entity names are uppercase and bolded
- The connecting verb is underlined
- Bi-direction of the relationship is represented


Once you have completed the README.md file, you will create an ER Diagram based on the relationships you have identified from the diagram. You will create the ER Diagram using a free web-based tool titled draw.io.  The shapes you will use to create your ER diagram can be found under the "Entity Relation" tab.  Instructions on how to operate draw.io can be found in the assignment resources section below.

## Requirements

### Deliverable 1 (5 Points)
All relationships are identified including the relationships that are formed when identifying the new **associative entities**


### Deliverable 2 (5 Points)
The ReadMe.md file is updated to reflect the relationships. The relationships adhere to the following bullet points below.
- Entity names are uppercase and bolded
- The connecting verb is underlined
- Bi-direction of the relationship is represented


### Deliverable 3 (5 Points)
A conceptual Entity Relationship Diagram(ERD) is created to reflect all entities and relationships identified in the write-up

## Submission Guidelines

For this lab, you will submit 2 items to the repository that has been assigned to you.  The two items that you will need to submit are listed below: 
1. The README.MD file that identifies the various Entities and a brief description of the entity and possible attributes, relationships, and assumptions. 
   1. When identifying relationships be sure to bold and uppercase the entity name, underline the verb and make sure relationships are bi-directional. 
   2. When identifying assumptions, make sure to formulate assumptions based on what is represented in the school ERD with either a Yes or No. 
   3. You can override this README.md file that contains the instructions or extend this README.md file by listing your requirements below the lab Resources section.

2. The draw.io XML file that contains your ER Diagram.  You will also need to take a snippet of the ER Diagram and add it as an image in your Readme file.

Once you have completed both of the items above, you will need to submit the link to your repository for assignment 1 prior to the due date and time listed.  Make sure you receive an email confirmation notifying you that the assignment has been submitted.


## Lab Resources
- [Mark-down Syntax Cheat Sheet](https://enterprise.github.com/downloads/en/markdown-cheatsheet.pdf)
- [Make a ReadMe file Web-based Editor](https://www.makeareadme.com/)
- [Draw.io Web-based diagramming tool](https://app.diagrams.net/)
- [Creating Entity Relationship Diagrams using Draw.io](https://www.youtube.com/watch?v=lAtCySGDD48)


Description:

**STUDENT** - A student is associated with a seat and course. A student consists of student id, student name, student address.

**SEAT** – A seat is associated with a student. A seat consists of seat no, and seat position.

**COURSE** – A course is associated with a student and a section. A course consists of course name and course number.

**SECTION** – A section is associated with course and professor. A section consists of a section number.

**PROFESSOR** – A professor is associated with a section. A professor consists of professor id, professor name, and professor faculty.

**INSTRUCTOR** – A instructor is associated with a course. A instructor consists of instructor no, instructor name, and instructor faculty.

Relationships:

A **STUDENT** can <ins>fill</ins> one and only one **SEAT**, each **SEAT** can be <ins>filled</ins> by one and only one **STUDENT**.

A **STUDENT** can <ins>take</ins> one or more **COURSE**, each **COURSE** can be <ins>taken</ins> by one and only one **STUDENT**.

A **COURSE** <ins>has</ins> one or more **SECTION**, each **SECTION** <ins>has</ins> one or more course.

A **PROFESSOR** can <ins>teach</ins> zero or more **SECTION**, each **SECTION** can be <ins>taught</ins> by zero or more PROFESSOR. 

A **INSTRUCTOR** can <ins>teach</ins> one or more **COURSE**, each **COURSE** can be <ins>taught</ins> by one instructor. 



Assumptions:

Can a **COURSE** exist with zero STUDENTS? Yes
Can a **COURSE** exist with zero STUDENTS? No
Can a **PROFESSOR** teach zero **COURSE**? No
![image](https://user-images.githubusercontent.com/93145401/201398380-5c740cfd-1b6b-4d8b-ac25-2806f2ecfbc2.png)

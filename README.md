# Lab 1 - Conceptual Modeling using Draw.io

<img width="1440" alt="Screenshot 2022-11-11 at 12 08 04 PM" src="https://user-images.githubusercontent.com/93145401/201402726-147bf249-20e7-4270-84c5-940284930c68.png">

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

A **COURSE** <ins>has</ins> one or more **SECTION**, each **SECTION** <ins>has</ins> one or more **COURSE** .

A **PROFESSOR** can <ins>teach</ins> zero or more **SECTION**, each **SECTION** can be <ins>taught</ins> by zero or more **PROFESSOR**. 

A **INSTRUCTOR** can <ins>teach</ins> one or more **COURSE**, each **COURSE** can be <ins>taught</ins> by one **INSTRUCTOR**. 


Assumptions:

Can a **COURSE** exist with zero **STUDENT**? Yes
Can a **COURSE** exist with zero **STUDENT**? No
Can a **PROFESSOR** teach zero **COURSE**? No

[ER_diagram.drawio.xml.zip](https://github.com/LUC-Intro-to-Database-Systems/lab-2-conceptual-modeling-and-er-diagramming-tierneygrabowski/files/9992486/ER_diagram.drawio.xml.zip)

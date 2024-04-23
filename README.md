# SQL

## Content

* [Description](#description)
* [Learning Outcomes](#learning-outcomes)
* [Assignments](#assignments)
* [Contacts](#contacts)
* [Delivery of the Learning Module](#delivery-of-the-learning-module)
* [Schedule](#schedule)
* [Requirements](#requirements)
* [Resources](#resources)
  + [Documents](#documents)
  + [Videos](#videos)
  + [How to get help](#how-to-get-help)
* [Folder Structure](#folder-structure)

## Description

SQL is used across the machine learning pipeline, and a fundamental skill for data scientists to master. This module will focus on the technical skills needed for working with SQL, including flat-file datasets (JSON, CSV) ingestion, query design, and relational database management. Additionally, participants will examine common data management concerns, data access management, and data privacy adherence.

Participants are introduced to data modelling and how to think about the structure of databases. The majority of the module is devoted to learning the necessary commands and their syntax to properly extract information from a database. Participants will learn how to problem solve through live coding. 

## Learning Outcomes
By the end of the module, participants will be able to:

**Week 1:**
1. Describe the structure of a database.
2. Use an export command to save and transport data in CSV and JSON file formats.
3. Use SQL querying and data manipulation techniques to formulate queries for diverse purposes.

**Week 2:**

4. Examine the legal framework around sharing data.
5. Analyze data requirements and work with different stakeholders such as analysts and managers.
6. Use advanced techniques such as String Manipulation, and NULL Management to manipulate results.

## Assignments

Participants should review the [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md) for instructions on how to complete assignments in this module.

There is one assignment and six mandatory homework exercises. Class Participation is considered in the evaluation of the  module. 

1. [Design a Logical Model](https://github.com/UofT-DSI/sql/blob/main/02_assignments/design_a_logical_model.md)

## Contacts

**Questions can be submitted to the #questions channel on Slack**

* Technical Facilitator: 
  * name and pronouns: `<Name>`, `<Pronouns>` 
  * email: `<first_name.last_name@mail.ca>`
* Learning Support Staff: 
  * name and pronouns: `<Name>`, `<Pronouns>` 
  * email: `<first_name.last_name@mail.ca>`

## Delivery of the Learning Module

This module will include live learning sessions and optional, asynchronous work periods. During live learning sessions, the Technical Facilitator will introduce and explain key concepts and demonstrate core skills. Learning is facilitated during this time. Before and after each live learning session, the instructional team will be available for questions related to the core concepts of the module. Optional work periods are to be used to seek help from peers, the Learning Support team, and to work through the homework and assignments in the learning module, with access to live help. Content is not facilitated, but rather this time should be driven by participants. We encourage participants to come to these work periods with questions and problems to work through. 
 
Participants are encouraged to engage actively during the learning module. They key to developing the core skills in each learning module is through practice. The more participants engage in coding along with the instructional team, and applying the skills in each module, the more likely it is that these skills will solidify. 

This module will use a dedicated _Etherboard_ for student collaboration. The link will be provided in the first class. New content will be added by the Technical Facilitator before each session. Each session will consist of slides to introduce topics, live coding to demonstrate the topics, and occasional breakout rooms/live polls to reinforce the topics.  

The technical facilitator will introduce the concepts through a collaborative live coding session using SQLite. The technical facilitator will upload any live coding files to this repository for participants to revisit under `/live_code`.

Participants should follow along with the coding, interact with the study material [SQL for Data Scientists by Renee Teate](https://sqlfordatascientists.com/), and think about the broader data landscape. Participants are encouraged to ask questions throughout. 

## Schedule 

Before First Live Learning Session: Install & Pre-Session [Setup](https://github.com/UofT-DSI/sql/blob/main/05_sql/sqlite_setup/sqlite_setup.md)

||Day 1|Day 2|Day 3|Day 4|Day 5|
|---|---|---|---|---|---|
|Week 1|Live Learning Session 1 Introduction, Data Modelling, Schema Design, Data Structures |Live Learning Session 2 Building Queries: SELECT, FROM, WHERE, CASE, DISTINCT, JOINs|Live Learning Session 3 Essential Techniques: Aggregation Functions, Subqueries, Temporary Tables, CTEs, Datetime Functions |Work Period 1|Work Period 2|

||Day 1|Day 2|Day 3|Day 4|Day 5|
|---|---|---|---|---|---|
|Week 2|Live Learning Session 4 Advanced Techniques: NULL Management, Windowed Functions, String Manipulation, UNION & UNION ALL, INTERSECT & EXCEPT  |Live Learning Session 5 Expanding your Database: INSERT, UPDATE, DELETE, Importing & Exporting Data, CROSS & Self Joins, Views   |Live Learning Session 6 Beyond SQL: Normal Forms, SQL and the Machine Learning pipeline, Broader Data Landscape, Reproducibility, Ethics, SQL in the wild |Work Period 1|Work Period 2|

The schedule above will shift to accommodate a case study during Live Learning Session 3 in Week 2

## Requirements

* Participants are not expected to have any coding experience; the learning content has been designed for beginners.
* Participants are encouraged to ask questions, and collaborate with others to enhance their learning experience.
* Participants must have a computer and an internet connection to participate in online activities.
* Participants must not use generative AI such as ChatGPT to generate code in order to complete assignments. It should be used as a supportive tool to seek out answers to questions you may have.
* We expect Participants to have completed the instructions mentioned in the [onboarding repo](https://github.com/UofT-DSI/onboarding/).
* We encourage participants to default to having their camera on at all times, and turning the camera off only as needed. This will greatly enhance the learning experience for all participants and provides real-time feedback for the instructional team. 

## Resources
Feel free to use the following as resources:

### Documents
- [Cheatsheet](https://www.sqlitetutorial.net/sqlite-cheat-sheet/)
- [W3Schools Tutorial](https://www.w3schools.blog/sqlite-tutorial)

### Videos
- [What is SQLite?](https://www.youtube.com/watch?v=p2tOmltUh34)
- [SQLite Playlist](https://www.youtube.com/playlist?list=PLWENznQwkAoxww-cDEfIJ-uuPDfFwbeiJ)

### How to get help
![image](./steps_to_ask_for_help.png)

<hr>

## Folder Structure

```markdown
.
├── 01_slides
├── 02_assignments
├── 03_homework
├── 04_data
├── 05_sql
├── 06_instructors
├── LICENSE
├── README.md
└── steps_to_ask_for_help.png
```

* **Slides:** Slides were built in markdown. Output files are HTML and PDFs.
* **SQL:** FarmersMarket.db, in-class SQL codes.
* **Data:** Data (csv, json, etc) we'll use for importing.
* **Homework:** Homework to be done after each module.
* **Assignments:** Assignments.
* **Instructors:** This folder guides Technical Facilitators and the Learning Support team on teaching methodologies and content delivery.
* README: This file!
* .gitignore: Files to exclude from this folder, specified by the Technical Facilitator

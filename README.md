                                                                    Software Requirement Specification for Task Portal
Technical Components 
Component 
Tech Stack 
Backend 
Spring Boot 
Frontend 
Angular 
Database 
MySQL 
API 
RESTful services 


1. Introduction 
1.1. Purpose 
This document aims to provide a comprehensive overview of the Task Portal. It will outline the 
system's objectives, features, interfaces, functionalities, operational constraints, and responses to 
external inputs. 
1.2. Scope of Project 
●  Using this software system, administrators will be able to give projects to faculty members 
and track their progress, acting as a portal for task management within the organization. From 
an administrative standpoint, this system will offer a feature-rich dashboard for faculty 
management and task supervision. 
assigned 
● A Tasks can be created and assigned to faculties by administrators. Teachers have access to 
their 
tasks, 
task 
status 
updates, 
and 
feedback 
forms.

3. System Overview 
2.1. Users 
1. Admins: 
● Review and manage task assignments. 
● Create and assign tasks to faculties. 
● Access a comprehensive dashboard for task and faculty management. 
2. Faculties: 
● View assigned tasks. 
● Update task proof and provide feedback. 
2.2. Features 
1. Login and Registration: 
● Admins and faculties can log in with their existing account.


3. Task Management: 
● Admin Dashboard: 
○ Admins can view a summary of all tasks and faculty details. 
○ Admins can open a form to add tasks, entering required fields such as faculty name,dept, task 
title, description, due date, and assign tasks to specific faculties. 
○ Admins can view and manage faculty details, including contact information and task 
assignments. 
● Task Creation: 
○ Admins can create tasks by filling out a form with necessary details (task id, task description,email, 
due date, assigned faculty). 
○ Tasks are assigned to faculties can view through the portal.


5. Faculty Details: 
Admins can view the faculty details through the faculty portal for the detail information about the faculty 
for creating a task.

7. Faculty Dashboard: 
● Faculties can log in to view their assigned tasks. 
● Faculties can see detailed descriptions of each task, including title, description, due date, and status. 
● Faculties can update the proof of their tasks and provide feedback or comments.


3. System Requirements Specification 
3.1. Functional Requirements 
User Management 
● Admin Login: 
○ Admins can log in. 
○ Admins have access to an analytical dashboard and dedicated features. 
● Faculty Login/Register: 
○ Faculties can log in. 
○ Faculties have access to view and manage their assigned tasks.


Task Management 
● Task Creation and Assignment: 
○ Admins can create tasks by filling out a form with appropriate details: 
■ Id 
■ Faculty name 
■ Department 
■ Task title 
■ Task description 
■ Duration 
■ Category 
■ Create task 
○ Tasks are assigned to their id through the portal. 
● Task View and Update: 
○ Faculties can view their assigned tasks. 
○ Faculties can update the status of their tasks and provide feedback. 
Task Details 
● Task Form Fields: 
○ Task Title 
○ Task Description 
○ Duration 
○ Assigned Faculty 
● Task Status: 
○ Faculties can update the current status of their tasks. 
○ Faculties can provide comments or feedback on their tasks. 
Admin Dashboard 
● View Task Summary: 
○ Admins can view a list of all tasks. 
○ Tasks can be filtered by status (verified). 
● View Faculty Details: 
○ Admins can view details of each faculty member, including contact information and 
assigned tasks. 
● Manage Tasks: 
○ Admins can approve or reject task updates with suitable remarks. 
○ Admins can schedule meetings for tasks if needed. 
Analytics Dashboard 
● Task Analytics: 
○ Admins can view the number of tasks by their status. 
○ Admins can view the number of tasks assigned to each faculty. 
○ Admins can view the overall progress of tasks. 
3.2. Non-Functional Requirements 
Performance 
● The system must respond to user actions within 2 seconds to ensure efficient usability. 
● The system must handle a concurrent user load of at least 100 users without significant 
performance degradation. 
Security 
● User data must be encrypted during transmission and storage. 
● Access to sensitive functionalities should be restricted to authorized admin users through 
secure authentication mechanisms. 
Usability 
● The user interface should be intuitive and user-friendly. 
● Clear and concise error messages should be provided to guide users in case of input errors or 
system failures. 
Reliability 
● The system should be available 24/7 with minimal downtime. 
● A backup and recovery mechanism should be in place to prevent data loss in case of system 
failures or crashes. 
Scalability 
● The system should be designed to accommodate an increasing number of users and data 
volume over time. 
● The system should be scalable to support additional features and functionalities as per future 
requirements. 
5. FLOWCHART: 
5.1  Admin’s Analytical Dashboard: 
5.2 Staff Analytical Dashboard: 

5.3 workflow: 
5.4 ER Diagram: 

# HR Service Management Platform (Power Apps)

Enterprise HR request management system built using Power Apps, SharePoint, and Power Automate with approval workflows, KPI tracking, and role-based access.

## Overview

This project is an enterprise-style HR Request Management System built using Microsoft Power Platform. The application allows users to submit HR requests, track progress, manage approvals, and automate HR task creation.

The goal of this project was to design a realistic internal HR platform similar to those used in enterprise environments. The solution focuses on improving HR processes, reducing manual work, and providing clear visibility of requests and tasks.

This project was built as a flagship portfolio piece to demonstrate practical Power Platform development skills, automation design, and user-focused interface design.

## Demo
![hr-platform-demo gif](https://github.com/user-attachments/assets/84fc38cc-2075-44a9-ac6d-271fdc920b3c)

## Why I Built This

In many organisations, HR processes are handled through emails, spreadsheets, or disconnected systems. This project was created to simulate a modern, centralised HR platform that improves visibility, accountability, and efficiency.

## The platform provides

- Structured request management
- Clear approval workflows
- Automated task creation
- Real-time dashboard visibility
- Clean and intuitive user interface

## Features

- HR Request submission
- Onboarding workflow
- Offboarding workflow
- Employee change workflow
- Approval and rejection system
- Role-based access (Admin / HR)
- Automated HR task creation
- KPI tracking dashboard
- Status tracking
- Priority management
- Request filtering and search
- Clean enterprise UI design

## Technologies Used

- Microsoft Power Apps
- Microsoft SharePoint Online
- Microsoft Power Automate
- Microsoft 365

## System Architecture

This solution is built using the Microsoft Power Platform:

User  
↓  
Power Apps (Frontend)  
↓  
SharePoint Lists (Data Storage)  
↓  
Power Automate (Workflow Automation)  
↓  
HR Tasks Created Automatically

## SharePoint Lists

### Requests

Main request list containing:

- Request ID
- Request Type
- Status
- Priority
- Employee Name
- Employee Email
- Department
- Job Title
- Manager Email
- Request Description
- Dates
- Asset Return Required
- HR Tasks

### HR Tasks

Automatically created when requests are approved:

- Task Name
- Assigned To
- Status
- Due Date
- Linked Request ID

## Workflow

1. User submits HR request  
2. Request enters HR Review stage  
3. HR reviews request  
4. HR approves or rejects  
5. If approved, Power Automate creates HR Tasks  
6. Tasks tracked to completion  
7. Request marked completed  

## UI Screens

This solution includes:

- HR Dashboard
- Request List Page
- New Request Form
- Edit Request Form
- Approval Screen
- KPI Dashboard

## Screenshots

### Dashboard
<img width="2555" height="1067" alt="image" src="https://github.com/user-attachments/assets/5475b487-f56a-4b61-bf4f-61422de28053" />

### Requests List
<img width="2518" height="1845" alt="image" src="https://github.com/user-attachments/assets/94495a8a-d3ad-4baa-8b97-4e49a679a3ef" />

### New Request Form
<img width="2538" height="1678" alt="image" src="https://github.com/user-attachments/assets/288ee27c-5973-44af-a23b-8690a819b23b" />

### Edit Request
<img width="2535" height="1282" alt="image" src="https://github.com/user-attachments/assets/fe587266-185e-48bf-a56b-0086ad85f8ac" />

### Approval Screen
<img width="2567" height="1500" alt="image" src="https://github.com/user-attachments/assets/86ed567b-2b96-4459-b103-22ad932bfef9" />

## Key Features Demonstrated

- Power Apps UI Design
- SharePoint Data Architecture
- Power Automate Workflow Automation
- Role-Based Security
- Enterprise UI Design
- KPI Dashboard Design
- Business Process Automation

## Challenges & Learning

During this project, I focused on designing a realistic business workflow and building a clean, user-friendly interface. Key areas of learning included:

- Designing scalable SharePoint data structures
- Creating dynamic dashboards
- Building approval workflows using Power Automate
- Implementing role-based access logic
- Creating consistent UI components across screens

## Future Improvements

- Email Notifications
- SLA Tracking
- Manager Approval Stage
- Reporting Dashboard
- Mobile Layout Optimisation

## Project Goals

The goal of this project was to design and build a realistic HR Service Management platform similar to enterprise service desk tools.

## This project demonstrates

- Business process design
- Automation
- UI/UX design
- Power Platform development
- Real-world use case

## Author

Scott Gardner  
IT Technical Officer  
Power Platform & Cloud Learner

## Project Status

Completed — Flagship Portfolio Project

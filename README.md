# HR Service Management Platform (Power Apps)

Enterprise HR request management system built using Microsoft Power Apps, SharePoint Online, Power Automate, and Microsoft 365.

Designed to streamline HR operations through request management, approval workflows, automated task creation, and KPI tracking within a modern enterprise-style application.

---

## 🎬 Demo

![hr-platform-demo gif](https://github.com/user-attachments/assets/84fc38cc-2075-44a9-ac6d-271fdc920b3c)

---

## 🚀 Overview

The HR Service Management Platform is a Microsoft Power Platform solution designed to centralise and automate internal HR processes.

Built using Power Apps, SharePoint Online, and Power Automate, the application enables employees and HR teams to manage onboarding, offboarding, employee changes, approvals, and operational HR tasks through a responsive enterprise-style interface.

The project was designed to simulate a realistic internal HR operations platform similar to systems used within enterprise and public sector environments.

---

## ✨ Key Features

### HR Request Management
- Submit and manage HR requests
- Track request lifecycle from submission to completion
- Support for multiple HR workflows:
  - Onboarding
  - Offboarding
  - Employee Changes

### Approval Workflows
- HR approval and rejection functionality
- Status tracking across workflow stages
- Automated progression handling
- Structured request management process

### KPI Dashboard & Reporting
- Real-time operational KPI dashboard
- Open request monitoring
- Pending approvals tracking
- Overdue task visibility
- Dashboard summaries and activity insights

### Search & Filtering
- Dynamic search functionality
- Delegation-friendly filtering
- Multi-filter support:
  - Status
  - Priority
  - Request Type
  - Assigned Tasks

### Role-Based Experience
- HR management views
- User-specific request visibility
- Role-based functionality for HR/Admin users

### Responsive Enterprise UI
- Responsive container-based layouts
- Consistent enterprise-style interface
- Sidebar navigation system
- Custom status badges and KPI cards
- Optimised user experience across screen sizes

---

## 🚀 Technical Highlights

- Built using responsive container-based layouts
- Designed scalable SharePoint list architecture
- Implemented approval workflows using Power Automate
- Created delegation-friendly filtering and search functionality
- Developed dynamic KPI dashboards
- Designed reusable UI patterns and consistent styling
- Implemented role-based request visibility
- Built structured HR workflow automation processes

---

## 🛠 Technology Stack

| Technology | Purpose |
|---|---|
| Microsoft Power Apps | Front-end application |
| SharePoint Online | Data storage & management |
| Power Automate | Workflow automation |
| Microsoft 365 | Platform integration |
| Power Fx | Application logic |
| Responsive Containers | Dynamic layouts |

---

## ⚡ Power Automate Integration

The solution includes automated workflows built using Power Automate for:

- Approval notifications
- Email alerts
- Status updates
- Automated HR task creation
- Workflow progression automation

---

## 🏗 System Architecture

```text
User
    ↓
Power Apps Frontend
    ↓
SharePoint Online Lists
    ↓
Power Automate Workflows
    ↓
Automated HR Tasks & Notifications
```

---

## 📂 SharePoint Lists

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
- Request Dates
- Asset Return Required

### HR Tasks
Automatically created when requests are approved:

- Task Name
- Assigned To
- Status
- Due Date
- Linked Request ID

---

## 🔄 Workflow Process

1. User submits HR request  
2. Request enters HR Review stage  
3. HR reviews request  
4. HR approves or rejects request  
5. Power Automate creates HR tasks automatically  
6. Tasks tracked through completion  
7. Request marked as completed  

---

## 📊 Screens Included

### HR Dashboard
Operational overview with KPI reporting and request summaries.

### Request List
Centralised management screen for HR requests and filtering.

### New Request Form
Dynamic request submission experience.

### Edit Request
Request management and workflow progression screen.

### Approval Screen
Approval and rejection interface for HR users.

### KPI Dashboard
Visual KPI tracking and operational reporting.

---

## 📸 Screenshots

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

---

## 💼 Business Value

This platform was designed to improve operational visibility, reduce manual HR administration, and streamline employee request workflows within a Microsoft 365 environment.

The project demonstrates:
- Enterprise application design
- Workflow automation
- Business process optimisation
- Microsoft 365 integration
- User-focused UI/UX design
- Operational reporting and KPI tracking

---

## 🔮 Future Improvements

- Manager approval stage
- SLA tracking
- Reporting dashboard enhancements
- Mobile layout optimisation
- Additional email automation
- Power BI integration
- Teams integration
- Dataverse migration

---

## 🧠 Skills Demonstrated

- Microsoft Power Apps
- SharePoint Online
- Power Automate
- Microsoft 365 Administration
- Power Fx
- Workflow Automation
- Responsive UI Design
- SharePoint Data Architecture
- Enterprise Application Development
- Business Process Automation

---

## 📁 Project Structure

```text
/images
    dashboard.png
    requests-list.png
    new-request-form.png
    edit-request.png
    approval-screen.png
    hr-platform-demo.gif

README.md
```

---

## 👨‍💻 Author

Scott Gardner  
Microsoft 365 & Power Platform Developer

GitHub: https://github.com/scottgard

---

## 📌 Project Status

Actively maintained portfolio project demonstrating Power Platform application development, workflow automation, and enterprise process design.

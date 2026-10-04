IT Asset & Incident Management Portal
📌 Project Overview
The IT Asset & Incident Management Portal is a centralized application developed to streamline and automate IT asset requests and incident management within an organization.

The platform provides a single system where employees can request assets and report incidents, while IT teams can review, approve, route, and fulfill those requests efficiently.

The application is designed to improve IT service delivery by reducing manual tracking, automating approval workflows, and ensuring timely resolution of employee requests.

🎯 Objectives
Centralize IT asset requests and incident reporting.
Simplify the process of requesting equipment and reporting issues.
Automate approval workflows for asset requests.
Improve request tracking and visibility for employees.
Automatically escalate stale or unattended requests.
Reduce manual intervention in IT request handling.
Improve response and fulfillment time.
Provide a structured, self-service IT portal experience.
🚀 Key Features
1. Asset Request Management
Employees can submit requests for IT assets through a custom Record Producer.

Features include:

Submitting new asset requests (laptop, monitor, software license, etc.)
Specifying priority (Low, Medium, High)
Providing business justification
Tracking request status in real time
2. Automated Approval Workflow
The platform includes a Flow Designer workflow that automatically routes requests for manager approval.

The workflow helps in:

Sending approval requests to the right approver
Updating the record automatically when approved or rejected
Sending notifications on approval/rejection
Moving approved requests into fulfillment
3. Incident Reporting & Auto-Routing
Employees can report IT incidents directly through the portal.

The system supports:

Incident creation through Service Catalog
Automatic routing by category (Hardware, Software, Network)
Status tracking through resolution
4. Stale Request Escalation
An automated scheduled job identifies and escalates requests that haven't been addressed.

This helps:

Prevent requests from being forgotten
Automatically bump priority on aging requests
Improve overall response time
5. Self-Service Portal Page
A custom Service Portal widget gives employees visibility into their own requests.

The portal page displays:

Item requested
Priority level
Approval status
Current fulfillment state
Option to submit a new request directly from the page
6. Reports & Dashboard
Built-in reporting gives visibility into request volume and status.

Includes:

Asset requests by priority (pie chart)
Request volume by item type (bar chart)
Status breakdown across the portal
🏗️ Application Components
Data Tables
Asset Request
Automation
Asset Request Approval Flow
Incident Auto-Assignment Flow
Escalate Stale Asset Requests (Scheduled Job)
Auto-Set Requester (Business Rule)
User Interface
Request New Asset (Record Producer)
My Asset Requests (Service Portal Widget)
🔄 Workflow Overview
Employee
   │
   ▼
Submit Asset Request / Report Incident
   │
   ▼
Record Created in Asset Request Table
   │
   ▼
Automatic Approval Routing (Flow Designer)
   │
   ▼
Manager Approves / Rejects
   │
   ▼
Record Updated + Notification Sent
   │
   ▼
IT Team Fulfills Request
   │
   ▼
Employee Views Updated Status on Portal
🛠️ Technologies Used
ServiceNow
ServiceNow Studio
ServiceNow Flow Designer
ServiceNow Service Portal (AngularJS Widgets)
ServiceNow Scheduled Jobs
ServiceNow Business Rules & Client Scripts
GitHub
Git Version Control
📂 Project Structure
IT Asset & Incident Management Portal
│
├── Data
│   └── Asset Request
│
├── Automation
│   ├── Asset Request Approval Flow
│   ├── Incident Auto-Assignment Flow
│   ├── Escalate Stale Asset Requests
│   └── Auto-Set Requester
│
├── User Interface
│   ├── Request New Asset (Record Producer)
│   └── My Asset Requests (Service Portal Widget)
│
└── Source Control
    └── GitHub Repository
🔐 Source Control
The project is directly connected to GitHub using ServiceNow's native Source Control integration.

This is used to:

Automatically version-control every table, flow, and script.
Maintain full commit history of application changes.
Store the actual ServiceNow application files, not just exports.
Support collaboration and future development.
⚙️ Installation and Setup
To work with this project:

Open the ServiceNow instance.
Navigate to ServiceNow Studio.
Open the IT Asset & Incident Management Portal application.
Review the configured tables, flows, and widgets.
Pull the latest application version from GitHub if required.
Test the Record Producer and Approval Flow end-to-end.
👨‍💻 Development Workflow
Develop Application
        │
        ▼
Test Application Features
        │
        ▼
Commit Changes (via ServiceNow Source Control)
        │
        ▼
Push to GitHub
        │
        ▼
Maintain Version History
📈 Benefits
The IT Asset & Incident Management Portal provides several benefits:

Centralized IT request management.
Faster approval and fulfillment cycles.
Automated approval routing.
Reduced manual follow-up on stale requests.
Better request tracking and transparency.
Improved employee self-service experience.
Clear visibility into request status at every stage.
🔮 Future Enhancements
Possible future enhancements include:

Auto-advance request state after approval.
SLA tracking and breach notifications.
Performance Analytics dashboard.
Mobile-friendly portal view.
AI-based incident categorization.
Automated asset inventory sync.
🎥 Demo Video
[Watch the full walkthrough](Coming soon)

📄 License
This project is developed for educational and academic purposes.

👤 Author
 PALAGIRI TOUSSIF AHMED

⭐ IT Asset & Incident Management Portal
A centralized, automated platform for managing IT asset requests, approvals, incidents, and self-service tracking.

# Patch-Management-with-WSUS-
Operated and configured patch management with WSUS on windows server 2016 to ensure performance of pc is not affected by updates and users can keep using their end points without interruptions or unsupervised security breaches. 

Project Overview
This project demonstrates the deployment and management of Windows Server Update Services (WSUS) to centrally manage and automate patch distribution within an organization. WSUS allows administrators to approve, schedule, and monitor software updates for Windows servers and clients to maintain security and compliance.

Features
- Centralized patch management for Windows OS and Microsoft products.

- Ability to approve or decline updates before deployment.

- Targeting updates by computer groups.

- Reporting and monitoring update status.

- Scheduling update downloads and installations.

System Requirements
- Windows Server 2016 or later.

- Sufficient disk space for update storage.

- Active Directory domain environment.

Setup Instructions
1. Install the WSUS role via Server Manager.

2. Configure WSUS server synchronization settings.

3. Create computer groups to organize clients.

4. Approve updates and assign to groups.

5. Configure Group Policy for client update settings.

6. Monitor WSUS reports to ensure compliance.

Testing
- Verify client computers report to WSUS.

- Confirm updates are installed as approved.

- Review update compliance reports.

Notes
- Regularly synchronize WSUS with Microsoft Update.

Clean up WSUS database periodically to maintain performance.


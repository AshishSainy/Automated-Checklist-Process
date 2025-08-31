# Automated-Checklist-Process

**Problem Statement** 
The 'Risk and Compliance' team currently performs quality checks using an Excel-based checklist template. While functional, this approach presents several limitations:
Lack of Flexibility: Adding or removing checklist items requires manual updates to the Excel template, which must then be redistributed to all auditors to ensure consistency.
Version Control Issues: Ensuring every auditor is using the latest version of the checklist is difficult, leading to potential discrepancies in audits.
Reporting Challenges: Once completed checklists are submitted to a shared folder, aggregating and analyzing results becomes cumbersome and time-consuming.

**Proposed Solution**
A more robust and scalable solution is needed to address these issues. Ideally, this solution should:
Allow dynamic updates to the checklist without manual redistribution.
Ensure version control and consistency across all users.
Enable centralized data collection and automated reporting for better insights and efficiency.

**Problem Statement** 
You can see existing checklist in file named 'OLD_Excel_Checklist'.

**Final Solution**
1. Move to a Web-Based Checklist System
Tools: Microsoft Power Apps.
Benefits:
Centralized checklist management.
Real-time updates and version control.
Easy access from any device.
You can view the created power app code,screenshots,formulas used in folder 'Checklist App'.

2. Use SharePoint or Microsoft Lists
Benefits:
Seamless integration with Microsoft 365.
Version history and permissions control.
Can be customized with Power Automate for workflows and notifications.
You can view the created SP list and rules used in folder 'SP List'

3. Automated Reporting with Power BI
Connect the checklist data source , SharePoint to Power BI.
Create dashboards for audit results, trends, and compliance metrics.
Schedule refreshes and share reports securely.
You can view the Power bi dashboard screenshots and dax used in folder 'Power BI'
Built-in data validation and user tracking.

## AI-Powered Student Scholarship Eligibility Automation System

## Overview:

The AI-Powered Student Scholarship Eligibility Automation System is a workflow automation project designed to automate the student scholarship verification process using n8n and Google Workspace integrations.The system collects student information such as Name, Gender, DOB, Course, Branch, Year of Study, CGPA, Phone Number, and Email through Google Forms, stores and organizes the data in Google Sheets, and automatically evaluates scholarship eligibility based on predefined academic criteria.
Using conditional workflow automation, students with a CGPA greater than or equal to 9.5 automatically receive an eligibility confirmation email, while other students receive a non-eligibility notification email.

## Features:
1.Automatic scholarship eligibility checking
2.CGPA-based filtering and evaluation
3.Automated approval and rejection email notifications
4.Google Sheets integration
5.Conditional workflow automation
6.Professional HTML email templates

## Tech Stack: 

1.n8n : Workflow automation platform used to automate repetitive processes.
2.Google Forms API : Used to collect student scholarship application data.
3.Google Sheets API : Used to store and manage student information.
4.Google Sheets Trigger (n8n) :– Automatically triggers workflow when a new response is added.
5.IF Node (n8n): Applies conditional logic to determine scholarship eligibility based on CGPA.
6.Gmail API : Sends automated eligibility and rejection emails to students.


## Workflow Architecture : 
Google Form → Google Sheets → Google Sheets Trigger → IF Condition Check → Eligible / Not Eligible Email

## Demo

### Eligible Student Email

![Eligible Email](Scholarship%20workflow%20automation%20output1.png)

---

### Non-Eligible Student Email

![Rejection Email](Scholarship%20workflow%20automation%20output2.png)

---

### Workflow Demo

![Workflow Demo](Scholarship%20workflow%20automation%20video.gif)

## Challenges Solved

- Eliminated manual scholarship eligibility verification.
- Reduced repetitive student screening work.
- Automated approval and rejection email responses.
- Improved response speed and workflow efficiency.
- Minimized human errors in eligibility checking.

---

## Use Cases

- Educational institutions
- Scholarship verification systems
- Student eligibility automation
- Academic workflow management

---

## Author

Developed by Sathwik

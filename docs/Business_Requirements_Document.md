Business Requirements Document: Student Success Plan (SSP) Navigator
1. Introduction & Problem Statement
1.1 Project Vision
To create a unified and proactive academic support platform on Salesforce that empowers university advisors to identify at-risk students early, manage personalized success plans, and coordinate intervention efforts across campus, ultimately boosting student retention and graduation rates.
1.2 Problem Statement
Universities struggle with student attrition due to a lack of coordinated, proactive systems for identifying and supporting at-risk students. Key information signaling a student is struggling (poor attendance, low grades, lack of engagement) is often siloed in disparate systems or not captured at all. This leads to reactive interventions, a lack of coordination between support staff, and an inability to scale support resources effectively to those who need them most.
2. Project Goals & Scope
2.1 Project Goals
Increase Student Retention: Proactively identify and support at-risk students to reduce dropout rates.
Improve Advisor Efficiency: Automate administrative tasks and provide a 360-degree student view to allow advisors to focus on high-value interactions.
Enhance Cross-Campus Collaboration: Create a single source of truth for all staff involved in a student's support network.
Enable Data-Driven Decisions: Provide administrators with actionable dashboards to measure the effectiveness of student success initiatives.
2.2 Scope
In Scope (Minimum Viable Product):
A centralized data model for Students, Success Plans, Goals, and Interactions.
An automated "Early Alert" system triggered by faculty.
Automated task reminders for advisor follow-ups.
A custom "Student 360" Lightning Web Component for advisors.
Dashboards for Advisors and Administrators.
Out of Scope (Future Enhancements):
External-facing portal for students to view their own success plans.
Direct integration with the university's Learning Management System (LMS).
Mobile app notifications for students.
3. Stakeholder Analysis
Persona / Role	Key Needs & Motivations	Role in SSP Navigator System
Academic Advisor	A single view of their students, automated reminders, efficient note-taking.	Primary User. Creates/manages SSPs, logs interactions, tracks goals.
Faculty Member	A quick and simple way to flag a student who is struggling in their class.	Initiator. Creates "Academic Alerts" to trigger the SSP process.
Dean / Administrator	High-level data on retention trends, effectiveness of support programs, and resource use.	Executive User. Views dashboards and reports to make strategic decisions.
4. Business Process Mapping
4.1 As-Is (Current) Process
The current process is manual and disconnected. A faculty member typically emails an advisor about a struggling student. The advisor then tracks this information in a personal spreadsheet or email folder. There is no central tracking, no automated follow-up, and no visibility for university leadership.
![alt text](./images/As_Is_Process.png)
4.2 To-Be (Future) Process
The new process will be streamlined and automated within Salesforce. A faculty member will submit a formal "Academic Alert." This action will automatically notify the correct advisor and prompt the creation of a Student Success Plan, all of which is tracked centrally and is visible to relevant stakeholders.
![alt text](./images/To_Be_Process.png)
5. Industry-specific Use Case Analysis
The SSP Navigator application will support the following core use cases for the higher education industry:
Use Case 1: Early Alert & Triage
A faculty member identifies a student missing assignments and creates an "Academic Alert" in Salesforce.
The system automatically assigns the alert to the student's primary advisor and notifies them.
The advisor reviews the alert within the context of the student's full profile to determine the severity and next steps.
Use Case 2: Centralized Success Plan Management
The advisor creates a formal Student Success Plan (SSP) linked to the student's record.
The advisor defines specific, actionable "Intervention Goals" within the SSP, such as "Attend weekly writing center tutoring."
Each goal can be assigned to a specific owner (e.g., the tutoring center staff) and has a target date.
Use Case 3: Coordinated Interaction & Progress Tracking
Every interaction (advising meeting, tutoring session) is logged against the SSP, creating a running history of support.
Automated reminders ensure that goal owners follow up with the student at scheduled intervals.
The advisor can track the status of all goals in one place, providing a holistic view of the student's progress.
6. AppExchange Exploration
A review of the AppExchange shows that Salesforce offers the Education Cloud with a product called Student Success Hub (formerly Advisor Link). This is a comprehensive, enterprise-level solution for student support.
Justification for Custom Build:
Learning & Demonstration: For the purpose of the TCS Last Mile program, building a custom solution from the ground up demonstrates a deep understanding of core Salesforce platform capabilities (data modeling, automation, LWC).
Tailored MVP: Our custom "SSP Navigator" will be a lightweight, highly tailored solution focused specifically on the MVP requirements defined in this document, avoiding the complexity of a full enterprise product.
Cost-Effectiveness: A custom build avoids the significant licensing costs associated with managed packages like the Student Success Hub, which is a realistic consideration for smaller institutions.

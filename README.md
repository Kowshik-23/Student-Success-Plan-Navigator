Student Success Plan (SSP) Navigator - Salesforce Application
🚀 Project Vision: Proactively Boosting Student Retention
The Student Success Plan (SSP) Navigator is a custom Salesforce application built to address one of the most significant challenges in higher education: student attrition. Developed as a final project for the TCS Last Mile program, this solution transforms a university's student support model from a reactive, disconnected process into a proactive, collaborative, and data-driven ecosystem.
The core mission of this project is to ensure no student falls through the cracks by empowering academic advisors with the tools they need to identify at-risk students early, manage personalized interventions, and measure the impact of their support efforts.
🔍 The Problem: A Disconnected Support Network
Universities invest heavily in student support services, but their effectiveness is often hampered by systemic issues:
Siloed Information: Critical indicators of a struggling student—poor attendance, low midterm grades, or disengagement—are scattered across emails, spreadsheets, and disparate university systems.
Reactive Interventions: Without early warnings, advisors often only learn of a student's difficulties after a critical failure, when the opportunity for meaningful intervention is limited.
Lack of Coordination: A student may interact with a writing tutor, a financial aid counselor, and an academic advisor, with none of the staff having a complete, holistic view of the student's situation and the support they are receiving.
Administrative Burden: Advisors spend too much time hunting for information and manually tracking interactions, reducing their capacity for high-value, face-to-face student guidance.
✨ The Solution: A Centralized Hub for Student Success
The SSP Navigator provides a comprehensive solution built on the Salesforce platform, featuring:
1. Early Alert & Triage System
Faculty members can quickly raise an "Academic Alert" for any student showing signs of struggle. This single action triggers an automated workflow, instantly notifying the student's primary advisor and prompting them to assess the situation. This replaces unreliable email chains with a formal, trackable process.
2. Holistic Student 360-Degree View
At the heart of the application is a custom "Student 360 Success Snapshot" built with Lightning Web Components. This powerful dashboard, embedded on the student's record, provides advisors with an at-a-glance view of:
The student's academic standing and key information.
The status of their active Student Success Plan (SSP).
A clear list of intervention goals and their progress.
A timeline of recent interactions with all campus support services.
3. Structured & Actionable Success Plans
When an intervention is needed, advisors can create a formal Student Success Plan (SSP). This is not just a static document; it's a dynamic record that allows advisors to:
Define specific, measurable goals (e.g., "Improve GPA to 2.5," "Attend weekly tutoring").
Assign ownership of goals to relevant campus staff (like a tutor or counselor).
Set check-in dates to ensure consistent follow-up, driven by automated task reminders.
4. Data-Driven Institutional Insights
The application provides powerful analytics for university leadership. Dashboards visualize key metrics such as at-risk student trends by major, the most common intervention reasons, and the correlation between support engagement and retention, allowing for strategic, data-informed decisions about resource allocation.
🛠️ Technology & Key Salesforce Concepts
This project leverages a blend of declarative and programmatic tools to deliver a robust and scalable solution:
Salesforce Flow: The engine behind the application, automating everything from alert notifications and task creation to proactive deadline reminders.
Custom Data Model: A relational data model built with custom objects to accurately represent the relationships between Students, Success Plans, Goals, and Interactions.
Lightning Web Components (LWC) & Apex: A modern, responsive user interface is powered by LWC, with server-side logic handled by Apex controllers to ensure efficient data handling and a seamless user experience.
Security & Sharing Model: A carefully configured security model using Profiles, Permission Sets, and OWD ensures that sensitive student data is only accessible to authorized personnel.
Bug Tracking and Reporting in Jira
This guide outlines logging, tracking, and reporting bugs in Jira for effective defect management.
Bug Tracking Process

Log Bugs:
Create issues in Jira using the bug report template (see templates/bug-report-template.md).
Include: Summary, description, steps to reproduce, expected/actual results, priority, and attachments.


Assign and Track:
Assign bugs to developers in To Do status.
Update status (e.g., In Progress, Done) as resolution progresses.


Prioritize:
Use priority levels (e.g., Critical, High, Medium, Low) based on impact and urgency.
Example: Payment failure = Critical; UI misalignment = Low.


Link to Test Cases:
Link bugs to test cases for traceability (e.g., "TC004_Payment_Success").


Monitor Progress:
Use Jira dashboards to track open, in-progress, and resolved bugs.
Filter by component, sprint, or priority.



Reporting in Jira

Define Report Goals:
Track defect trends, resolution times, and test progress.
Example: Identify recurring payment bugs.


Key Reports:
Bug Summary: Number of open/resolved bugs per module.
Defect Trend: Bugs reported vs. resolved over time.
Test Coverage: Bugs linked to requirements/test cases.


Customization:
Create filters (e.g., "Bugs in Payment Module") for targeted reporting.
Use JQL (e.g., project = ECOM AND issuetype = Bug AND status = Open).


Stakeholder Communication:
Export reports as CSV/PDF for sprint reviews.
Share dashboards with PMs and developers.



Example

Bug Report: "Payment fails with invalid card" (Critical, linked to TC005).
Report: 10 bugs in payment module, 8 resolved, 2 critical open.

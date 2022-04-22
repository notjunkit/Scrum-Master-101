# Ayam Scrum Master 
- [Scrum Events](#scrum-events)
  - [Sprint Planning](#sprint-planning)
  - [Daily Scrum](#daily-scrum)
  - [Sprint Review](#sprint-review)
  - [Sprint Retrospective](#sprint-retrospective)
- [Bi-Weekly Update](#bi-weekly-update)
- [Atlassian Setup](#atlassian-setup)
  - [Jira Ground Zero](#jira-ground-zero)
  - [Confluence Ground Zero](#confluence-ground-zero)
- [References](#references)

---
## Scrum Events

### Sprint Planning
_The agenda for the meeting_

1. Sprint goal - Business and technical goal for the sprint. Allows us to negotiate the scope of the sprint in case we find out that something is more complex than expected during the sprint
2. Sprint backlog - Measure user stories with Fibonacci sequence
3. Team commitment - Clarify if anyone is unavailable during the sprint . Is someone on holiday? Are there public holidays during the sprint?
4.	Team velocity - Approximate appetite of user stories able to commit for the sprint based on resources availability
5.	Individual capacity - Developers and QA will be full time, meanwhile leads will be half-time operational work

### Daily Scrum
_The agenda for the meeting_

1.	What did I do yesterday?
2.	What will I do today?
3.	What will I achieve today?
4.	Anything blocking your progress?
    - Person-in-charge
    - Issue statement
    - Target resolution date

### Sprint Review
_The agenda for the meeting_

1.	Informal session between scrum team, PO and/or stakeholders to show on the work completed to ensure Sprint Goal is met
2.	State what will (and what will not) be demonstrated
3.	Scrum team to demo new functionality
4.	Product Owner and/or stakeholders to provide feedback (if any) 

### Sprint Retrospective
_The agenda for the meeting_

1. **Loved** - List what you loved about your work
2. **Longed** for - List what you wished you had while working
3. **Loathed** - List what you didn't like about your work
4. **Learned** - List what you learned
5. Action items - How should the next sprint play out? This will determine corrective actions to take in the next sprint, preventing the same mistakes from occurring, and making successful actions a repeatable outcome.

---
## Bi-Weekly Update
_The agenda for the meeting_

1. Participants list
2. Action items
3. Decisions
4. Development
    - Current sprint scope / progress
    - Next sprint scope / progress
    - Sprint report (velocity chart, burndown chart, defect trend)
    - Risk register/assessment
5. Release Preparation
    - Operational preparation and progress
    - Technical preparation and overall timeline
8. Release Done
    - KPI
    - Escaped defects

---
## Atlassian Setup

### Jira Ground Zero
What to do if you had Jira (cloud version)



1. Audit log retention period 
    - Jira Settings > Troubleshooting and Support > Audit Log > Audit Log Settings > Retention Period
2. Look and feel 
    - Jira Settings > System > User Interface > Look and Feel > Logo
    - Jira Settings > System > User Interface > Look and Feel > Navigation Colors
4. Attachment file size limit
    - Jira Settings > System > Advanced > Attachments > Attachment Size
6. Jira software configuration – parallel sprints
    - This is the setup to allow parallel sprints in the case that we have a sprint that has yet to be closed due to conflict (such as code conflict, requirement conflict, dropping the sprint) while we need to start a new sprint.
    - Jira Settings > Products > Jira Software Configuration > Features > Parallel Sprints
8. Project workflow creation
    - Jira Settings > Issues > Workflows
    - Jira Settings > Issues > Workflow schemes
9. Custom fields creation
    - Jira Settings > Issues > Fields > Custom Fields
11. Permission scheme creation
    - Note that most of the permissions will have Project Role with “atlassian-addons-project-access”, do not remove or change anything regarding this project role as it is a default project role. It might cause system bugs.
    - Jira Settings > Issues > Issue Attributes > Permission Schemes

---
### Confluence Ground Zero
What to do if you have Confluence (cloud version)

1. Attachment file size limit
    - Confluence Settings > Configuration > General Configuration > Attachment Settings
2. Default space permission
    - Confluence Settings > Security > Space Permissions
3. Look and feel
    - Confluence Settings > Look and Feel > Site Logo and Favicon
    - Confluence Settings > Look and Feel > Colour Scheme
4. Audit log retention period
    - Confluence Settings > Administration > Audit Log > Audit Log Settings > Retention Period

## References
1. https://scrumguides.org/scrum-guide.html
2. https://cucumber.io/docs/gherkin/
3. https://www.planitpoker.com/
4. https://www.atlassian.com/git/tutorials/comparing-workflows
5. https://confluence.atlassian.com/alldoc/
6. https://support.atlassian.com/jira-cloud-administration/resources/
7. https://developer.atlassian.com/cloud/
8. https://confluence.atlassian.com/enterprise/atlassian-enterprise-documentation-587303541.html
9. https://support.atlassian.com/jira-cloud-administration/docs/manage-project-permissions/
10. https://support.atlassian.com/jira-cloud-administration/docs/permissions-for-company-managed-projects/#Permissionsforcompanymanagedprojects-data
11. https://community.atlassian.com/t5/Adaptavist-questions/How-to-make-a-field-required-during-a-workflow-transition/qaq-p/589657

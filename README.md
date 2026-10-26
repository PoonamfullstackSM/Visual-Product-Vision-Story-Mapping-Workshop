Packers & Movers Agile Project – Jira & Scrum Practice 🚚
A hands-on Agile project demonstrating how a Scrum Team can organize, estimate, plan, track, and inspect work for a Packers & Movers service platform using Jira. The project includes a product backlog, epics and user stories, story-point estimation, bug tracking, custom fields, and sprint reports.

The artifacts illustrate practical use of Jira to support Scrum planning, transparency, inspection, and adaptation.
🎯 Project Overview
The goal of this project is to organize the work needed for a Packers & Movers platform and demonstrate how Agile practices can help a team turn product needs into manageable work items.

The project uses Jira to:
- Structure product work through epics, user stories, and subtasks.
- Refine and prioritize the product backlog.
- Estimate work using story points and Planning Poker.
- Track bugs using a saved filter.
- Capture business-value information in a custom field.
- Review sprint progress using velocity and burndown charts.
🗂️ Project Artifacts
1. Epics and User Stories
The backlog is organized into epics and related user stories. The examples shown include:
- Product management
  - Basic service selection
  - Photo uploads
  - Simplified inventory
- Login/Registration
  - Login with email
  - User registration
  - Log out
- Home page
  - Verifiable contact
  - Customer panel
These work items show how larger product capabilities can be broken down into smaller pieces of work for planning and delivery.
2. User Stories and Acceptance Criteria
User stories describe functionality from a user's or administrator's perspective. One example is the ability for an administrator to upload Packers & Movers service types so that users can browse available services.

The associated acceptance criteria cover points such as:
- A service-type upload form is available.
- Relevant service fields, such as name, description, and image, are available.
- An upload action is provided.
- A success message appears after a successful upload.
- The uploaded service is visible on the home page.
- Mandatory fields are available.
- Non-functional requirements include browser compatibility, security testing, and performance testing.
Acceptance criteria help clarify expectations and provide a shared understanding of what needs to be verified.
3. Subtasks Under a User Story
A user story is broken down into implementation and verification tasks. The example includes:
- UI/UX front-end development
- API development
- Database creation
- Front-end and back-end integration
- Test-case creation
- End-to-end testing
- Unit testing
- Deployment
- Documentation
- User acceptance testing (UAT)
This breakdown helps the team make the work more visible and coordinate implementation and testing.
4. Product Backlog Refinement
The Jira backlog contains work items with story-point estimates, priorities, and labels or categories. Refinement helps the team clarify requirements, discuss scope, identify dependencies, and prepare items for future sprint planning.

The screenshots show example stories with estimates of 13, 8, 5, and 3 story points. These are estimates for the displayed work items, not a recommended target for every sprint.
5. Sprint Planning
The Jira sprint-planning view is used to select work from the backlog for a sprint. The team can review the items and their estimates before confirming the sprint plan.

Sprint planning should account for the Sprint Goal, the team's capacity, the work's complexity, and relevant dependencies. The amount selected should be based on the team's understanding and available capacity rather than a fixed story-point target.
6. Estimation Using Scrumpy Planning Poker
The project uses the Scrumpy Planning Poker app in Jira to support collaborative estimation. Team members vote on a story-point value, review the voting results, and discuss differences in estimates.

Planning Poker supports shared understanding of the work. The estimate should reflect the team's discussion and judgment, rather than being treated as a measure of individual performance.
7. Custom Field – Business Value
A custom single-choice field named Business value is configured in Jira with selectable options numbered 1 through 5.

This field can be used to record a business-value assessment for work items. The team should agree on what each option means and apply the scale consistently. A custom field by itself does not calculate or guarantee backlog priority; prioritization should consider business value alongside other relevant factors.
8. Bug Filter
A saved Jira filter named Bug filter is configured with criteria shown in the screenshot:
- Space: Packers and Movers
- Assignee: Poonam
- Type: Bug
- Sprint: CKERSPA Sprint 2
The filter displays matching bug work items, including an example bug titled “On resetting password confirmation mail is not going to the user.”

Saved filters help teams focus on a relevant subset of work. The results depend on the filter criteria and the work-item data currently in Jira.
9. Pie Chart Gadget for Bug Filter
A Jira dashboard pie-chart gadget is configured to visualize data associated with the bug filter and the Business value field.

The screenshot shows 2 total issues divided into two displayed values: one issue with value 5 and one issue with no value (None). This highlights both the distribution of the selected field and the presence of an item that has not been assigned a business-value option.

Dashboard charts are useful for visibility, but their meaning depends on the filter, field, and data represented.
10. Velocity Chart
The velocity chart compares committed and completed story points across two sprints:
Sprint	Commitment	Completed
CKERSPA Sprint 1	21	21
CKERSPA Sprint 2	8	8


The average completed work across these two sprints is 14.5 story points per sprint.

Interpretation: The chart can help the team discuss recent delivery and inform future forecasting. The change from 21 to 8 story points is a signal to inspect, not proof of lower productivity. Possible discussion points include team capacity, work complexity, availability, and the work selected for each sprint. Since the chart covers only two sprints, the average is an early reference point rather than a reliable long-term forecast.
11. Burndown Chart
The burndown chart visualizes remaining work over the course of a sprint. In the supplied chart, remaining work declines from approximately 21 story points to zero by the end of the displayed period. Flat sections indicate periods when the remaining-work line did not change.

Interpretation: The team can investigate flat periods during daily coordination and consider whether blockers, dependencies, work not yet reaching completion, or delayed chart updates explain the pattern. The Developers can then adapt their plan to address impediments and improve progress toward the Sprint Goal.
12. Metric Interpretation Report
The accompanying report explains how velocity and burndown charts can support the Scrum Team's Inspect and Adapt approach.
- Inspect: Review the charts and discuss what the data shows without jumping to conclusions.
- Understand: Explore the context behind changes in completed work or periods with no visible burndown.
- Adapt: Agree on practical actions, such as improving dependency coordination, splitting work into smaller pieces, or clarifying completion criteria.
- Follow up: Review later sprints to see whether the actions helped delivery and the team's way of working.
The Sprint Review provides an opportunity to inspect the product outcome and discuss stakeholder feedback. The Sprint Retrospective focuses on inspecting how the Sprint went and identifying improvements to try.
Key principle: Velocity supports forecasting, while burndown helps visualize remaining work during a sprint. These metrics should support team learning and realistic planning—not comparisons between teams or pressure on Developers to increase story points.

🔄 Scrum and Jira Workflow Demonstrated
1. Organize the product backlog into epics and user stories.
2. Add clear descriptions and acceptance criteria.
3. Break stories into implementation and testing subtasks where useful.
4. Refine backlog items and discuss priority, value, and dependencies.
5. Estimate work collaboratively using Planning Poker.
6. Select appropriate backlog items during Sprint Planning.
7. Track bugs using saved Jira filters.
8. Use a dashboard gadget to visualize selected bug data.
9. Inspect sprint results using velocity and burndown charts.
10. Discuss findings and agree on improvements through the Scrum Team's Inspect and Adapt cycle.
🛠️ Tools & Practices
- Jira – Backlog organization, work-item tracking, sprint planning, filters, custom fields, dashboards, and reports
- Scrumpy Planning Poker – Collaborative story-point estimation
- Epics, user stories, and subtasks – Structuring and decomposing product work
- Acceptance criteria – Clarifying expected behavior and verification
- Story points – Supporting estimation and sprint forecasting
- Business Value custom field – Recording a selectable business-value assessment
- Bug filter and pie-chart gadget – Filtering and visualizing bug-related information
- Velocity and burndown charts – Supporting sprint inspection and planning discussions
📁 Repository Structure
The following structure reflects the supplied artifact names. Keep these files in the repository alongside this README if you want the embedded links and image references to work.
.
├── Burndown Chart.jpg
├── Created Bug Filter.jpg
├── Created custom field- Business Value.PNG
├── Epics and user stories.PNG
├── Estimation using Scrumpy Planning Poker.PNG
├── Metric Interpretation Report.pdf
├── Refined Product Backlogs.jpg
├── Subtasks under user story.PNG
├── User Story & Acceptance Criteria.PNG
├── Using Pie Chart Gadget for Bug Filter.jpg
├── Velocity Chart.PNG
└── README.md
👩‍💻 My Role
Scrum Master / Agile project practitioner

Through this hands-on project, I practiced and documented:
- Organizing epics, user stories, and subtasks in Jira.
- Writing user stories and acceptance criteria.
- Supporting backlog refinement and sprint planning.
- Using Planning Poker to facilitate collaborative estimation.
- Configuring a custom Business Value field.
- Creating a saved filter to view relevant bugs.
- Using a pie-chart gadget to visualize issue data.
- Interpreting velocity and burndown charts.
- Using metrics to encourage discussion, forecasting, and continuous improvement.
📌 Project Outcome
The project brings together backlog structure, estimation, tracking, and reporting in Jira:

Epics → User Stories → Acceptance Criteria & Subtasks → Backlog Refinement → Sprint Planning → Bug Tracking → Sprint Metrics → Inspect and Adapt

The artifacts demonstrate practical familiarity with Jira and core Scrum activities, while showing how work-item data and sprint reports can support transparency, shared understanding, and continuous improvement.
📚 Key Learnings
- Breaking product capabilities into manageable epics, stories, and subtasks.
- Writing acceptance criteria that make expected behavior clearer.
- Supporting collaborative estimation through Planning Poker.
- Preparing and refining backlog items before sprint planning.
- Using Jira filters and dashboard gadgets to make selected work visible.
- Understanding what velocity and burndown charts show—and what they do not prove.
- Using sprint metrics as conversation starters rather than individual or team performance targets.
- Connecting inspection of delivery data with practical improvement actions.
⚠️ Project Note
This is a hands-on portfolio and practice project based on the supplied Jira screenshots and metric report. The screenshots show a simulated Packers & Movers project and a limited set of work items and sprint results. Metric interpretations are based on the supplied charts and should be considered in context; the two-sprint velocity average is not sufficient on its own to establish a reliable long-term forecast.

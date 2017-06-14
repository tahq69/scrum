# [Scrum](https://www.visualstudio.com/en-us/docs/work/guidance/scrum-process)

![scrum process plan](https://www.visualstudio.com/en-us/docs/work/guidance/_img/scrum-process-plan-wits.png)

To plan a software project and track software defects using Scrum, teams use the product backlog item (PBI) and bug work item types (WITs). To gain insight into a portfolio of features, scenarios, or user experiences, product owners and program managers can map PBIs and bugs to features. When teams work in sprints, they define tasks which automatically link to PBIs and bugs.

## Define PBIs and bugs

When you define a product backlog item, you want to focus on the value that your customers will receive and avoid descriptions of how your team will develop the feature. The product owner can prioritize your product backlog based on each item's business value, effort, and relative dependency on other backlog items.

By prioritizing the PBIs and bugs on the backlog page (which is captured in the Backlog Priority field), product owners can indicate which items should be given higher priority.

- BPIs Description 
> rovide enough detail for estimating how much work will be required to implement the item. Focus on who the feature is for, what users want to accomplish, and why. Don't describe how the feature should be developed. Do provide sufficient details so that your team can write tasks and test cases to implement the item.

- BPIs Acceptance Criteria
>Define what "Done" means by describing the criteria that the team should use to verify whether the PBI or the bug fix has been fully implemented.
Before work begins on a PBI or bug, describe the criteria for customer acceptance as clearly as possible. Conversations between the team and customers to determine the acceptance criteria helps ensure a common understanding within the team to meet customers' expectations. The acceptance criteria can be used as the basis for acceptance tests so that the team can more effectively evaluate whether an item has been satisfactorily completed.

## Workflow states

![BPI](https://www.visualstudio.com/en-us/docs/work/guidance/_img/alm_pt_scrum_wf_pbi.png) ![Bug](https://www.visualstudio.com/en-us/docs/work/guidance/_img/alm_pt_scrum_wf_bug.png) ![Task](https://www.visualstudio.com/en-us/docs/work/guidance/_img/alm_pt_scrum_wf_task.png)

### PBIs and bugs follow this typical workflow progression:

- The product owner creates a PBI or a tester creates a bug in the **New** state with the default reason, **New backlog item**
- The product owner moves the item to **Approved** after it is sufficiently described and ready for the team to estimate the level of effort. Most of the time, items near the top of the Product Backlog are in the Approved state, while items toward the middle and bottom are in a New state
- The team updates the status to **Committed** when they decide to complete the work during the sprint
- The item is moved to the **Done** state when the team has completed all its associated tasks and the product owner agrees that it has been implemented according to the Acceptance Criteria.

>For example, a developer can define tasks to implement PBIs, and a tester can define tasks to write and run test cases.

## Try this next

Use your [task board](https://www.visualstudio.com/en-us/docs/work/scrum/task-board) during your daily scrum meetings to perform these tasks:

![task board](https://www.visualstudio.com/en-us/docs/work/scrum/_img/alm_tb_grp_people_all.png)

- Update task status and remaining work (daily updates of remaining work leads to smoother burndown charts)
- Review progress with the team during the daily Scrum meetings
- Update items and address uncompleted work at the close of the sprint
- Also, you can monitor your [burndown chart](https://www.visualstudio.com/en-us/docs/work/scrum/sprint-burndown) to make sure your team remains on track throughout the sprint.

![burndown chart](https://www.visualstudio.com/en-us/docs/work/scrum/_img/alm_sb_riskmitigation.png)


Updating Remaining Work, preferably prior to the daily Scrum meeting, helps the team stay informed of the progress being made. It also ensures a smoother burndown chart.

Each team member can review the tasks they've worked on and estimate the work remaining. If they've discovered that it's taking longer than expected to complete, they should increase the remaining work for the task. Remaining work should always reflect exactly how much work the team member estimates is remaining to complete the task.

![updater work](https://www.visualstudio.com/en-us/docs/work/scrum/_img/alm_tb_updaterwork.png)

## Dashboards

Teams can create multiple dashboards to share information, access quick links and other functions, and view status, progress, and trends. Easily add and rearrange widgets on the dashboard to show recent changes made to source control folders, build status, and charts created from work item queries.

![widgets](https://www.visualstudio.com/en-us/docs/report/_img/dashboard-view-with-widgets.png)

# Thanks
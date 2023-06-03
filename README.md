# ADOWiki

This Wiki Page provides a introduction into some of the components used in Azure DevOps that 

## Azure DevOps Backlogs

Backlogs are a fundamental feature of Azure DevOps which we will be using in this class consistently for a list of tasks/user stories which are to be completed for the studio badging and for other projects as part of the badges. Backlogs help assist teams in managing and organizing their work effectively. A backlog serves as a central repository for capturing, prioritizing, and tracking all the tasks, user stories, and bugs related to a software development project. Within the Backlogs, each item can be further defined by adding details such as a title, description, acceptance criteria, and effort estimation and this is one of the primary ways we will be using ADO Backlogs in CSS390.

### Setting up the Software Engineering Studio Backlog:

Information about how to set up your Software Engineering Studio Backlog can be found in the following (video)[https://uw.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=20cd3ec8-d297-45c3-a0e7-ae4400578fd9] at a timestamp of 1:35:00


## Azure DevOps Team Dashboard Setup and Usage

Azure DevOps provides powerful dashboards to track various metrics related to team productivity, task status, and project progress. The "Team 02 Metrics" dashboard example includes several different metrics and visualizations. Here's a guide on how to set up a similar dashboard and understand the various filters and metrics.

### Setting up the Team Dashboard:

1. **Create a new dashboard**: From your project homepage, navigate to `Overview > Dashboards`. Click on the `New Dashboard` button. Provide a name for your dashboard (e.g., "Team 02 Metrics") and a description if you want.

2. **Add widgets**: After your dashboard is created, you can start adding widgets. Click the `Edit` button on your new dashboard and then `Add Widget`. A widget catalog will appear from where you can select different types of widgets according to your needs. For instance, if you want to track the status of work items, you can add a "Work Items" widget.

3. **Configure widgets**: Each widget will have different configurations according to its type. After adding a widget, click on the `Configure` icon (usually appears as a gear symbol) on the widget to set it up. 

### Understanding Dashboard Filters and Metrics:

Let's dive into some of the specific items present in your "Team 02 Metrics" dashboard to understand what they represent and how to configure them:

1. **Work Items Status**: These are a set of widgets that display counts of work items based on different criteria. The red or yellow backgrounds are used to highlight issues that need immediate attention. 

    - *Active Tasks without Original Estimation*: This shows the number of active tasks that do not have an original estimate of work.

    - *Unassigned Work Items*: This represents the work items that are not yet assigned to any team member.

    - *Tasks with Incorrect Iteration Path*: This shows the number of tasks that are assigned to incorrect or invalid iteration paths.

2. **Sprint 1 - Team 02**: This displays a brief summary of the ongoing sprint including start and end date, hours spent, and the status of user stories.

3. **Items By State Chart**: This chart visualizes the distribution of work items by their current state (e.g., new, active, closed).

4. **Work Items by Assigned To Chart**: This chart shows the distribution of work items by assignee.

5. **Team Sprint Status**: This section includes two burndown charts, one for user stories and one for tasks. Burndown charts show how quickly you and your team are burning through your customer's user stories. 

6. **Team 01 Cycle Time**: This chart represents the average time it takes for your team to complete work items. Cycle time is only calculated for completed work.

7. **Velocity**: This chart represents the count of work items completed in the last iteration and the average velocity of your team. Velocity is a measure of the amount of work a Team can tackle during a single Sprint and is the key metric in Scrum.

Remember, your dashboard is a dynamic tool. You can continue to customize and change it as your project progresses or as your team's needs change. It's designed to give a quick overview and insight into your team's progress and performance.

## Azure DevOps Boards Setup and Usage

Azure DevOps Boards are a valuable tool for visualizing the work in your pipeline, understanding the state of your tasks, and optimizing your flow. Here's a tutorial on how to set up and use Boards in Azure DevOps.

### Setting up the Boards:

1. **Access the Boards**: From your project homepage, navigate to `Boards > Boards`. 

2. **Create a new Board**: A new board can be created in the context of a team. From the `Boards` overview page, select the team from the dropdown menu and click `New board`. Enter the board's name, and it will be created within the selected team's scope. For example, for the CSS 390 project "Dates" you can create a board named "Dates".

3. **Configure Columns**: Azure DevOps allows you to customize the columns on your board. Each column represents a stage in your workflow. Click `Column options` on the top right, and then `+ New column` to add a new column. Columns can be renamed, removed, or reordered to match your workflow.

4. **Adding Work Items**: Click on the `+ New item` button (found in the "New" column) to create a new work item. Fill in the details and click `Save & Close`.

### Using the Boards:

1. **Moving Work Items**: Each work item can be dragged and dropped into different columns as they progress through stages. For example, once an item has been researched and is ready for development, you can drag it from the "Researching" column to the "Coding via TDD" column.

2. **Viewing Work Items**: Click on a work item to view its details. This will show all the information associated with the work item including title, description, assignment, comments, and history.

3. **Filtering**: You can filter the work items shown on the board by several criteria. This can be useful if you have a large number of work items and need to focus on specific items. 

    - The board's filter bar can be expanded to reveal several filter options. 
    - These filters can be combined to refine the board's view.

4. **Collapsing and Expanding Columns**: Each column on the board can be collapsed or expanded using the `Expanded/Collapsed` toggle. This can help focus on specific stages of the workflow.

The Azure DevOps Boards provide an at-a-glance overview of the project's progress. They are a crucial tool for any Agile development process, enabling effective task tracking and project management.

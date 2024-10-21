# QuickList - Simple Task Management

**QuickList** is a straightforward to-do list manager designed to help users organize and prioritize their daily tasks. Whether you're managing work assignments, personal errands, or long-term projects, QuickList keeps you on track with intuitive task management features. With QuickList, users can create tasks, set deadlines, assign priorities, and receive reminders—all in a simple, clutter-free interface.

## Key Features

**Task Management**: Create, edit, and delete tasks easily.
**Deadlines**: Set deadlines for tasks to ensure timely completion.
**Priority Levels**: Assign priority labels (Low, Medium, High) to tasks for better organization.
**Notifications**: Receive reminders for upcoming tasks and deadlines.
**Progress Tracking**: Monitor task completion with visual progress indicators.

## Installation Guide

To install QuickList on your system, follow the steps below based on your operating system:

1. **Windows**
   1. Download the QuickList installer from the official website.
   2. Run the installer and follow the on-screen instructions.
   3. Launch QuickList from the Start menu.

2. **macOS**
   1. Download the QuickList .dmg file from the official website.
   2. Open the .dmg file and drag QuickList to your Applications folder.
   3. Launch QuickList from your Applications.
  
3. **Linux**
   1. Open the terminal and run the following command to install QuickList: **sudo apt install quicklist**
   2. Once installed, you can launch QuickList from the applications menu.
  
## User Guide

### Creating a Task

To create a new task in QuickList, follow these steps:
- Open QuickList.
- Click on the "Add Task" button.
- Enter the task name in the provided field.
- Set a deadline if needed.
- Assign a priority level (Low, Medium, High).
- Click "Save" to add the task to your list.

### Collaboration

QuickList offers several collaboration options to enhance teamwork. Below is a comparison of available options:

| Collaboration Option     | Description                                  |
|--------------------------|----------------------------------------------|
| **Shared Lists**         | Share your task lists with team members.    |
| **Task Assignments**     | Assign tasks to specific team members.      |
| **Comments**             | Add comments and feedback on tasks.         |
| **Notifications**        | Receive updates when tasks are modified.    |

### Reporting

Users can generate reports to track their productivity. Here’s an example of a generated report in JSON format:

```json
{
  "user": "Ali AlKhaldi",
  "tasks": [
    {
      "taskName": "Complete DBSadie Project Report",
      "status": "completed",
      "deadline": "2024-10-24"
    },
    {
      "taskName": "Submit the project through blackboard",
      "status": "pending",
      "deadline": "2024-10-24"
    }
  ]
}

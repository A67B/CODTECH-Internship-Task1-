Name: ABHAY B
Company: CODTECH IT SOLUTIONS
ID: CT6WD635
Domain: WEB DEVELOPMENT
Duration:June to August
Mentor:Muzammil
OVERVIEW OF THE PROJECT
PROJECT NAME: To-Do List Web Application
PURPOSE:
The To-Do List Web Application is designed to help users efficiently manage their tasks. Users can add tasks, set deadlines, mark tasks as completed, and categorize them based on their status (In Progress or Done). Additionally, users can view categorized tasks in separate tabs, providing a streamlined overview of their progress.

Core Features:
Task Addition:

Users can add new tasks with an associated due date and time.
Tasks are displayed in a list format with options to mark them as completed or delete them.
Task Categorization:

Tasks are categorized into two main categories: In Progress and Done.
Tasks marked as completed are moved to the Done category.
Tasks that are not completed remain in the In Progress category.
Side Navigation Bar:

A sidebar allows users to navigate between different task categories.
The sidebar contains clickable labels that open new tabs showing tasks categorized as In Progress or Done.
New Tab Display:

Clicking on the "In Progress" or "Done" labels opens a new tab.
The new tab displays a list of tasks based on their completion status with different background colors (purple for In Progress, green for Done).
Responsive Design:

The application features a responsive layout that adapts to different screen sizes, ensuring usability across devices.
├── index.html
├── style.css
└── script.js
 HTML (index.html):
Structure:

The HTML file includes a title, linked stylesheets, and a body containing the core components: a menu icon, a sidebar, and the main task container.
Key Elements:

Menu Icon: Toggles the visibility of the sidebar.
Sidebar: Contains labels for navigating between task categories.
Container: Displays the task list and input fields for adding new tasks.
 CSS (style.css):
Layout:
The CSS file manages the layout of the application, including the sidebar's position, the container's styling, and the responsiveness of the layout.
Styling:
The application uses a linear gradient background for a visually appealing design.
Different background colors are applied to the new tabs based on the task category (purple for In Progress, green for Done).
Transitions:
Smooth transitions are implemented for the sidebar to slide in and out.
JavaScript (script.js):
Core Functionality:
Task Addition: Handles adding new tasks to the list, including validation for non-empty inputs.
Task Deletion: Allows users to remove tasks from the list.
Task Categorization: Categorizes tasks based on their completion status.
Sidebar Toggle: Manages the opening and closing of the sidebar.
New Tab Functionality:
Clicking on "In Progress" or "Done" in the sidebar opens a new tab displaying tasks that match the selected category.
Each new tab has a specific background color based on the task category.
Usage Instructions:
Adding a Task:

Enter a task description and select a due date and time.
Click the "Add" button to add the task to the list.
Categorizing Tasks:

Mark a task as completed by checking the checkbox next to it.
Tasks that are not checked remain in the In Progress category.
Navigating Task Categories:

Open the sidebar by clicking the menu icon.
Click "In Progress" to view tasks that are not completed in a new tab with a purple background.
Click "Done" to view tasks that have been completed in a new tab with a green background.
Future Enhancements:
Task Editing:

Add functionality to edit existing tasks.
Task Prioritization:

Allow users to prioritize tasks (e.g., high, medium, low priority).
Data Persistence:

Implement localStorage or a database to persist tasks between sessions.


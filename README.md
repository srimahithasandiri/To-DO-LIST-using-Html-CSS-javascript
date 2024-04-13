# To-DO-LIST-using-Html-CSS-javascript
# **INTRODUCTION**

In the realm of personal productivity and organizational tools, the to-do list occupies a central role, universally recognized for its simplicity and effectiveness in managing tasks and priorities. The evolution from paper-based lists to digital platforms has significantly expanded the functionality and accessibility of to-do lists.

A to-do list project is highly useful in today's world for several reasons:Time Management: With busy schedules and numerous tasks to complete, a to-do list helps users manage their time effectively by prioritizing tasks and staying organized. Accessibility: With the prevalence of smartphones and other devices, users can access their to-do lists from anywhere, ensuring they always have their tasks at hand and can add or update them as needed. a to-do list project provides users with a simple yet powerful tool for managing their tasks, increasing productivity, and reducing stress in today's hectic world.

This project is driven by the vision to harness the capabilities of JavaScript and the versatility of web technologies to deliver a superior task management experience.

# **Implementation**
*	JavaScript Framework: Utilize a modern JavaScript framework for building the frontend application.
*	HTML/CSS: Use HTML5 and CSS3 for structuring and styling the user interface, ensuring compatibility with various web browsers.
*	Responsive Design: Implement responsive design principles to ensure optimal viewing experience across desktop and mobile devices.
*	User Interface Components: Utilize UI libraries for designing interactive and visually appealing components.

# **CODE EXPLAINATION**

## **HTML Structure**
<div class="container">: Acts as the main container for the to-do list application, wrapping everything in a visually appealing background.
<div class="todo-app">: Encloses the to-do list's title, input area, and list itself, providing a centered, stylized container for the app components.
<h2>To-Do List</h2>: The title for the application.
Input Row (<div class='row'>): Contains the text input field and the Add button. Users can type their task here and add it to the list.
<ul id="list-container">: The unordered list where tasks will be displayed as list items (<li>).
  
## **CSS Styling**
The CSS styles define the look and feel of the to-do list, applying a gradient background, styling the input fields, buttons, and tasks. 
Key styling includes:
•	The container class adjusted on the page with a min-height, width and background-color and padding.
•	The application is centered on the page with a maximum width, border-radius, margin and padding for aesthetics.
•	Input fields and buttons are styled for a seamless interface.
•	The .container and .todo-app are styled to center the content and apply specific background colors and paddings.
•	Tasks (<li> elements) have distinctive styles, with completed tasks being visually different to provide clear feedback on their status.
•	Tasks (<li> elements) and other components like the input box and buttons have specific styles for appearance, hover effects, and when a task is marked as completed.

## **JavaScript Functionality**
The JavaScript adds dynamic behavior to the to-do list, covering task addition, completion marking, and deletion.
Adding Tasks (addTask):
Checks if the input field (inputBox) is empty. If not, it proceeds; otherwise, it alerts the user to write something.
Creates a new list item (<li>) and sets its content to the value entered in the input field.
Appends a close button (<span>) to each task for the removal functionality, with a click event listener that hides the task on click.
Clears the input field after adding the task to the list.
Marking Tasks as Completed:
Utilizes event delegation by adding a click event listener to the list container (inputBox). When a task is clicked, the 'checked' class is toggled on the task, changing its appearance to indicate completion.
Removing Tasks:
The close button (<span> with '×') added to each task allows users to remove tasks from the list.
Initially set up in the add function and further facilitated through a click event listener that sets the task's display style to "none", effectively hiding it.

# **USAGE**
Adding a Task: Users enter a task in the input field and click "Add" to add it to the list.
Marking a Task as Completed: Users click on a task to toggle its "completed" status.
Removing a Task: Users click the "×" button on a task to remove it from the list.


# **CONCLUSION**
In conclusion, the development of our to-do list project has been a rewarding journey that has showcased the power and versatility of HTML, CSS, and JavaScript in creating dynamic web applications. Our primary objective was to design a user-friendly and functional to-do list that empowers users to manage their tasks efficiently. Through meticulous planning and collaboration, we successfully implemented key features such as task addition and deletion. The seamless integration of HTML for structure, CSS for styling, and JavaScript for interactivity has resulted in a polished and intuitive user interface.

# **OUTPUT**
![image](https://github.com/srimahithasandiri/To-DO-LIST-using-Html-CSS-javascript/assets/166735932/b8e4a291-3779-40fa-908b-e9bdea83dd87)

![image](https://github.com/srimahithasandiri/To-DO-LIST-using-Html-CSS-javascript/assets/166735932/c461c73f-7df4-4f10-afe6-fad7bee86cbf)

![image](https://github.com/srimahithasandiri/To-DO-LIST-using-Html-CSS-javascript/assets/166735932/1c8656dc-f72f-4342-ad66-4cdbb520d0e5)







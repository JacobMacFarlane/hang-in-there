# Hang in There  

### Abstract:
[//]: <> (Briefly describe what you built and its features. What problem is the app solving? How does this application solve that problem?)

The website we created has the ability has the ability to generate a random inspirational poster, as well as generate one from an image and text prompts. These posters can be saved into a grid, and those images can be removed with a double click. This website solves the worldwide problem of lack of inspiration. We are at the dawn of the age of Aquarius and this is its harbinger.

### Installation Instructions:
[//]: <> (What steps does a person have to take to get your app cloned down and running?)

1. Open the repo
2. Click the green Code button and copy the SSH
3. In Terminal, type the command 'mkdir' to create a new directory  and 'cd' into that directory
4. Once in the directory, type the command git clone [paste ssh]
5. Type the command 'code .' to open up VS Code
6. Type the command 'open index.html' to open in the browser.

### Preview of App:
[//]: <> (Provide ONE gif or screenshot of your application - choose the "coolest" piece of functionality to show off.)

### Context:
[//]: <> (Give some context for the project here. How long did you have to work on it? How far into the Turing program are you?)

We worked on the project approximately 4-5 hours for four days to reach the end of iteration 4. We used Trello to manage the project. The expectations were broken out into a checklist. We organized our kanban with 'To Do', "In Progress", "Completed", and "Resources". This allowed us to have a hub from which to work, rather than disrupt the workflow to share resources or updates. 

We switched off each iteration so that the workload would be balanced and we would each have equal experience working with the GitHub workflow.

We are both currently in Week 2 of Mod 1.

### Contributors:
[//]: <> (Who worked on this application? Link to their GitHubs.)

Jacob Macfarlane: https://github.com/JacobMacFarlane
Christopher Cole: https://github.com/chrometaphor

### Learning Goals:
[//]: <> (What were the learning goals of this project? What tech did you work with?)

Learning Goals:

1. Write clean, DRY JavaScript
2. Use a provided class by creating object instances using the new keyword
3. Manipulate the page after it has loaded adding, removing, and updating elements on the DOM
4. Begin to understand the connection between HTML, CSS and JavaScript
5. Practice reading, understanding, and using provided code
6. Build an understanding of writing code collaboratively
7. Document changes with atomic commits & thorough code reviews
8. Communicate, troubleshoot, and plan effectively as a team

We worked with Chrome as a DOM, HTML, CSS, Javascript for our languages within the code editor VS Code, which was accessed through Terminal.

### Wins + Challenges:
[//]: <> (What are 2-3 wins you have from this project? What were some challenges you faced - and how did you get over them?)

Wins:

1. Accessing HTML and CSS elements through Javascript
2. Understanding how Event Listeners work and link to 'click' on the site.

Challenges:

1. In iteration 2 we got stuck: when in new poster form view, users should be able to fill out the three input fields and then hit the Show My Poster button. We believed our query selectors and event listeners were hooked up properly, but our function was not producing the final image on click. We researched how to prevent default and added function to display it to display in the function.

2. We struggled with the delete image in Iteration 4. After research, we we found out that we need to remove the HTML elements from the grid and remove the array in Javascript using 'splice'.
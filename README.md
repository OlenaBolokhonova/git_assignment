# Git Assignment - <OlenaBolokhonova>
a. What is an issue?
An issue in is a tool to track ideas, enhancements, tasks, or bugs for work on software projects. Issues are a great way to keep track of tasks, enhancements, and bugs for  projects. They often include discussion threads and can be linked to pull requests.
b. What is a pull request?
A pull request is a method used in version control systems to request that changes you have made to a branch be reviewed and then merged into another branch (typically the main branch). It includes a review process where other developers can review, discuss, and approve the changes before they are integrated.
c. How do I open up a pull request?
1. Push  branch to the remote repository (if not already done) 
git push origin your-branch-name
2. Go to the repository on GitHub.
3. Navigate to the 'Pull requests' tab and click 'New pull request'.
4. Select the base branch (the one I want to merge into) and compare branch (the one with my changes).
5. Click 'Create pull request'.
6. Add a title and description for your changes.
7. Submit the pull request by clicking 'Create pull request' again.
d. Give me a step by step guide on how to add someone to your repository.
1. Go to GitHub repository.
2. Navigate to 'Settings' > 'Manage access'.
3. Click 'Invite a collaborator'.
4. Enter their GitHub username or email address and click 'Add'.
5. The person will receive an invitation which they must accept to become a collaborator.
e. What is the difference between git and GitHub?
Git is a distributed version control system for tracking changes in source code during software development. It's designed to handle everything from small to very large projects with speed and efficiency.

GitHub is a cloud-based hosting service that lets you manage Git repositories. It provides additional features beyond what Git offers, such as a web-based graphical interface, access control, bug tracking, feature requests, task management, and wikis for every project.
f. What does git diff do?
git diff is a command used in Git to show the differences between various commits, the staging area (index), and the working directory. It's useful for seeing what has changed between two states of a project. For example, git diff will show the differences in the code between your current working directory and the last commit.
g. What is the main branch?
The main branch (formerly known as 'master' in many repositories) is the default development branch. When you create a new repository, this is the initial and primary branch where the stable codebase is maintained. All major changes are usually merged back into this branch at some point.
h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
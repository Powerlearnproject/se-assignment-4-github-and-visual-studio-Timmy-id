[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15290071&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.

    - GitHub is an online platform for storing, sharing and managing codes.
    - Its primary function is to store and manage codes.
    - its allows multiple people to work on the same codebase

Repositories on GitHub:

What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.

    - GitHub repository is like a folder for storing files and its different versions, which is accessible to anyone with the link
    = To create a repository on GitHub:
        - Go to ```https://github.com/``` and create an account
        - Then select the icon for creating a new repository and then follow the steps
    - The essential elements that should be included in a repository:
        - A README.md file which should contain information about the repository
        - A .gitignore file which should contain files and folders that you don't want to visible to others

Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?

    - Git tracks changes that is made in our files and folders which creates a different version for every change that is made. This allows for reverting to older versions should the need arises
    - GitHub enhances version control in that it allows developers to work on the same codebase at the same time without conflicting each other and also allows the developers see each other's codes

Branching and Merging in GitHub:

What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.

    - Branch is a feature on GitHub that allows a developer have a copy of the whole codebase in which changes made on that codebase does not affect the the original codebase
    - Branch is important because it allows developers have personal copies of the codebase and the changes made does not affect one another
    - To create a branch:
        - Select the branch text on screen and then on the next screen, click on the new branch button
        - Then input the branch name and also select the source
        - You then have a copy of the source selected
        - Any change made on that codebase will be on the branch just created
        - After all the changes have been made, stage the changes and then commit the changes.
        - Then a pull request is made which compares the codes in the branch and its source. If no error is detected, then the codes can be merged to the main branch.

Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.
    - Pull request is an alert that tells people you are working with that you have made changes to a branch and have pushed that branch to GitHub.
    - This facailiates code reviews and collaboration by allowing others see the changes you have made and to be able to make corrections where necessary.
    - The steps to create and review a pull request are:
        - You push the branch where the changes are made to GitHub
        - You press the create a pull request button which allows you to select the branch you want merge your branch to
        - You then create a pull request
        - The code reviewer then checks that the code is good enough to be merged to the main branch and also allows to leave comments
        - If the code is not good enough, the pull request will not be approved and you have to make corrections
        - If the pull request is okay, the code is merged to the main branch

GitHub Actions:

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.

    - GitHub actions allows software developers automate their test, build and development pipelines and they can be used to automate workflows by applying some set of rules to it.
    - A simple CI/CD pipeline is checking that a codebase passes some parameters before it can be merged 

Introduction to Visual Studio:

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?

    - Visual studio is an integrated development environment.
    - The features of visual studio includes:
        - It comes with debugging tools which makes it easy to debug our codes
        - It has intellisense feature that makes writing code simpler and easier
        - It helps in testing our code right from the interface
    - Visual studio differs from visual studio code in that visual studio is an integrated development environment while visual studio code is a code editor.

Integrating GitHub with Visual Studio:

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?
Debugging in Visual Studio:

    - Steps to integrate a GitHub repository with Visual Studio
        - Open visual studio
        - Select the clone a repository option under the Get started option on the opening page
        - Enter the repository url or select the option to browse through your repository
    - This integration enhances the development workflow as code changes will be pushed to GitHub right from visual studio
Source: [https://learn.microsoft.com/en-us/visualstudio/get-started/tutorial-open-project-from-repo?view=vs-2022](https://learn.microsoft.com/en-us/visualstudio/get-started/tutorial-open-project-from-repo?view=vs-2022)

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?

    - One of the tools available is the inbuilt debugger
    - Developers can use this tool to fix performance issues in their code

Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.

    - GitHub and visual studio can be used together in that it makes it easier to work on the same codebase with other collaborators from your development environment without having to go to GitHub


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].

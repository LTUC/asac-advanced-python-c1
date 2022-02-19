# Lab: Projects, Packages and Modules

## Overview

In this lab you will create a project using poetry in order to have a separate environment and move your gradebook application into it.

## Feature Tasks and Requirements

Create a poetry project called gradebook
Move your code from your previous lab into a module called `main.py` in the package called gradebook inside of your gradebook project.

Make sure the root of your project folder is the root of your git repository
Refactor your code to ensure you are using functions
use name == "main" to guard your application from running if your module is imported.

## Implementation Notes

User Acceptance Tests
GIVEN the user is in the root directory of the project
AND the virtual environment is activated
WHEN the user executes
`$ python -m gradebook.main` is executed

THEN the main menu is shown
Configuration

Use poetry to create gradebook project.

`$ poetry new gradebook`

`$ poetry shell`

Use the folder created by Poetry as the root of your project's git repository.

## Submission Instructions

Create a branch from your previous gradebook repo and name it `gradebook-functions` and submit the link for it.

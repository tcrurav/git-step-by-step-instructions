# Git step by step instructions

This project includes step by step instructions to work with git, and github projects and issues as part of RiddleHunt Project in march 2024.

This is not a guide to learn git. This is a guide to use git in a certain way, using github issues and projects.

## Prerequisites

You need basic git background.

You need a working environment with:
* [Git](https://git-scm.com) - You can install it from https://git-scm.com/downloads.

## The steps of this step-by-step short guide

This short guide is divided into:
* Preliminary steps
  - Step 1: Installing Git locally.
  - Step 2: Installing Visual Studio Code locally.
  - Step 3: Creating a Github account.
* First steps done only once at the beginning of a project
  - Step 4: Creating a Github repository.
  - Step 5: Creating a Github project.
  - Step 6: Creating Github rules for main branch and develop branch.
  - Step 7: Creating a local project in Visual Studio Code.
  - Step 8: Creating main and develop branches locally and push your first commit.
* Steps during the project
  - Step 9: Adding items to the backlog at anytime.
* Steps during the sprint creation
  - Step 10: Dragging items to the Ready column.
  - Step 11: Dragging items to the In-progress column.
  - Step 12: Converting items in issues.
  - Step 13: Assigning issues to developers.
* Steps working locally on an issue.
  - Step 14: Creating a new branch locally from develop with name issue#n
  - Step 15: working on the issue#n.
  - Step 16: git add, commit and push to remote branch issue#n
* Steps in Github to Create, Review, Accept or Deny, and finally Merge a pull request
  - Step 17: Creating pull request for issue#1
  - Step 18: Reviewing pull request for issue#1
  - Step 19: Merging into develop or Requesting Changes for issue#1
* Steps in Github to merge from develop to main
  - Step 20: Same steps 17 to 19 but now from merge from develop to main

In the next sections we will see all this steps a bit deeper.

### Preliminary steps

In the preliminary steps you just have to start working with git following this steps:

* Step 1: Installing Git locally.

Just go to ```https://git-scm.com/downloads``` and then download Git for your favourite operating system; finally install git in your computer.

* Step 2: Installing Visual Studio Code locally.

Just go to ```https://code.visualstudio.com/``` and then download Visual Studio Code for your favourite operating system; finally install git in your computer.

* Step 3: Creating a Github account.

Just go to ```https://github.com/``` and then create your Github account.

### First steps done only once at the beginning of a project

In the preliminary steps you just have to start working with git following this steps:

* Step 4: Creating a Github repository.

Log in with your Github account and create a new repository.

![Creating a new repository](/screenshots/screenshot-47-short.png)

* Step 5: Creating a Github project.

Clic on the tab ```Projects``` and then create a new Project in Github.

![Creating a new project](/screenshots/screenshot-04-short.png)

Now you can create the project:

![Creating a new project](/screenshots/screenshot-05-short.png)

Use the ```Team Backlog``` template:

![Creating a new project](/screenshots/screenshot-06-short.png)

We will work with this 5 columns. Please remove the default left most one:

![Creating a new project](/screenshots/screenshot-07-short.png)

We will work with the following board columns, so that please delete the first default one:

![After deleting the first column](/screenshots/screenshot-04-short.png)

* Step 6: Creating Github rules for main branch and develop branch.

Clic on the tab ```Settings``` and then create rules for main and develop branches in Github.

![Creating a new project](/screenshots/screenshot-22-short.png)

* Step 7: Creating a local project in Visual Studio Code.

Just create a new local project in Visual Studio Code in a new folder.

* Step 8: Creating main and develop branches locally and push your first commit.

Just create a new local project in Visual Studio Code in a new folder. After that create some files (maybe your README.md file), and introduce the following git commands:

```
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin <<your github's repository url>>
git push origin main

git branch develop
git checkout develop
git push origin develop
```



## Built With

* [Visual Studio Code](https://code.visualstudio.com/) - The Editor used in this project

## Acknowledgments

* https://gist.github.com/PurpleBooth/109311bb0361f32d87a2. A very complete template for README.md files.
* https://www.conventionalcommits.org/en/v1.0.0/. A specification for adding human and machine readable meaning to commit messages
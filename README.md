# DevTeam – Student Developer Portfolio

## Project Description

DevTeam is a simple static portfolio website created as a college mini-project for **Module 6: Git and GitHub**.

The website presents our team members, skills, and projects in a clean and simple layout. The main purpose of this project is to demonstrate the basic concepts of **Git version control and GitHub repository management**.

## Team Members

- Aaditya Pratap
- Ameen TR
- Antonio Sajeev
- Antony Victor
- Amal Sudheer

## Technologies Used

- HTML
- CSS
- Git
- GitHub

No frameworks, databases, APIs, or backend technologies are used.

## Website Sections

The portfolio contains the following sections:

- **Home** – Introduction to the team
- **About** – Short description of the team
- **Team** – Details of the five team members
- **Skills** – Technologies and tools explored by the team
- **Projects** – Sample projects completed by the team
- **Contact** – Email, GitHub, and LinkedIn links

## Git & GitHub Features Demonstrated

This project demonstrates the following Git and GitHub concepts:

- Creating a local Git repository
- Checking repository status
- Staging files
- Creating commits
- Viewing commit history
- Creating a feature branch
- Making changes in a branch
- Merging a branch into the main branch
- Connecting a local repository to GitHub
- Pushing changes to a remote repository

## Basic Git Workflow

The project follows this basic workflow:

```text
Create Project
      ↓
git init
      ↓
Initial Commit
      ↓
Create GitHub Repository
      ↓
Connect Remote Repository
      ↓
Push to GitHub
      ↓
Make Changes
      ↓
Create Commit
      ↓
Create Feature Branch
      ↓
Make Changes
      ↓
Merge Branch
      ↓
Push Final Version
```

## Git Commands Used

```bash
git init
git status
git add .
git commit -m "Initial portfolio website"

git branch
git checkout -b feature-contact

git checkout main
git merge feature-contact

git remote add origin <repository-url>
git push -u origin main

git log
```

## Commit History

The project uses at least three meaningful commits:

```text
Initial portfolio website
Added skills and projects section
Updated contact section
```

The `feature-contact` branch is used to demonstrate branch creation, modification, committing, and merging.

## How to Run the Project

No installation or server is required.

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in a web browser.

The website will run directly in the browser.

## Project Objective

The objective of this mini-project is to understand and demonstrate how Git and GitHub can be used to track changes, maintain different versions of a project, work with branches, merge changes, and store a project in a remote repository.
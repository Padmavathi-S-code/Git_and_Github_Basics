# Git_and_Github_Basics
A personal learning journal documenting Git and Github fundamentals, commands, workflows, practical examples, and troubleshooting.
## Table of Contents

| No. | Topic | Subtopics |
|:---:|---|---|
| 01 | [Introduction](#1-introduction) | Git, GitHub, Git vs GitHub, Version Control |
| 02 | [Git Fundamentals](#2-git-fundamentals) | Version Control Systems, How Git Works, Git Architecture |
| 03 | [Git Configuration](#3-git-configuration) | Installation, Version, Username, Email, Configuration |
| 04 | [Working with Repositories](#4-working-with-repositories) | Init, Clone, Status, .git Directory, .gitignore |
| 05 | [Staging and Committing](#5-staging-and-committing) | Staging, Tracking, Commits, Commit Messages, Git Log |
| 06 | [Branching and Merging](#6-branching-and-merging) | Creating, Switching, Renaming, Deleting, Merging, Conflicts |
| 07 | [Working with GitHub](#7-working-with-github) | Repositories, README, Public vs Private, Issues, Releases |
| 08 | [Remote Repositories](#8-remote-repositories) | Origin, Remote, Push, Pull, Fetch, Upstream |
| 09 | [Collaboration and Open Source](#9-collaboration-and-open-source) | Fork, Clone, Pull Requests, Code Reviews, Contributions |
| 10 | [Undoing Changes](#10-undoing-changes) | Restore, Reset, Revert, Amend |
| 11 | [Errors and Troubleshooting](#11-common-errors-and-troubleshooting) | Push Rejections, Merge Conflicts, Authentication, Detached HEAD |
| 12 | [Useful Git Commands](#12-useful-git-commands) | Command Reference |
| 13 | [Learning Resources](#13-learning-resources) | Official Documentation, Tutorials, Books |

## 1. Introduction
### 1.1 What is Git? 
Git is a free, open-source, distributed version control used to track changes in files and coordinate work among multiple people.
- Open-source: Its source code is publicsly available, and it can be used and modified under its licence.
- Distributed: Each user can have a complete copy of the repository and its history locally.
### 1.2 Who developed Git?
Git was created by Linus Torvalds also the creator of Linux kernel.
### 1.3 Important Git Concepts
- Repository : Your project managed by git.
- Commit: A recorded snapshot of changes you made to your project.
- Branch: An independent line of development (eg: main branch, master branch)
- Merge: Combining changes from different branches.
### 1.4 Git vs GitHub
| Git | GitHub |
|---|---|
| Version control system | Cloud-based development platform |
| Installed on your computer | Accessed through the web or others |
| Tracks changes in files | Host Git repositories |
| Works locally without internet | Requires internet for online collaboration |
| Manages commits and branches | Provides Pull Requests, Issues and collaboration features |
|Developed by Linus Torvalds | Owned by Microsoft |
### 1.5 Why use Version Control?
Version control helps developers and researchers:
- Track changes made to files.
- Maintain project history.
- Recover previous versions.
- Experiment without affecting the main project when trying to do open-source contributions.
- Collaborate with other developers and researchers around the world.
- Maintain reproducibility and transparency in research projects.

## 2. Git Fundamentals
### 2.1 What is version Control?
Versions Control is a system that records changes made in files over time, allowing users to track, compare, and restore previous versions.
- Why Version Control is important?
- Tracking: Keeps track of changes made to files.
- History: Maintains a record of project development.
- Recovery: Helps recover previous versions.
- Collaboration: Allows multiple people to work on the same project.
- Experimentation and open source contribution to projects: Allows developers and researchers to experiment with open-source projects without directly affecting the main development branch.


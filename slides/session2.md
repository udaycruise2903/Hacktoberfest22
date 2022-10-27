---
theme : "black"
transition: "convex"
highlightTheme: "monokai"
logoImg: "./images/sigma_club.jpg"
slideNumber: false
title: "Hacktoberfest 2022"
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.4.0/reveal.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.4.0/reveal.js">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.4.0/theme/black.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.4.0/plugin/highlight/highlight.min.js">

<!-- .slide: data-background="bvjsc-54*54.png" -->

![Hacktoberfest](./images/Hfest-Logo-2-Color-Manga%402x.png)

---

## Session 2 - Git-ventures

--

#### What is Git

Git is a version control software for your local system

--

#### Why do we need git?

- It tracks the history of changes as people and teams collaborate on projects together
- As developers make changes to the project, any earlier version of the project can be recovered at any time.

--

Developers can review project history to find out:

- Which changes were made?
- Who made the changes?
- When were the changes made?
- Why were changes needed?

--

#### Install Git

Download from - https://gitforwindows.org/

Download **git cheatsheet** in VSCode extensions

--

#### Setup Git in your system

1. to set the username

`git config --global user.name "john144`

2. to set the user email

`git config --global user.email "john144@gmail.com"`

---

### Activity 01
#### contribute to an existing branch on GitHub

--

#### Demonstration -  Clone a repository that you forked recently to local system

--

1. *download a repository on GitHub to our machine*
2. Replace `owner/repo` with the owner and name of the repository to clone
git clone https://github.com/owner/repo.git

3. change into the existing branch called `session1-notes`
 
`git checkout session1-notes`

--

4. make changes, for example, edit `notes1.md` and `notes2.md` using the text editor

5. stage the changed files

`git add notes1.md notes2.md`

6. take a snapshot of the staging area, Make a comment on what are the changes related to.(anything that's been added)

`git commit -m "edited notes"`

--

7. push changes to github

`git push --set-upstream origin my-new-branch`

--

#### Exercise-01

- clone your notes repo 
- checkout to an existing branch (ex: session1-notes)
- add a file call todo.md. Please list the task that you want to redo.
- push the changes of branch **session1-notes**

---

### Activity 02
#### Contribute to an existing repository

--

#### Demonstration -  Clone a repository that you forked recently to local system

--

1. *download a repository on GitHub to our machine*
2. Replace `owner/repo` with the owner and name of the repository to clone
git clone https://github.com/owner/repo.git

3. change into the `repo` directory
 
`cd repo`

4. create a new branch to store any new changes.(Please rename your branch differently)

`git branch my-new-branch`

--

5. switch to that branch (line of development)

`git checkout my-new-branch`

6. make changes, for example, edit `notes1.md` and `notes2.md` using the text editor

7. stage the changed files

`git add notes1.md notes2.md`

--

8. Make a comment on what are the changes related to.(anything that's been added)

`git commit -m "added 2 notes on bikes"`

9. push changes to github

`git push --set-upstream origin my-new-branch`

--

#### Exercise-02

- clone any forked repo(hello-world/any other repo of your friend)
- create a new branch on local system called **readme-session2**
- add a file called participating.md
- push the changes of **branch readme-session2**

---

SESSION 1 - Git-ventures

THE END

---


---
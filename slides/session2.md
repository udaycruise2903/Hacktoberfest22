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

#### Activity 02
### 

--

#### Demonstration - How to create a repository? 

---

#### Activity 01 
### 1. Creating a repository

1. In the upper-right corner of any page, use the  drop-down menu, and select New repository.

![create-repo](./images/repo-create.png)

--

2. In the Repository name box, enter **Notes** as repo name
3. In the Description box, write a short description.(My Notes at Hacktoberfest)
4. Select Add a README file.
5. Select whether your repository will be Public or Private.
6. Select a license - MIT License

--

7. Click Create repository.
![hello-world](./images/hello-world-repo.png)

--

#### Exercise - Create your first repository

Edit the README file with little introduction of file, comment and save changes, refer to markdown cheatsheet

---

### Activity 01 
#### 2. Creating a branch

--

#### Demonstration -  creating a branch in the first repo.

--

Have you ever saved different versions of a file? Something like:

- design1.html
- design-with-navbar.html
- final-design.html

--

#### What is a good solution for this?

![hello-world](./images/branching.png)

--

1. Click the Code tab of your **Notes** repository.
2. Click the drop down at the top of the file list that says main.

![hello-world](./images/branch-selection-dropdown.png)

--

3. Type a branch name - **activity1-notes**, into the text box.
4. Click Create branch: activity1-notes from main.
![hello-world](./images/new-branch.png)

--

Now you have two branches, main and activity1-notes. Right now, they look exactly the same. Next you'll add changes to the new branch.

--

#### Exercise - create a new hello-world repo and create a new branch called 1-edit-readme

---

#### Activity 01 
### 3. Editing and committing changes

--

#### Demonstration - making changes and committing it in the first repo.

--

1. Under the activity1-notes branch you created, click the README.md file.
2. Click at pencil symbol to edit the file.
3. In the editor, write a bit about yourself. Try using different Markdown elements.
4. In the Commit changes box, write a commit message that describes your changes.

--

5. Click Commit changes.
![hello-world](./images/first-commit.png)

--

#### Exercise - create a branch in your first repo

---

#### Activity 01 
### 4. Opening a pull request

--

#### Demonstration - Creating a PR in my repo, and mentioning my friend’s name

--

1. Click the Pull requests tab of your activity1-notes repository.
2. Click New pull request
3. In the Example Comparisons box, select the branch you made, activity1-notes, to compare with main (the original).

--

4. Look over your changes in the diffs on the Compare page, make sure they're what you want to submit.
![hello-world](./images/diffs.png)

--

- Pull requests are the heart of collaboration on GitHub. When you open a pull request, you're proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in different colors.

--

- As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.
- By using GitHub's @mention feature in your pull request message, you can ask for feedback from specific people or teams, whether they're down the hall or 10 time zones away.

--

- You can even open pull requests in your own repository and merge them yourself. It's a great way to learn the GitHub flow before working on larger projects.

--

#### Exercise - Creating a PR in hello-world from branch(1-edit-readme) and mention your  friend’s name that you have finished doing it

---

#### Activity 01 
### 5. Merging your pull request

--

#### Demonstration - merge your activity1-notes branch into the main branch.

--

1. Click Merge pull request to merge the changes into main.

![hello-world](./images/pullrequest-mergebutton.png)

2. Click **Confirm merge**. You will receive a message that the request was successfully merged and the request was closed.

--

3. Click **Delete branch**.

Now that your pull request is merged and your changes are on main, you can safely delete the 1-edit-readme branch. If you want to make more changes to your project, you can always create a new branch and repeat this process.

--

#### Exercise - Merge your 1-edit-readme branch into the main branch in hello-world repo. 

After you merge your pull request, the changes on your 1-edit-readme branch will be incorporated into main.

---

### Activity 02 
#### Create your profile using README

You can create your custom profile that would be displayed whenever some user visits your profile.

--

#### Exercise - Create a repo and name it your username and include a README file while creating the repo.

- [X] Use the markdown cheatsheet
- [ ] For comprehensive understanding, refer to this article from Github

--

Markdown consists of a set of symbols inserted in a document ending with .md suffix to control its structure, formatting, or the relationship between its parts.

---

SESSION 1 - Getting Started with Github

THE END

---


---
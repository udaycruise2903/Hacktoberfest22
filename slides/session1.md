---
theme : "black"
transition: "convex"
highlightTheme: "monokai"
logoImg: "./images/sigma_club.jpg"
slideNumber: true
title: "Hacktoberfest 2022"
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.4.0/reveal.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.4.0/reveal.js">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.4.0/theme/black.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.4.0/plugin/highlight/highlight.min.js">

<!-- .slide: data-background="bvjsc-54*54.png" -->

![Hacktoberfest](./images/Hfest-Logo-2-Color-Manga%402x.png)

---

![BVJSC](./images/192x192.svg)
![Sigma Club](./images/sigma_club.jpg)
## Hacktoberfest 2022

::: block
Organised by
*BV Jagadeesh Science Centre* 
in association with 
Dept. of Computer Science, 
National College Jayanagar
{style=background:red;width:100px}
::: 

---

Sigma Club members@workshop

   - Charan Yadav
   - Spoorti K
   - Bhargav Ram
   - Uday Kiran N

---

Contributions

   - Chandan NL
   - Shashank A
   - Chandhan SS

---

## Session 1 - Getting started with Github

--

#### What is Github

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

--

#### Are there alternatives to Github?

Yes, Gitlab, Gitea and many more

--

#### Signing up for a new GitHub account  

--

#### Introduction 

- Home page
- Explore, trending options
- Issues
- Notifications
- Repository
- Organisation
- Stars

--

#### Demonstration 

How to search for a project and star it?

--

#### Exercise

Search for a project in your subject and star it.(some topics - open source university, awesome)

---

#### Activity 01 
### Creating your first repo and editing it

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

Download **Markdown All in one** extension in VSCode

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

### Activity 03 
#### Fork Spoon-Knife repository

--

#### Why fork a repo?

- Propose changes to someone else's project
- Use someone else's project as a starting point for your own idea

--

#### Am I violating ethics or doing something illegal?

No, Open source software is based on the idea that by sharing code, we can make better, more reliable software.

--

#### Who/What determines who can use the code of a project?

--

Repo owner can choose various licenses that determine how you want your project to be shared with others. 

--

### Activity 03 
#### 1. Forking a repository

--

1. On GitHub.com, navigate to the [octocat/Spoon-Knife](https://github.com/octocat/Spoon-Knife) repository.
2. In the top-right corner of the page, click Fork.

![fork_button](./images/fork_button.png)

--

3. Select an owner for the forked repository.

![fork-choose-owner](./images/fork-choose-owner.png)

--

4. By default, forks are named the same as their parent repositories. You can change the name of the fork to distinguish it further.

![fork-choose-repo-name](./images/fork-choose-repo-name.png)

--

5. Optionally, add a description of your fork.

![fork-description](./images/fork-description.png)

--

6. Choose whether to copy only the default branch or all branches to the new fork. For many forking scenarios, such as contributing to open-source projects, you only need to copy the default branch. By default, only the default branch is copied.

![copy-default-branch-only](./images/copy-default-branch-only.png)

--

7. Click Create fork.

![fork-create-button](./images/fork-create-button.png)

--

#### Exercise - fork your friend's repo (hello-world / Notes) 

- create a separate branch(ex: update-code) from main branch
- (**Up for a challenge?**) open a Pull request from it.

--

#### How to update your forked repo, if your friend accepts and merges your pull request

--

- After your friend merges your pull request, Go to forked repo. 
- You will find **Sync fork** option
- click on **update branch**

![sync-fork](./images/sync-fork.png)

--

##### complicated right?

Please repeat this exercise a number of times to get an idea of whole process

---

SESSION 1 - Getting Started with Github

THE END

---


---
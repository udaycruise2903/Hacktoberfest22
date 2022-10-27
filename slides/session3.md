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


## Session 3 - Hacking time

![Hacktoberfest](./images/Hfest-Logo-2-Color-Manga%402x.png)

---

#### fun projects to accomplish (static site)

- [ ] personal website
- [ ] Sigma Club website
- [ ] Digital Museum Gallery
- [ ] Event website

--

#### We will be working on building your personal website now

--

#### pre-requisites

1. Download and setup Hugo for [windows](https://gohugo.io/getting-started/installing/#windows)

--

#### Overview of tasks

- [ ] (for advanced contributions) Download Go -https://go.dev/dl/ 

- [ ] setup Hugo
- [ ] create a personal website
- [ ] clone a hugo theme
- [ ] deploy to Github -https://gohugo.io/hosting-and-deployment/hosting-on-github/

--

#### Steps

1. >hugo new site <your website's name>
2. >cd <your website's name>/themes/
3. Clone the raditian-free-hugo-theme
> git clone https://github.com/radity/raditian-free-hugo-theme.git)

--

#### steps

4.  Replace the "config.toml" file in your project's root directory with /themes/raditian-free-hugo-theme/exampleSite/config.toml
5. delete .git folder in   
/themes/raditian-free-hugo-theme/  
1. change baseURL in me/config.toml  
baseURL = "https://bvjsciencecentre.github.io/me/"`

7. To start the server
 
`hugo server -D`

--

#### steps - Deployment

Refer this site- https://gohugo.io/hosting-and-deployment/hosting-on-github/

8. Create a file in   
me/.github/workflows/gh-pages.yml
9. copy the gh-pages.yml snippet.
10. cd me/   
git init
11. add the branch   
git branch -M main

--

12. commit all the changes    
git commit -m "first commit"

13. add the link of github repo to local repo   
`git remote add origin https://github.com/bvjsciencecentre/me.git`
14. push all the changes to github    git push -u origin main
15.  Go to Settings > GitHub Pages, and change the **source** branch to **gh-pages**

---

SESSION 3 - Hacking time ends

HACKATHON BEGINS

---


---
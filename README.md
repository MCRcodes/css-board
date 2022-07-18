# CSS Board Challenge 🎨✨

## Introduction

This challenge is designed to give you a little taste of working on a project with other developers!

Hopefully, whilst getting to flex your CSS skills, you can see the process of pulling down a shared repo, adding some content, and then pushing back up.

It’s likely this process will involve some 🚨**conflicts**🚨, so we can also learn what to do with those too!

**Full instructions can be found in the slides accompanying this exercise** 📚

---

<br/>

## Tutor Setup Instructions

**NB: This step is for course tutors only. If you're a student then you don't need to perform this step.**

Before starting this exercise please create a new branch from `main`.

Name it after the cohort that's doing the exercise, eg. `june-22`

Students will commit to the new branch, keeping the `main` branch sparkly clean for future use ✨

At the start of the exercise students will need to be given access to the repo:
- Share the branch link, and ask students to provide their GitHub usernames
- In the repo, go to Settings > Collaborators & Teams > Add People. Add each student by their username (or email) with Write access.
- Added students will receive invitations to their email inbox. Each student will need to accept their invite before they can push to the repo.

---

<br/>

## Student Instructions

### 1. Setup

- Clone this repo to your machine.
- We've created a branch for your cohort. To access this, open a terminal in VS Code and run the command `git checkout june-22`
- Create a new branch from the `june-22` branch, with your own name as the branch name:  
  `git checkout -b your-name`  
  where `your-name` is your name, eg. `freddie-mercury`. You can check which branch you're in using the command `git branch`.
- Familiarise yourself with the project structure. Have a look at the HTML & CSS.
- **In the slides provided during this exercise**, go to the last slide and find your name. You’ve been assigned a CSS topic. Your task is to create a post-it for this topic!

---

<br/>

### 2. Creating the HTML

- In the correct section of the html document, create a new `li` list element.
- Give the new `li` element the **class “post-it”** and an **id of your name**.
- Inside of your new `li` element, add:
  - A `h3` heading containing the name of the **CSS topic** assigned to you.
  - A `p` paragraph containing a **short description** of your CSS topic.

---

<br/>

### 3. Styling

In the correct section of the CSS document, add styles for your post-it:

- Each post-it should have an aspect ratio of **1:1**, with a height of **200px**.
- <span style="color:black; background-color: #E0EA87">**Selector** post-its</span> should have a background-color of <span style="color:black;  background-color: #E0EA87">**#E0EA87**.</span>
- <span style="color:black; background-color: #FF6F91">**Property** post-its</span> should have a background-color of <span style="color:black; background-color: #FF6F91">**#FF6F91**.</span>
- <span style="color:black; background-color: #0089BA">**Layout** post-its</span> should have a background-color of <span style="color:black; background-color: #0089BA">**#0089BA**.</span>
- **h3** elements should be **bold**.
- Post-its are never perfectly aligned, so make sure you **rotate** them slightly (somewhere between **-10deg** & **10deg**).

**Once you’re happy with the styling and able to see the post-it properly displayed in your browser, let one of us know. Then you can prepare a Merge Request 👇**

---

<br/>

### 4. Push & Merge (& Conflicts?!)

- **Add** the files you’ve changed to the staging area.
- **Commit** them with a meaningful message.
- **Push** your branch to the repo.
  - To do this you’ll have to set an upstream. The command for this is:  
    `git push --set-upstream origin branch-name`  
    where `branch-name` is the branch name you set earlier (it should be your name eg. `freddie-mercury`).
- Back in the GitHub repo on the website, you’ll have to open a **Pull Request (PR)** in order to merge your changes to the `main` branch. [Here are the GitHub docs on creating a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request). Add the instructors as **reviewers** of your PR.
- We’ll perform a **Code Review** of your changes. Once we accept it, you’ll be free to **merge**, as long as there are no **conflicts**.
- If there are conflicts we’ll work through them together.

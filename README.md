# Practical Task: Testing Tools

[![Made by Adam Cegiełka](https://img.shields.io/badge/made%20by%20-Adam%20Cegielka-blue.svg?style=flat-square)](https://adamcegielka.pl) <br>
[![Postman](https://img.shields.io/badge/Postman-Docs-ef5b25.svg?logo=postman)](https://learning.postman.com/docs/introduction/overview/)
[![Charles Proxy](https://img.shields.io/badge/Charles-Docs-bde.svg?logo=charles)](https://www.charlesproxy.com/documentation/welcome/)
[![DevTools](https://img.shields.io/badge/DevTools-Docs-2172f8.svg?logo=google-chrome)](https://developer.chrome.com/docs/devtools)
[![SQL](https://img.shields.io/badge/SQL-Tutorial-04AA6D.svg?logo=mysql)](https://www.w3schools.com/sql/default.asp)
[![GIT](https://img.shields.io/badge/GIT-Docs-f14e32.svg?logo=git)](https://git-scm.com/doc)

This repository contains my homework assignments as part of an internship program focused on gaining proficiency in popular API testing tools including Postman, Charles, and Chrome DevTools. It offers practical exercises and resources to effectively use these tools for building and testing APIs, thereby enhancing my software development skills.
- **Postman:** Tasks to help learn API creation, testing, and deployment.
- **Charles:** Exercises to understand and use this web proxy for HTTP monitoring and debugging.
- **Chrome DevTools:** Assignments to explore and utilize these tools for web application troubleshooting and optimization.  

The repository also encompasses basic **SQL** tasks and introductory **GitHub** exercises as part of the comprehensive training in software development practices provided by the internship.

## Internship Homework

### [Postman task:](https://github.com/AdamCegGrid/practical_task_module_8/tree/main/Postman_Task)  
[Solution](https://github.com/AdamCegGrid/practical_task_module_8/tree/main/Postman_Task)  
1. Install Postman REST Client
2. Create Account in Trello using PERSONAL mail (not Grid)
3. Sign In to Account
4. Get and save API Key: https://trello.com/app-key
5. Get token (Use token button)
6. Check that everything works By typing URL to address line: 
```
https://api.trello.com/1/members/me?key={YOUR_KEY}&token={YOUR_TOKEN}
```
7. If Step 6 returned JSON go to Step 8 if not go to Google
8. Create Postmen collection for:
    - Creating a new board `POST` *
    - Getting board by ID `GET`
    - Updating board `PUT`
    - Remove board  

<sub> *you need to use the same board id for all requests, so please extract the variable from the response to the POST request.  
USE DOC: https://developer.atlassian.com/cloud/trello/rest/api-group-boards/*</sub>

---

### [Charles Proxy task:](https://github.com/AdamCegGrid/practical_task_module_8/tree/main/Charls_Task)   
[Solution](https://github.com/AdamCegGrid/practical_task_module_8/tree/main/Charls_Task)  

Pre-conditions
Set up charles proxy
You need an Instagram account for testing (create new or you can use your own). Please, use the web version.

Do the following tasks using Map Local, Rewrite, breakpoints features in Charles:
1. Change the number of subscribers to 13 00000
2. Change the number of subscriptions for -12
3. Change the biography (Description) to text with 300 characters
4. Return 500 when opening a publication
5. Return 400 when opening profile page
6. Return 0 posts and check the text on the page
7. Delete your profile photo and check what present instead of photo

<sub>*Attach the screenshots of each step.*</sub>

---

### [Chrome DevTool task:](https://github.com/AdamCegGrid/practical_task_module_8/tree/main/DevTools_Task)  
[Solution](https://github.com/AdamCegGrid/practical_task_module_8/tree/main/DevTools_Task)  

1. Open the page https://www.amazon.com/  
`Elements Tab`  
2. Change a headline on the card to bigger one (more than 1 line text)  
3. Change the color and font (type, weight, size etc) for headlines
4. Make an image size 2 times smaller.
5. Make a screenshot of the new page view on Galaxy Note 3
6. Refresh the page. Choose one of the category blocks. Describe the block size, picture size and margins.  
`Console Tab`
7. Filter Errors only in the console. Describe what you understand from each message. Attach the screenshot  
`Network Tab`  
8. Compare the time DOMContentLoaded and Finish time for your usual internet connection and Slow 3G  
`Performance Tab`
9. Profile the page with Fast 3G connection. Analyze the results.

---

### [SQL task:](https://github.com/AdamCegGrid/practical_task_module_8/tree/main/SQL_Task)  
[Solution](https://github.com/AdamCegGrid/practical_task_module_8/tree/main/SQL_Task)  

1. Download DB and pdf schema
2. Prepare query for:
    - Select all publishers (publishers) that are from USA
    - Select all publishers (publishers) that are NOT from USA sort by name

<sub>*Attach requests for queries and screenshots with results*</sub>

---

### [GIT Basics task:](https://github.com/AdamCegGrid/GD_Internship)  
[Solution](https://github.com/AdamCegGrid/GD_Internship)  

**Part 1**


1. Create account on https://github.com/ 
2. Install GIT on your workstation https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
3. Setup git: change your global configs (add name and email, setup core text editor).
4. Generate ssh-key and integrate it with GitHub.
5. Create a new `GD_Internship` project on GitHub.
6. Clone project to your workstation.
7. Provide access for a mentor to your repository on GitHub.

**Part 2**

1. Open the git console in the `GD_Internship` directory and do the next steps.
2. Do all your experiments in the folder `task1_git_practice`.
3. Create an empty `readme.txt` file.
4. Make an init commit.
5. Create a develop branch and checkout on it.
6. Create `index.html` empty file. Commit.
7. Create a branch with the name `images`. Checkout. Add some images folder with images inside it. Commit.
8. Change your `index.html`. Add some image source inside it. Commit.
9. Go back to the develop branch.
10. Create a branch with the name `styles`. Add some styles folder with styles source inside it. Commit.
11. Change your `index.html`. Commit.
12. Go to the develop branch.
13. Merge two new branches into develop using git merge command. Resolve conflict if it appears.
14. Do not delete any branches!
15. Merge develop branch into master.
16. Checkout to the develop branch and repeat 7 items once more (use names `images2`, `styles2` for new branches). Now use the git `rebase` command for merging.  

<sub>*NOTE: As a result master/develop branches should contains all commits that were done in process*</sub>

**Part 3**

1. Try to inspect your repository with the git log command. Use different options with this command `git log --help`.
2. Push all your changes with all your branches to origin `git push origin all`.
3. Execute the command `git reflog` and save its content somewhere (not in the repository) with filename `GIT_Basics_homework.txt`.
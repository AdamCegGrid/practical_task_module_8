# Postman task:

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

<br>

## [Solution](https://github.com/AdamCegGrid/practical_task_module_8/blob/main/Postman_Task/Trello%20-%20Homework%20-%20Run%20results.png)  

<br>

![Solution](Trello%20-%20Homework%20-%20Run%20results.png)

<br>

## Tutorials:

- [Postman: The Complete Guide - REST API Testing - Udemy](https://www.udemy.com/course/postman-the-complete-guide/)
- [Postman Beginner's Course - API Testing](https://www.youtube.com/watch?v=VywxIQ2ZXw4)
- [API testing for Beginners with Real Project Examples](https://www.youtube.com/watch?v=dsZIi1SrXG4&list=PLedmK0jZBQvjiAikOeEWPV36bXY8YDlvs)
- [Postman API Testing](https://www.youtube.com/watch?v=IPpGqyeMEZU&list=PLL34mf651faPfS9z4BXdLfaw1KAaJOI7n)
- [Postman - pl](https://www.youtube.com/watch?v=hczgV-qY6s0&list=PL9jnDJ4h6Jbykm8CRq7vEW--8KoNKodFD)
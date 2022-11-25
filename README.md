<h1 align="center">Knab assignment</h1>

# Install and requirements

1. Cypress
2. JavaScript
4. Any IDE

Note:
You can find the assignment here  [Vigan Krasniqi assignment](https://github.com/ViganKrasniqi/Trello-API). 

First we need to install cypress:

```shell
npm install cypress
```

Open cypress, writting in terminal:

```shell
npx cypress open
```

Then it opens a Browser where you could run the test through UI


## 📁 Folder structure
```

cypress/
├─ e2e/
│  ├─ api/
│  │  ├─ accountsApi.cy.js
│  │  ├─ util.java
├─ fixtures/
│  ├─ httpConstants.js
│  ├─ itemConstants.js
├─ support/
│  ├─ e2e.js
│  ├─ commands.js


## Test analysis

The file accountApi have two test cases :
1. Send e request with valid credentials and check for status code 200 (Positive test case)
2. Send e request with invalid credentials and check for status code 403 (Negative test case)


## Suggestions for improvements:

-Test the creation of boards, using API and try to send different invalide values 
-Try to delete a board using API
-Try to delete a board of a user from another user, using API 

# 🖋️ Commits guide
Set of good practice rules for writing clean, easy, explicit, reusable and standardized commits, across all personal or group projects.

## 🏗️ Structure
A good commit message should be structured in three parts, as follow:

```
<type>[title]: <description>
[body]
[optional footer]
```

## 📒 Type and title
The <type> should always be in uppercasing and with an optional emoji to facilitate identification of each commit at first sight.

  | Commit | Description |
| ----------- | ----------- |
| 🎉 INITIAL | First commit  |
| ➕ ADD | A new function is added |
| ⚙️ FEATURE | A new feature is added |
| 🐞 BUGFIX | A bug or error is fixed |
| ♻️ REFACTOR | A refactor or code amend  |
| 🚨 TEST | A test is added |
| 👽 TRANSLATION | A new language is added |
| 🔀 MERGE | A function, file or block of code is removed |
| ➖ DELETE | A test is added |
| 📚 DOCS | Anything related to the documentation |
| 🖼️ STYLE| Anything related to styling |
| 🚀 DEPLOY | Anything related to deployment |
| ♿ A11Y | Anything related to accessibility |
| 🔖 VERSION | Anything related to versioning |
| 🏷️ TAGS  | Anything related to tags |
  
## 💬 Description
Short, objective and imperative text, with less than 50 characters.
  
## 📝 Body
It should be used to explain What and Why of the commit, it must also be short and objective.
  
## 🐾 Footer
Place to follow up issues or tickets, to keep a good track of the workflow.
  
##❗❗ Example
````
  🐞 BUGFIX: User authentication error  
  Authentication with Gmail now working for new sign up and login.
  Issue: #5

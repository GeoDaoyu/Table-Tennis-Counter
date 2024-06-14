# Contribution Guide

[View Chinese / 查看中文](./docs/CONTRIBUTING.zh-CN.md)

Welcome your contributions! Please follow these guidelines:  

Fork the repository.  
Create a new branch for your feature or bug fix.  
Write your code for the changes.  
<!-- Use [Prettier](https://prettier.io) to format your code.   -->
Commit your changes with a descriptive message.  
**Note: The commit message _must_ follow the [format below](#commit-message-format)**  
Push your branch to your fork.  
Submit a pull request to the main repository.  

## Commit Message Format

The commit message follows the [Angular team commit guidelines](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines), which are:  

```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

Meaning explained below.  
You can install [this VSCode extension](https://marketplace.visualstudio.com/items?itemName=redjue.git-commit-plugin) to assist with filling in the message.  

### Tag Meanings

#### type

Must be one of the following types:  
|     Type     |                                 Explanation                                 |
|--------------|-----------------------------------------------------------------------------|
| 🎉 init     | Project initialization                                                      |
| ✨ feat     | Adding new features                                                         |
| 🐞 fix      | Fixing bugs                                                                 |
| 📃 docs     | Modify documentation only                                                   |
| 🌈 style    | Only the spaces, formatting, commas, etc. were changed, not the code logic  |
| 🦄 refactor | Code refactoring, no new features added or bug fixed                        |
| 🎈 perf     | Optimization-related, such as improving performance, experience             |
| 🧪 test     | Adding test cases                                                           |
| 🔧 build    | Dependency-related content                                                  |
| 🐎 ci       | CI configuration related e.g. changes to k8s, docker configuration files    |
| 🐳 chore    | Change build process, or add dependencies, tools, etc.                      |
| ↩ revert    | Rollback to the previous version                                            |

#### scope
**Optional.**  
Scope.  
The scope can be anything specifying the place of the commit change. For example, `$location`, `$browser`, `$compile`, `$rootScope`, `ngHref`, `ngClick`, `ngView`, etc.  
When the change affects multiple scopes, use `*`.  

#### subject
Subject.  
The subject contains a brief description of the change:  
Use the imperative mood: "change" instead of "changed" or "changes"  
~~Do not capitalize the first letter~~ Actually, you can capitalize the first letter  
Do not end with a period (.)  

#### BLANK LINE
Blank line.  

#### body
Body.  
Just like in the subject, use the imperative mood: "change" instead of "changed" or "changes". The body should include the motivation for the change and compare it to the previous behavior.  

#### footer
Footer.  
The footer should contain any information about major changes and is also the location to reference the GitHub Issue that this commit closes.  
Major changes should start with `BREAKING CHANGE:`, followed by a space or two newlines. Then, the rest of the commit message will be used for this purpose.  
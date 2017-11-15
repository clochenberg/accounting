# Contribution Information

## Contribution to SpecTech Accounting

Every help is welcome, you don't have to be a professional PHP developer or SQL database engineer.
We appreciate any support with helping other users, translating the software or simply spreading
the word.


## Contents

* Get familiar with our Development Guidelines
* Contributing Code

---

## Get familiar with our Development Guidelines

We are following some strict development guidelines while developing.

### PHP
Coding Standard: PSR-2

### JavaScript
Use JShint / JSlint to check your JavaScript code and try to resolve all code issues.

### CSS
We use SASS only. The Sass files are compiled to minified and automatically prefixed CSS files.

---

## Contributing Code

:warning: **Read this carefully to prevent your pull request to be closed!**

1. Before you submit any code to the repository please take a look at the repositry and search for your issue!
    * If an issue exists and someone is working on it, please contact this person.
    * If an issue exists and no one is working on it, assign it to yourself or write a comment.
2. Always reference the issue ID (e.g. SA-317) in all commits you make for this issue.
3. Before you create a pull request, rebase from the development branch.
    * Add the development branch as a remote
    * Do a rebase with the following command: `git pull --rebase sa development`
    Where `sa` is the name of the remote and `development` the branch.
    * Solve all conflicts and check if your code is still working.
4. Submit the pull request, reference the issue ID in the title and add a meaningful description.

Please ask questions related to this process if you are unclear. Asking before doing anything will save your and our time.

---

> The name 'SpecTech Accounting' and the SpecTech logo are both copyright by Christo Lochenberg and www.spectech-it.co.za
and their usage is restricted! For more information visit http://www.spectech-it.co.za/license.html

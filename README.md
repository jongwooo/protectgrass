<p align="center">
  <img alt="protectgrass" src="https://protectgrass-bucket.s3.ap-northeast-2.amazonaws.com/assets/images/octocat.png" width="60" />
</p>
<h1 align="center">
  protectgrass
</h1>

<h3 align="center">
  🌿⚙️🤖
</h3>

<h3 align="center">
  Protect the grass on GitHub using GitHub Actions
</h3>

<p align="center">
  <a href="LICENSE">
    <img alt="GitHub" src="https://img.shields.io/github/license/jongwooo/protectgrass?color=blue">
  </a>
  <a href="https://github.com/jongwooo/protectgrass/actions?query=workflow%3A%22Protect+Grass%22">
    <img alt="GitHub Workflow Status" src="https://github.com/jongwooo/protectgrass/workflows/Protect%20Grass/badge.svg">
  </a>
</p>

## 🚀 Quick start

1.  **Fork this repository to yours**

2.  **Create a Personal access token**

    In `Account Settings / Developer Settings / Personal Access Token`, you can generate a [Personal access token](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line) for GitHub Actions. You can check the `repo` and `workflow` in the **Select scope**.

    <img alt="Select scope" src="https://protectgrass-bucket.s3.ap-northeast-2.amazonaws.com/assets/images/scope.png" width="50%">

3.  **Add your GitHub username and email to the Secrets**

    You just add the GitHub user name and email to [Secrets](https://help.github.com/en/actions/configuring-and-managing-workflows/creating-and-storing-encrypted-secrets) in `Repository / Settings / Secrets`. Secrets are encrypted environment variables that you create in a repository for use with GitHub Actions.

    | name         | value             |
    | ------------ | ----------------- |
    | `USER_NAME`  | [YOUR_USER_NAME]  |
    | `USER_EMAIL` | [YOUR_USER_EMAIL] |

    <img alt="Add a new secret" src="https://protectgrass-bucket.s3.ap-northeast-2.amazonaws.com/assets/images/secrets.png" width="50%">

## 🧐 What's inside?

A quick look at the top-level files and directories you'll see in a protectgrass project.

    .
    ├── .github/workflows
    ├── node_modules
    ├── .eslintrc.js
    ├── .gitignore
    ├── .prettierignore
    ├── .prettierrc.js
    ├── LICENSE
    ├── README.md
    ├── commit.js
    ├── history.log
    ├── package-lock.json
    └── package.json

1.  **`/.github/workflows`**: This directory contains settings about Github Actions.

2.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages) are automatically installed.

3.  **`.eslintrc.js`**: This is a configuration file for [ESLint](https://eslint.org/). ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs.

4.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

5.  **`.prettierignore`**: This file tells Prettier which files it should not format for.

6.  **`.prettierrc.js`**: This is a configuration file for [Prettier](https://prettier.io/). Prettier is a tool to help keep the formatting of your code consistent.

7.  **`LICENSE`**: protectgrass is licensed under the MIT license.

8.  **`README.md`**: A text file containing useful reference information about your project.

9.  **`commit.js`**: This file modifies the `history.log` file when it runs.

10. **`history.log`**: This log file contains the commit timestamp.

11. **`package-lock.json`** (See `package.json` below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t change this file directly).**

12. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

## 📝 License

Licensed under the [MIT License](LICENSE).

# Getting Started with Git and GitHub

This guide will walk you through the basic steps of creating a Git repository and performing essential version control tasks.

## Prerequisites

Before you begin, make sure you have Git installed on your computer. You can download it from [https://git-scm.com/](https://git-scm.com/).

## Creating a New Git Repository

1. **Create a New Directory:** Open your terminal or command prompt and navigate to the directory where you want to create your project. Use the `mkdir` command to create a new directory.

    ```bash
    mkdir my-project
    cd my-project
    ```

2. **Initialize a Git Repository:** Run the following command to initialize a new Git repository in your project folder.

    ```bash
    git init
    ```

## Adding and Committing Changes

1. **Create or Edit Files:** Add, modify, or delete files within your project directory.

2. **Add Changes:** To stage the changes for committing, use the following command, replacing `<file>` with the file name or `.` to add all changes.

    ```bash
    git add <file>
    ```

3. **Commit Changes:** Commit your changes with a meaningful message.

    ```bash
    git commit -m "Added feature X"
    ```

## Working with Remotes (GitHub)

1. **Create a GitHub Account:** If you haven't already, sign up for a GitHub account at [https://github.com/](https://github.com/).

2. **Create a New Repository on GitHub:**

    a. Log in to GitHub.

    b. Click the "+" icon in the top-right corner and select "New repository."

    c. Follow the prompts to create your repository. Make sure to leave the "Initialize this repository with a README" option unchecked if you already have a Git repository locally.

3. **Link Your Local Repository to GitHub:**

    a. Copy the URL of your GitHub repository.

    b. In your terminal, add the remote repository with the following command, replacing `<URL>` with your repository's URL:

    ```bash
    git remote add origin <URL>
    ```

4. **Push Your Code to GitHub:**

    ```bash
    git push -u origin main
    ```

Congratulations! You've successfully created a Git repository, made changes, and pushed them to GitHub.

Remember to replace `<file>` and `<URL>` with your specific file names and repository URLs as needed.
# PLPBasicGitAssignment
Certainly! Below is a README.md file content that documents the steps and commands used for the Git and GitHub setup and submission process:

---

# PLPBasicGitAssignment

This repository serves as a basic demonstration of setting up a Git repository locally and pushing changes to GitHub.

## Requirements
- GitHub account
- Git installed locally
- Code editor (e.g., Visual Studio Code)

## Task 1: Repository Setup

### 1. GitHub Repository Creation
- Log in to your GitHub account.
- Create a new repository on GitHub named "PLPBasicGitAssignment".
- Initialize the repository with a README file.

## Task 2: Local Setup

### 1. Local Folder Setup
- Create a new folder on your local machine named "PLPBasicGitAssignment".
- Open a terminal or command prompt and navigate to the created folder.

### 2. Git Initialization
- Initialize a new Git repository in your local folder using the following command:
  ```bash
  git init
  ```

### 3. Connecting to GitHub
- Link your local repository to the GitHub repository you created in Task 1 using the following command:
  ```bash
  git remote add origin <repository-url>
  ```
  Replace `<repository-url>` with the actual URL of your GitHub repository.

## Task 3: Making Changes

### 1. Create a File
- Inside your local folder, create a new text file named `hello.txt`.
- Add a simple text message, for example, "Hello, Git!" to the file.

### 2. Committing Changes
- Stage the changes using the following command:
  ```bash
  git add hello.txt
  ```
- Commit the changes with a commit message:
  ```bash
  git commit -m "Add hello.txt with a greeting"
  ```

## Task 4: Pushing to GitHub

### 1. Pushing to GitHub
- Push the committed changes to your GitHub repository using the following command:
  ```bash
  git push -u origin main
  ```

## Task 5: Verification

### 1. Verify on GitHub
- Visit your GitHub repository in a web browser to confirm that the `hello.txt` file and commit message are visible.


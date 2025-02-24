# Module Assignment: Version Control using Git and GitHub

## Project: Module 1

### Topic: Version Control using Git and GitHub - Commit, Branching, Merging, and Pull Requests

## Steps to Complete the Assignment:

### 1. Set Up a Local Git Repository:
- Initialize a new Git repository in your local development environment.
- Create a new text file named `README.md` and add some initial project description or any content you choose.
- Stage and commit this file with an appropriate commit message.

### 2. Create a New GitHub Repository:
- Create a new repository on GitHub with a meaningful name.
- Link your local repository to the remote GitHub repository using:
  ```sh
  git remote add origin <your-github-repo-url>
  ```
- Push your local commits to the GitHub repository:
  ```sh
  git push -u origin main
  ```

### 3. Branching:
- Create a new branch in your local repository called `dev`:
  ```sh
  git checkout -b dev
  ```
- Switch to the `dev` branch and create a new file named `hello.txt`.
- Commit the changes to the `dev` branch.

### 4. Pushing the New Branch:
- Push your `dev` branch to GitHub:
  ```sh
  git push -u origin dev
  ```
- Verify that the new branch is visible on GitHub.

### 5. Create a Pull Request:
- Once the new changes have been committed and pushed, go to your GitHub repository.
- Open a pull request (PR) to merge your `dev` branch into the `main` branch.
- Provide a descriptive message about the changes made.

### 6. Merge the Pull Request:
- After reviewing your pull request, merge the pull request into the `main` branch on GitHub.
- Update your local `main` branch after merging:
  ```sh
  git checkout main
  git pull origin main
  ```

## Submission Instructions:
- Ensure your GitHub repository is public.
- Share the link to your public GitHub repository where all the changes and pull requests can be viewed.

## Deliverables:
- A public GitHub repository containing:
  - The initial commit with the `README.md` file.
  - A new branch (`dev`) with changes and a pull request created.
  - The pull request merged back into the `main` branch.

## Important Notes:
- Your repository should be structured neatly with meaningful commit messages and proper branch names.
- Ensure that the pull request contains a descriptive message explaining the changes and their purpose.

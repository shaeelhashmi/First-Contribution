# Contributing to This Repository

Thank you for your interest in contributing to this repository! Follow these steps to learn the process of contributing:

## Step 1: Fork the Repository
- Go to the repository page on GitHub.
- Click the **Fork** button in the top-right corner to create a copy of the repository under your account.

## Step 2: Clone Your Fork
- Clone the forked repository to your local machine using the command:
  ```bash
  git clone https://github.com/<your-username>/<repository-name>.git
  ```
- Go into the project folder
  ```bash
  cd <repository-name>
  ```
## step 3: Set upstream branch:
- Set the upstream branch for your fork to stay in sync with the original repository:
  ```bash
  git remote add upstream https://github.com/shaeelhashmi/First-contribution.git
  ```
## Step 4: Add Your GitHub Username
- Open the `README.md` file in the repository using your preferred text editor.
- Add your GitHub username to the list in the file.
- **Rules for Adding Your Name:**
  1. If your name is not the first in the list, add a comma (`,`) before your name.
  2. End the list with a period (`.`) after your name.

## Step 5: Commit Your Changes
- Stage your changes:
  ```bash
  git add .
  ```
- Commit the changes with a clear message:
  ```bash
  git commit -m <Your Commit Message>
  ```
## Step 6: Sync Your Changes and Push
- Fetch the latest changes from the upstream repository:
  ```bash
  git fetch upstream
  ```
- Merge any changes into your fork's `main` branch:
  ```bash
  git checkout main
  git merge upstream/main
  ```
- Push your changes to your forked repository:
  ```bash
  git push origin main
  ```

## Step 7: Create a Pull Request
- Go to the original repository on GitHub.
- Click **Pull Requests** > **New Pull Request**.
- Select your branch from your forked repository and submit the pull request.
- Provide a brief description of your changes.

Thank you for contributing to this repository and learning the process of collaboration on GitHub!

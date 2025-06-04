# Git and GitHub Commands Cheat Sheet

This repository contains a quick reference of common Git and GitHub commands.
Use it as a handy guide when working with repositories.

## Git Commands
1. **Initialize a new Git repository:**
   ```bash
   git init
   ```
   Creates a `.git` directory and begins tracking version history.

2. **Clone a repository:**
   ```bash
   git clone <repository_url>
   ```
   Downloads an existing repository to your local machine.

3. **Check the status of the repository:**
   ```bash
   git status
   ```
   Shows modified, staged and untracked files.

4. **Stage changes for commit:**
   ```bash
   git add <file_name>
   ```
   Adds a file to the staging area.

   - Stage all changes:
     ```bash
     git add .
     ```

5. **Commit changes:**
   ```bash
   git commit -m "Commit message"
   ```
   Saves the staged snapshot to the project history.

6. **Pull changes from a remote repository:**
   ```bash
   git pull origin <branch_name>
   ```
   Fetches and merges updates from the specified branch.

7. **Push changes to a remote repository:**
   ```bash
   git push origin <branch_name>
   ```
   Uploads committed changes to the remote branch.

8. **Create a new branch:**
   ```bash
   git branch <branch_name>
   ```
   Makes a new branch pointer without switching to it.

9. **Switch to a different branch:**
   ```bash
   git checkout <branch_name>
   ```
   Changes HEAD to the specified branch.

   - Create and switch to a new branch:
     ```bash
     git checkout -b <new_branch_name>
     ```

10. **Merge branches:**
    ```bash
    git merge <branch_name>
    ```
    Combines the specified branch into the current branch.

11. **View commit history:**
    ```bash
    git log
    ```
    Displays a list of previous commits.

12. **Discard local changes:**
    ```bash
    git checkout -- <file_name>
    ```
    Restores a file to the last committed state.

13. **Undo the last commit (local):**
    ```bash
    git reset HEAD^
    ```
    Reverts to the commit before HEAD while keeping changes unstaged.

## GitHub Commands

1. **Add a remote repository:**
   ```bash
   git remote add origin <repository_url>
   ```
   Links a local repository to a remote one.

2. **Set upstream branch:**
   ```bash
   git branch --set-upstream-to=origin/<branch_name>
   ```
   Associates the current branch with a remote tracking branch.

3. **Create a pull request:**
   After pushing changes to your branch, open a pull request on GitHub to start a code review.

4. **Fetch changes from a remote repository:**
   ```bash
   git fetch origin
   ```
   Retrieves updates without merging them.

5. **View remote branches:**
   ```bash
   git branch -r
   ```
   Lists all branches available on the remote.

6. **Delete a remote branch:**
   ```bash
   git push origin --delete <remote_branch_name>
   ```
   Removes the specified branch from the remote repository.

7. **View pull requests:**
   On GitHub, navigate to the "Pull Requests" tab to see open and closed pull requests.

8. **Merge a pull request (locally):**
   After reviewing and approving a pull request on GitHub, merge it locally using:
   ```bash
   git pull origin <branch_name>
   ```

9. **View collaborators and contributors:**
   On the GitHub repository page, navigate to "Settings" > "Collaborators" to manage collaborators. Use the "Insights" tab to view contributors.

10. **Fork a repository:**
    On GitHub, click the "Fork" button on the top right of a repository to create your own copy.


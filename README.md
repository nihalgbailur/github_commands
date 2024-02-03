# github_commands
```markdown
# Git and GitHub Commands Cheat Sheet
  ```

## Git Commands
1. **Initialize a new Git repository:**
   ```bash
   git init
   ```

2. **Clone a repository:**
   ```bash
   git clone <repository_url>
   ```

3. **Check the status of the repository:**
   ```bash
   git status
   ```

4. **Stage changes for commit:**
   ```bash
   git add <file_name>
   ```

   - Stage all changes:
     ```bash
     git add .
     ```

5. **Commit changes:**
   ```bash
   git commit -m "Commit message"
   ```

6. **Pull changes from a remote repository:**
   ```bash
   git pull origin <branch_name>
   ```

7. **Push changes to a remote repository:**
   ```bash
   git push origin <branch_name>
   ```

8. **Create a new branch:**
   ```bash
   git branch <branch_name>
   ```

9. **Switch to a different branch:**
   ```bash
   git checkout <branch_name>
   ```

   - Create and switch to a new branch:
     ```bash
     git checkout -b <new_branch_name>
     ```

10. **Merge branches:**
    ```bash
    git merge <branch_name>
    ```

11. **View commit history:**
    ```bash
    git log
    ```

12. **Discard local changes:**
    ```bash
    git checkout -- <file_name>
    ```

13. **Undo the last commit (local):**
    ```bash
    git reset HEAD^
    ```

## GitHub Commands

1. **Add a remote repository:**
   ```bash
   git remote add origin <repository_url>
   ```

2. **Set upstream branch:**
   ```bash
   git branch --set-upstream-to=origin/<branch_name>
   ```

3. **Create a pull request:**
   After pushing changes to your branch, create a pull request on the GitHub repository.

4. **Fetch changes from a remote repository:**
   ```bash
   git fetch origin
   ```

5. **View remote branches:**
   ```bash
   git branch -r
   ```

6. **Delete a remote branch:**
   ```bash
   git push origin --delete <remote_branch_name>
   ```

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


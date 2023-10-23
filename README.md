# git_and_github_activity

**Activity Title: Introduction to Git and GitHub**

**Objective:** In this activity, you will learn the basics of version control using Git and how to collaborate with others on GitHub.

**Prerequisites:**
- Create a GitHub account (if you don't have one already).
- Install Git on your local machine.

**Instructions:**

**Step 1: Setting up a Local Git Repository**

1. Open a terminal or Git Bash.
2. Navigate to the directory where you want to create your project.
3. Initialize a new Git repository with the following command:
   ```
   git init
   ```
4. Create a new text file (e.g., `pyfun.py`) and add some content to it.
5. Add this file to your Git repository:
   ```
   git add pyfun.py
   ```
6. Commit your changes with a meaningful message:
   ```
   git commit -m "Initial commit"
   ```

**Step 2: Creating a GitHub Repository**

1. Go to your GitHub account and click on the '+' sign in the top right corner, then select "New Repository."
2. Give your repository a name, choose public or private, and add a README file.
3. Click "Create repository."

**Step 3: Linking Local and Remote Repositories**

1. In your local terminal, add the remote repository URL you just created on GitHub:
   ```
   git remote add origin <your-repo-url>
   ```
2. Push your local repository to GitHub:
   ```
   git push -u origin main
   ```

**Step 4: Collaboration with Others**

1. Go to your GitHub repository on the GitHub website.
2. Click on the "Settings" tab.
3. Under "Manage access," click "Invite a collaborator" and invite a friend (using their GitHub username or email).
4. Your collaborator should accept the invitation.
5. Both you and your collaborator can now make changes to the project and collaborate using Git and GitHub.

**Step 5: Making Changes and Pull Requests**

1. Make changes to your project locally and commit them.
2. Push your changes to GitHub.
3. In your GitHub repository, click on "New Pull Request" to suggest changes to the original repository.
4. Review and merge the changes.

**Step 6: Using Branches**

1. Create a new branch in your local repository:
   ```
   git checkout -b new-feature
   ```
2. Make changes in this branch, commit, and push them to GitHub.
3. Create a pull request to merge the new branch into the master branch.

**Step 7: Git and GitHub Best Practices**

- Explore branching strategies (feature branches, hotfixes, etc.).
- Use meaningful commit messages.
- Regularly update your local repository with changes from the remote repository (`git pull`).
- Collaborate with your partner to practice working on the same codebase.

**Conclusion:**
Congratulations, you've completed this Git and GitHub activity for beginners! You've learned how to set up a Git repository, collaborate with others, and use essential Git and GitHub commands.

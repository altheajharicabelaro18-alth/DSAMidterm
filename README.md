# HELLO WORLD

Step-by-Step Guide
How to set up Git, VS Code, and push your project to GitHub
1. <strong>Install Visual Studio Code</strong>
 Go to https://code.visualstudio.com/download and download the version for your computer.
 Install it by clicking Agree and Next until it finishes.
 After installing, open VS Code.
2. <strong>Install Git</strong>
 Go to https://git-scm.com/ and download Git.
 Run the installer and accept the default options.
 After installation, open Command Prompt or Git Bash and type: git --version
 If it shows a version number, Git is installed correctly.
 In Windows 11, right-click your folder, click Show more options, then choose Git Bash.
3. <strong>Create a project folder</strong>
 Create a folder named for your project (example: MyProject or DSA-midterm) on your Desktop or Documents.
 Inside that folder, make a file named hello-world.html to test.
4. <strong>Open the folder in VS Code</strong>
 Right-click the folder and select “Open with Code” or open Command Prompt in that folder and type: code .
 In VS Code, click File → Auto Save to turn it on.
5. <strong>Open the VS Code terminal</strong>
 Click View → Terminal or press Ctrl + `.
 If your terminal shows PowerShell, you can change it by clicking the dropdown arrow and selecting Command Prompt or Git Bash.
6. <strong> Install helpful VS Code extensions</strong>
 Click the Extensions icon on the left.
 Install these:
Conventional Commits (optional but helpful)

Git (built-in in VS Code)

GitLens (optional for viewing commit history)
 Sign in with your GitHub account from the lower-left corner of VS Code.

7. <strong> Initialize Git and make your first commit</strong>
 In the VS Code terminal, type:
 git init
 Then configure your name and email (do this only once):
 git config --global user.name "Your Name"
 git config --global user.email "your-email@example.com"
 Add all files to Git:
 git add .
 Make your first commit:
 git commit -m "Initial commit"
 Rename the branch to main:
 git branch -M main
8. <strong>Create a repository on GitHub</strong>
 Go to GitHub → click New repository.
 Type the repository name (example: DSA-midterm) → choose Public → click Create repository.
 Copy the HTTPS URL of the repo (ends with .git).
 Back in VS Code terminal, connect your local folder to GitHub:
 git remote add origin https://github.com/yourusername/DSA-midterm.git
 Push your files to GitHub:
 git push -u origin main

If you see “Repository not found,” check that you are logged in to GitHub, and that the URL is correct with .git at the end.

9. <strong>Use VS Code Source Control</strong>
 Click the Source Control icon on the left side.
 You’ll see your changed files.
 Click the plus (+) sign to stage them, type a commit message, then click the check mark to commit.
 Click the circular arrows (Sync or Push) to upload to GitHub.
10. <strong>Example workflow when editing</strong>
 Edit hello-world.html.
 Changes will appear in Source Control.
 Stage files, write a commit message like “feat: add hello world file,” and push to GitHub.
11. <strong>Clone your repository on another computer</strong>
 Open Git Bash or Command Prompt in any folder.
 Type: git clone https://github.com/yourusername/DSA-midterm.git
 Then open it in VS Code by typing: code DSA-midterm
 You now have all your files and commit history on the new computer.

# PLPBasicGitAssignment
1. GitHub Repository Creation
    Logged in to my GitHub account.
    Created a new repository on GitHub:
    Clicked the + button in the top-right corner and selected New repository.
    Named the repository PLPBasicGitAssignment.
    Checked the box to initialize the repository with a README file.
    Clicked Create repository.

Task 2: Local Setup
    2. Local Folder Setup
    Created a new folder on my local machine:
    Navigated to my file explorer.
    Created a new folder and named it PLPBasicGitAssignment.
    Opened a terminal(git bash) and navigated to the created folder:

    cd /path/to/PLPBasicGitAssignment
    3. Git Initialization
    Initialized a new Git repository in my local folder:

    git init
    4. Connecting to GitHub
    Linked my local repository to the GitHub repository I created in Task 1:

    git remote add origin <https://github.com/Naliea/PLPBasicGitAssignment.git.>

Task 3: Making Changes
    5. Create a File
    Inside my local folder,I created a new text file named hello.txt.
    Added a simple text message to hello.txt ( "Hello, Git!") using a text editor or the echo command:

    6. Committing Changes
    Staged the changes:

    git add hello.txt
    Committed the changes with a message:

    git commit -m "Add hello.txt with a greeting"
Task 4: Pushing to GitHub
    7. Pushing to GitHub
    Pushed the committed changes to your GitHub repository:

    git push -u origin main
    Task 5: Verification
    8. Verify on GitHub
    Visited my GitHub repository in a web browser.
    Confirmed that the hello.txt file and the commit message "Add hello.txt with a greeting" are visible.
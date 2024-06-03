# A02

Part 1: Directions on Using VS Code

1. **Download and Install VS Code**

   Download VS Code from the official Visual Studio Code website. Depeding on your operating system of course.

2. **Set Up VS Code with GitHub** (the hardest step in this whole process in my opinion)

   a. **Install Git**: If Git is not installed, download it from Git-SCM and install it. Please make sure Git is in your system PATH.

   b. **Install GitHub Extension**: In VS Code, go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window. Search for "GitHub Pull Requests and Issues" and install it.

3. **Clone a Repository**

   a. Open VS Code and open the Command Palette.

   b. Type `Git: Clone` and select it. 

   c. Enter the URL of the repository you want to clone and select a folder to clone the repository into.

4. **Create a Branch**

   a. Click on the Git icon in the Activity Bar on the side of the window to open the Source Control view.

   b. Click on the branch name in the status bar at the bottom of the window, then click `+ Create new branch` and name it appropriately, e.g., `feature-branch`.

5. **Make Changes and Commit**

   a. Open the file you want to edit in the Explorer view.

   b. Make your changes in the editor.

   c. Save the changes and go to the Source Control view.

   d. Enter a commit message in the input box at the top.

   e. Click the checkmark icon to commit the changes.

6. **Push Changes to GitHub**

   a. In the Source Control view, click the more actions button.

   b. Select `Push` from the dropdown menu.

7. **Pull Changes from GitHub**

   a. In the Source Control view, click the more actions button.

   b. Select `Pull` from the dropdown menu to fetch and integrate changes from the remote repository.

8. **Merge Branches**

   a. Click on the branch name in the status bar at the bottom of the window.

   b. Select `Merge Branch` and choose the branch you want to merge into your current branch.

### Part 2: Glossary

- **Branch**: An exact copy version of a repository, allowing changes to be done without affecting the main code.
- **Clone**: A copy of a repository that is stored locally.
- **Commit**: Shows changes made to the repository.
- **Fetch**: Downloading objects and references from another repository.
- **GIT**: A control system for tracking changes in source code.
- **Github**: A web-based platform for version control and collaboration using Git.
- **Merge**: Combining the changes from two branches into one.
- **Merge Conflict**: A situation or issue where Git cannot automatically resolve differences between branches.
- **Push**: Uploading local repository content to a remote repository.
- **Pull**: Fetching and using changes from a remote repository to the local repository.
- **Remote**: A version of the repository that is hosted on the internet or network.
- **Repository**: A space where your project lives forever as stated in class.

### References

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Documentation](https://docs.github.com/)
- [VS Code Documentation](https://code.visualstudio.com/docs)
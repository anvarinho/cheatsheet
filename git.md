### 01 Git Configuration

| Command                                                 | Description                                                           |
| ------------------------------------------------------- | --------------------------------------------------------------------- |
| [`git config --global user.name "Your Name"`](#)        | Set the name that will be attached to your commits and tags.          |
| [`git config --global user.email "you@example.com"`](#) | Set the email address that will be attached to your commits and tags. |
| [`git config --global color.ui auto`](#)                | Enable some colorization of Git output.                               |

### 02 Starting a Project

| Command                        | Description                                                                                                                                                                                 |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`git init [project name]`](#) | Create a new local repository in the current directory. If `[project name]` is provided, Git will create a new directory named `[project name]` and will initialize a repository inside it. |
| [`git clone <project url>`](#) | Downloads a project with the entire history from the remote repository to the code.                                                                                                         |

### 03 Day-to-Day Work

| Command                         | Description                                                                                                                                                                          |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [`git status`](#)               | Displays the status of your working directory. Options include new, staged, and modified files. It will retrieve branch name, current commit identifier, and changes pending commit. |
| [`git add [file]`](#)           | Add a file to the staging area. Use `.` in place of the full file path to add all changed files from the current directory down into the directory tree.                             |
| [`git diff [file]`](#)          | Show changes between working directory and staging area.                                                                                                                             |
| [`git diff --staged [file]`](#) | Shows any changes between the staging area and the repository.                                                                                                                       |
| [`git checkout -- [file]`](#)   | Discard changes in the working directory. This operation is unrecoverable.                                                                                                           |
| [`git reset -- [file]`](#)      | Revert some paths in the index (or the whole index) to their state in HEAD.                                                                                                          |
| [`git commit`](#)               | Create a new commit from changes added to the staging area. The commit must have a message!                                                                                          |
| [`git rm [file]`](#)            | Remove file from working directory and staging area.                                                                                                                                 |

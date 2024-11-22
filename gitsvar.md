# Kest_verkefni_4_2

1. **What does `cd -` do?**
   - The `cd -` command switches back to the previous directory you were in before the last `cd` command.

2. **What does `ls -` do?**
   - The `ls` command lists the contents of the current directory. The `-` in `ls -` is invalid unless it is followed by valid options (e.g., `ls -l` for detailed listing).

3. **What does `pwd -` do?**
   - The `pwd` command prints the current working directory. The `-` is unnecessary and ignored.

4. **What does `mkdir -` do?**
   - The `mkdir` command creates a new directory. The `-` must be followed by options (e.g., `mkdir -p` to create parent directories as needed).

## Git Commands

5. **What does `git clone` do?**
   - The `git clone` command creates a copy of an existing repository from a remote server (e.g., GitHub) onto your local machine.

6. **What does `git status` do?**
   - The `git status` command shows the current state of the working directory and staging area. It lists changes, staged files, and files yet to be staged or committed.

7. **What does `git diff` do?**
   - The `git diff` command displays differences between changes in your working directory and the staged area or between commits.

## Git Commands Together

8. **What do `git log`, `git checkout`, and `git branch` do together?**
   - These commands are used for navigating and managing branches in a repository:
     - `git log`: Displays the commit history.
     - `git checkout`: Switches to a different branch or commit.
     - `git branch`: Lists or manages branches.
   - Together, these commands allow version control and movement between different states of the repository.

## General Questions

9. **What is version control?**
   - Version control is a system for tracking and managing changes to files and projects over time. It allows collaboration, history tracking, and rollback to previous versions.

10. **What are the main advantages of using GIT?**
    - Distributed version control (local and remote repositories).
    - Collaboration through branching and merging.
    - History tracking and rollback capabilities.
    - Efficiency and speed for large projects.
    - Open-source and widely supported.

11. **How often should you commit to a project?**
    - Commit often, whenever a meaningful change is made. For example, after completing a small task or fixing a bug. This keeps the history clear and manageable.

12. **What are the "Working Directory" and "Staging Area" in GIT?**
    - **Working Directory**: The local files and folders in your repository. This is where you make changes.
    - **Staging Area**: A preparation area where changes are added (`git add`) before committing to the repository.

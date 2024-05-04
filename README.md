TASK 3
What Do You Understand By Git? 
Git is a distributed version control system (DVCS) designed to track changes in source code during software development. It allows multiple developers to collaborate on projects efficiently by managing changes to the codebase. Here are some key aspects of Git:
1.	Version Control: Git tracks changes to files over time, allowing developers to view previous versions of the code, revert to earlier states, and compare changes between versions.
2.	Distributed: Unlike centralized version control systems, each developer's copy of the code repository in Git is a complete repository with its full history. This enables developers to work offline and independently, then later synchronize their changes with others.
3.	Branching and Merging: Git encourages the use of branching, where developers can create separate branches to work on new features or bug fixes without affecting the main codebase. Branches can be easily merged back into the main branch when the changes are ready.
4.	Collaboration: Git facilitates collaboration among developers by providing tools for sharing code changes, reviewing each other's work, and resolving conflicts that may arise when merging changes from different branches.
5.	Speed and Efficiency: Git is designed to be fast and efficient, even with large codebases. Operations such as committing changes, branching, merging, and comparing versions are optimized for speed.
6.	Open Source: Git is an open-source project, which means its source code is freely available for anyone to use, modify, and distribute under the terms of the GNU General Public License (GPL).
TASK 4
Define Version Control
Version control, also known as source control or revision control, is a system that manages changes to documents, files, or any set of information over time. It allows multiple users to collaborate on projects by keeping track of modifications, recording who made the changes, and enabling the retrieval of earlier versions if needed.
Key features of version control systems include:
1.	Tracking Changes: Version control systems record every change made to files, including additions, deletions, and modifications.
2.	Revision History: They maintain a history of changes, allowing users to view past versions of files and revert to previous states if necessary.
3.	Collaboration: Version control enables multiple users to work on the same files simultaneously while managing conflicts that may arise when merging changes.
4.	Branching and Merging: Users can create separate branches to work on new features or experiments without affecting the main codebase. Branches can later be merged back into the main branch.
5.	Concurrency: Version control systems handle concurrent access to files, ensuring that changes made by different users do not interfere with each other.
6.	Backup and Recovery: By storing multiple versions of files, version control systems serve as a backup mechanism, protecting against data loss due to accidental deletion or corruption.
TASK 5
Describe The Process Of Committing A Project To Github Repository.
Committing a project to a GitHub repository involves several steps. Here's a general outline of the process:
1.	Initialize a Git repository locally: Navigate to your project directory in the command line interface (CLI) or terminal and initialize a Git repository by running the command git init. This sets up Git to track changes in your project.
2.	Add files to the staging area: Use the git add command to add the files you want to include in the commit to the staging area. For example, to add all files, you can use git add ..
3.	Review changes: Optionally, you can use the git status command to review the files that have been modified, added, or deleted, and ensure that you're committing the correct changes.
4.	Commit changes: Once you're satisfied with the changes, commit them to the local repository using the git commit command. You'll need to provide a commit message that describes the changes you're committing. For example: git commit -m "Add initial project files".
5.	Create a GitHub repository: Go to GitHub and create a new repository. You can do this by clicking on the "+" icon in the top right corner of the page and selecting "New repository". Follow the prompts to set up your repository with a name, description, and other options.
6.	Link local repository to the remote repository: Copy the URL of the GitHub repository you just created. Then, in your terminal, add the GitHub repository as a remote by running the command git remote add origin <repository_URL>.
7.	Push changes to GitHub: Finally, push your committed changes from your local repository to the remote repository on GitHub using the git push command. For example: git push -u origin main (assuming your main branch is named "main").


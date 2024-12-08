+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| 4cc68b56d6c7447cb1fc4bde0ee777fd |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Doniah Camille G. Dizon    | DATE                   |          |
|                                  | PERFORMED:11/20/2024   |          |
+----------------------------------+------------------------+----------+
| Section:IDC1                     | DATE                   |          |
|                                  | SUBMITTED:11/20/2024   |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Git Basics

Answer the following research questions about Git, GitLab desktop and
GitHub.

1.  What is Git, and why is it important in software development?

> \- Git is a version control system used for tracking changes in
> computer files. It is generally used for source code management in
> software development. It is important to software development because
> It allows multiple developers to work together and it can track
> changes in the source where we can go back to old edits in the code.

2.  How does Git track changes in a project?

> \- Git tracks changes in a project by maintaining a history of
> snapshots. Every time you commit, Git captures the state of your
> project files, storing them as snapshots. These snapshots are saved
> using a unique hash (SHA), allowing you to retrieve or compare
> versions. Git operates in three main areas: the working directory,
> staging area, and repository. Files move through these stages as they
> are modified, staged, and committed.

3.  What is the difference between a local repository and a remote
    repository in Git?

-   **Local Repository**: Resides on your local machine and includes all
    the project files and full version history. You work with this
    repository offline.

-   **Remote Repository**: Hosted on a server, such as GitHub or GitLab,
    enabling collaboration. It allows multiple developers to push and
    pull changes. Synchronization between local and remote repositories
    is done using commands like git push, git pull, or git fetch.

4.  What are the basic Git commands?

-   **git init**: Initialize a new repository.

-   **git add**: Stage changes for commit.

-   **git commit**: Save staged changes to the repository.

-   **git status**: View the status of files in your project.

-   **git push**: Upload local commits to a remote repository.

-   **git pull**: Fetch and merge changes from a remote repository.

-   **git clone**: Create a local copy of a remote repository.

-   **git branch**: List, create, or delete branches.

-   **git merge**: Combine branches into one.

5.  How do you check the status of a Git repository?

> \- The git status command tells the current state of the repository.
> The command provides the current working branch. If the files are in
> the staging area, but not committed, it will be shown by the git
> status.

6.  What is the purpose of branches in Git, and how do you create and
    switch between them?

> \- Git branches provide a structured way to manage code changes,
> enabling a smooth integration of new features, bug fixes, and
> experimental ideas without disrupting the main codebase.
> Traditionally, we used the git checkout command to move between
> branches

7.  What are GitLab Desktop and GitHub, and how are they different from
    Git?

> \- GitLab is a web-based platform that streamlines development
> workflows. It does this by merging Git repository management with
> continuous integration (CI), deployment, and collaboration
> tools. While GitHub on the other hand is a cloud-based hosting service
> that provides a user-friendly web interface for managing Git
> repositories. It allows developers to store, share, and collaborate on
> their codebase with teams or the open-source community.

8.  How do you connect a local Git repository to a GitLab or GitHub
    repository?

> \- To connect a local Git repository to GitHub or GitLab, first create
> a repository on the platform and copy the URL. Then, initialize your
> local repository with git init if you haven\'t already, and link it to
> the remote repository by running git remote add origin
> \<repository-URL\>. Push your changes to the remote repository using
> git push -u origin main (or your branch). To confirm the connection,
> use git remote -v

9.  What are the steps to collaborate with others using GitLab or
    GitHub?

> \- To collaborate with others, first clone the remote repository using
> git clone \<repository-URL\>. After making local changes, create a new
> branch with git checkout -b \<branch-name\> and commit your changes.
> Push your branch to the remote with git push origin \<branch-name\>.
> Then, open a pull request (GitHub) or merge request (GitLab) for
> others to review your work. Once approved, your changes can be merged
> into the main branch. Regularly pull the latest updates using git pull
> origin main to keep your local repository in sync.

10. How do you resolve merge conflicts in Git?

-   \- To resolve merge conflicts in Git, first, identify the
    conflicting files by running git status after attempting a merge.
    Git will mark the conflicting sections in the files with special
    markers: \<\<\<\<\<\<\< HEAD, =======, and \>\>\>\>\>\>\>
    \<branch-name\>. You must manually open the files and decide which
    changes to keep---either from your branch or the incoming branch, or
    a combination of both. After resolving the conflicts and removing
    the markers, save the file. Stage the resolved files with git add
    \<file-name\>, and then complete the merge by committing the changes
    with git commit. Finally, push your changes to the remote repository
    using git push origin \<branch-name\>. Always test the merged code
    to ensure no issues remain after the conflict resolution

11. What is a pull request, and why is it used in GitHub?

> \- A pull request is a request to merge code changes from one branch
> to another in a repository. It\'s used to review, discuss, and ensure
> quality before integrating code.

12. What are some best practices for writing commit messages?

> \- To collaborate with others using GitHub or GitLab, first clone the
> remote repository with git clone \<repository-URL\>. Next, create a
> new branch to work on using git checkout -b \<branch-name\>, and make
> your changes locally. Afterward, stage and commit the changes with git
> add.And git commit -m \"Your message\". Push your branch to the remote
> repository using git push origin \<branch-name\>. Then, open a pull
> request (GitHub) or merge request (GitLab) to have your changes
> reviewed. Once approved, the changes can be merged into the main
> branch. Be sure to keep your local repository updated by regularly
> running git pull origin main.

Reference:

<https://docs.github.com/en/get-started/using-git>

<https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories>

<https://www.freecodecamp.org/news/git-and-github-for-beginners/>

<https://docs.github.com/en/pull-requests>

<https://www.simplilearn.com/tutorials/git-tutorial/git-commands#:~:text=The%20git%20status%20command%20tells,shown%20by%20the%20git%20status>.

<https://www.datacamp.com/tutorial/git-switch-branch>

<https://kodekloud.com/blog/git-vs-github-vs-gitlab/#:~:text=your%20project's%20needs.-,Key%20Takeaways,CD%20pipelines%20and%20security%20features>..

<https://docs.github.com/en/get-started/using-git>

<https://docs.gitlab.com/ee/user/project/repository/>

<https://docs.github.com/en>

<https://git-scm.com/book/id/v2/Git-Basics-Recording-Changes-to-the-Repository>

<https://docs.gitlab.com/ee/user/project/repository/merge_requests/merge_conflicts.html>

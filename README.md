## Git_practice
Practice repo to test new connections.

#### About Git & GitHub
  <div style="display: inline_block"><br>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg" width="80" height="80"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="80" height="80"/>
  </div>

---

Git is used worldwide to help developers track changes while working on different parts of the same project. GitHub is a web application that can be integrated with Git. Together, users can host, organize, explore, and collaborate on code with teams and the developer community at large. Next, dive into GitHub Copilot, a generative AI that can help streamline your workflow.

#### Skills you will acquire

#

#### Learn how Git and GitHub work

Git is a distributed version control system that allows developers to work on a project without the need to be physically present in the same location. It tracks and records all changes made to a set of files, allowing you to retrieve specific versions later.

Here are some key Git concepts:

1. **Repository**: A Git repository is a directory where all your project files are stored and tracked.
2. **Commit**: A commit is a 'snapshot' of your project at a given moment. Each commit has a unique identifier (called a hash) that allows you to reference that specific commit later.
3. **Branch**: A branch is an independent line of development. You can use branches to work on different features or experiments without affecting the main branch (usually called 'master' or 'main').

GitHub is a code hosting platform that utilizes Git for version control. It allows developers to collaborate on projects efficiently. With GitHub, you can clone repositories to your local computer, make changes, and then 'push' those changes back to the repository on GitHub.

Here are some GitHub features:

1. **Pull Requests**: A Pull Request (PR) is a way to suggest changes. Other contributors can review your changes, provide feedback, and eventually 'merge' your changes into the main branch.
2. **Issues**: Issues are a way to track tasks, enhancements, and bugs for your project.
3. **Actions**: GitHub Actions allow you to automate software development tasks, such as testing and deployments.

#

#### Use common Git commands

Git commands are essential for effective project management. Here are some of the most common commands you will use when working with Git:

1. **`git init`**: This command is used to initialize a new local Git repository. It creates a new subdirectory called `.git` that contains all the necessary files for the repository.

2. **`git add`**: The `git add` command is used to add files to the Git index. For example, `git add .` will add all modified files to the index.

3. **`git commit`**: The `git commit` command is used to save your changes to the local repository. For example, `git commit -m "Your message here"` will commit with the specified message.

4. **`git push`**: The `git push` command is used to send your changes to a remote repository. For example, `git push origin master` will send your changes to the master branch of the remote repository named origin.

5. **`git pull`**: The `git pull` command is used to fetch the latest changes from a remote repository and merge them into your local branch.

6. **`git clone`**: The `git clone` command is used to copy a remote repository to your local computer.

7. **`git status`**: The `git status` command is used to see the current status of your repository. It will show which files have been modified and which files are ready to be committed.

8. **`git branch`**: The `git branch` command is used to list, create, or delete branches. For example, `git branch new-feature` will create a new branch named new-feature.

9. **`git checkout`**: The `git checkout` command is used to switch between different branches or commits. For example, `git checkout new-feature` will switch to the new-feature branch.

10. **`git merge`**: The `git merge` command is used to merge the changes from one branch into another. For example, if you are on the master branch and run `git merge new-feature`, the changes from the new-feature branch will be merged into the master branch.

#

#### Collaborate using Git and GitHub

Git and GitHub offer various tools and features that make collaboration on software development projects easier. Here are some ways you can collaborate using Git and GitHub:

1. **Clone repositories**: The `git clone` command allows you to copy a remote repository to your local computer. This allows you to work on the project in your own development environment.

2. **Create and merge branches**: Git allows you to create branches to work on different features or bug fixes. Once work on a branch is complete, you can merge it back into the main branch using the `git merge` command.

3. **Resolve merge conflicts**: When multiple people are working on the same project, merge conflicts are common. Git provides tools to help resolve these conflicts efficiently.

4. **Pull Requests**: On GitHub, you can use Pull Requests to propose changes to a repository. Other collaborators can review your changes, provide feedback, and eventually merge your changes into the project.

5. **Issues**: GitHub Issues are a great way to track tasks, enhancements, and bugs. You can assign issues to yourself or other collaborators, and others can comment on issues to provide feedback or suggestions.

6. **GitHub Actions**: GitHub Actions allow you to automate software development tasks, such as testing and deployments. This can help ensure code quality and the efficiency of the development workflow.

#

#### Write code with GitHub Copilot

GitHub Copilot is a generative AI that suggests lines of code or entire code blocks as you type. Here's an example of how GitHub Copilot can help write a function in Python to calculate the factorial of a number:

```python
def factorial(n):
    """Calculate the factorial of a number."""
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
```

#

<div align="center">
    Hey, you made it to the bottom!
    Take a cookie 🍪
</div>

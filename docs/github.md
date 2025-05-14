# Github ☁️

![VS Code](./images/github-workflow.png)

## Git
[Git](https://git-scm.com/) is a version control system that allows you to track changes in your code. Originally developed to support development of the Linux kernel by thousands of engineers around the world, it has become the dominant version control system on for all kinds of software development projects. On KLC, git is pre-installed at `/usr/bin/git`. 

```bash
# Check if git is installed
git --version
```


The VS Code source control extension with git support is installed by default:

![VS Code Source Control](./images/vscode-source-control.png)

This extension provides a user-friendly interface for managing your git repositories. You can use it to stage changes, commit code, and push to remote repositories.

## Github
Github is a web-based platform that uses git for version control. It allows you to host your code repositories, collaborate with others, and manage your projects. 

Using git does not require GitHub, but Github is an extremely popular platform for hosting git repositories. You can use Github to store your code, track issues, and collaborate with others. You can create a free account on Github and start hosting your code repositories. Microsoft owns GitHub and is also the primary sponsor of the open-source VS Code tool. As a consequence there is an excellent integration between VS Code and Github, making it easy to manage your code repositories from within the editor.

## Setting up Github in VS Code

1. Create a Github account if you don't have one already.

![GitHub Account](./images/github-web.png)

2. Login to your Github account in VS Code.

![GitHub Login](./images/vscode-github-login.png)

3. Open the VS Code extension

![GitHub Extension](./images/vscode-github-extension.png)


```{admonition} Exercise
:class: dropdown
Let's create our own git repository on KLC and with a remote backup on Github.

- Open VS Code on KLC using the remote extension.
- Open a terminal and create a new folder for your project, call it `test-project`.
    ```bash
    mkdir test-project
    ```
- Open the new folder in VS Code.

- Paste files from your local machine into the folder.
- Click on the Source Control icon in the left sidebar.
- Click on the Initialize Repository button.
- Commit the changes.
- Click on the Publish to GitHub button.
- View the repository on Github.
```
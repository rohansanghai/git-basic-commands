# Most basic Git commands with example
List of 300 VueJS Interview Questions

> Click :star:if you like the project. Pull Requests are highly appreciated.

### Table of Contents
-------------------------------------------------------------------
| No. | Questions |
|---- | ---------
|1  | [Git: Configuration](#git-configuration) |
|2  | [Git: starting as a repository](#git-starting-as-a-repository) |
|3  | [Git: staging files](#git-staging-files)|
|4  | [Git: committing to a repository](#git-committing-to-a-repository)|
|5  | [Git: pulling and pushing from and to repositories](#git-pulling-and-pushing-from-and-to-repositories)|
|6  | [Git: branching](#git-branching)|

1.  ### Git: Configuration
    Before you start using a git. Git wants you to do registration with git

    To tell Git who you are, run the following two commands:
    
    ```javascript
        $ git config --global user.name "mentionedYourGitUsername"
        $ git config --global user.email "mentionGitRegisterEmailId"
    ```

    We are able to see the outputs from many git commands in the terminal. We can have colorful out for the commands what we are running in terminal.

    To turn on code highlighting, just run the following command:

    ```javascript
        $ git config --global color.ui true
    ```

    The last basic configuration command will let you view your Git configurations. Running this command is the same as asking for a copy of your contract:

    ```javascript
        $ git config --list
        user.name=GitUserName
        user.email=GitRegisterdEmailId
    ```
    **[⬆ Back to Top](#table-of-contents)**

2.  ### Git: starting as a repository
    ```javascript
        $ git init
    ```

    The "init" command stands for initialize. Once you run "git init", Git will initialize a hidden directory called ".git" in the project's root directory.

    To know the Git status, you'll need to run:
    ```javascript
        $ git status
    ```
    **[⬆ Back to Top](#table-of-contents)**

3.  ### Git: staging files

    ```javascript
        $ git add <file-name>
    ```

    ```javascript
        $ git add <file-name> <another-file-name> <yet-another-file-name>
    ```

    ```javascript
        $ git add .
    ```

    ```javascript
        $ git add --all
    ```

    ```javascript
        $ git add -A
    ```

    ```javascript
        $ git add --cached <file-name>
    ```

    ```javascript
        $ git reset <file-name>
    ```
    **[⬆ Back to Top](#table-of-contents)**

4.  ### Git: committing to a repository
    ```javascript
        $ git commit -m "Add Files"
    ```

    ```javascript
        $ git reset --soft HEAD^
    ```

    ```javascript
        $ git commit --amend -m <enter your message>
    ```
    **[⬆ Back to Top](#table-of-contents)**

5.  ### Git: pulling and pushing from and to repositories
    ```javascript
        $ git remote add origin <link>
    ```

    ```javascript
        $ git push -u origin master
    ```

    ```javascript
        $ git add <file-name>
    ```

    ```javascript
        $ git clone <clone URL>
    ```

    ```javascript
        $ git pull
    ```
    **[⬆ Back to Top](#table-of-contents)**

6.  ### Git: branching
    ```javascript
        $ git branch
    ```

    ```javascript
        $ git branch <branch-name>
    ```

    ```javascript
        $ git checkout <branch-name>
    ```

    ```javascript
        $ git merge <branch-name>
    ```

    ```javascript
        $ git checkout -b <branch-name>
    ```
    **[⬆ Back to Top](#table-of-contents)**

7.  ### Git:
    $ git diff <file-name>

    $ git checkout <file-name> undo changes made in file

    $ git stash - remove all changes

    $ git clean -fx - remove untracked files

    $ git log - 

    $ git log --all -- Display All Commits

    $ git log -3 -- View most recent commits

    Filter Commits By Author or Committer
    $ git log --author <name>
    $ git log --committer <name>

    View All Diff of Changes for Each Commit
    $ git log -p

    View Summary of Changes for Each Commit
    $ git log --stat

    Help
    $ git help
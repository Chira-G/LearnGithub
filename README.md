# LearnGithub

How to check your Git configuration:
returns a list of information about your git configuration including user name and email:
```bash
git config -l
```

How to setup your Git username:
To configure your user name:
```bash
git config --global user.name "myname"
```

How to setup your Git user email:
This command lets you setup the user email address you'll use in your commits.
```bash
git config --global user.email "myname@mymail.com"
```

How to cache your login credentials in Git:
You can store login credentials in the cache so you don't have to type them in each time. Just use this command:
```bash
git config --global credential.helper cache
```

How to initialize a Git repo:
The first step is to initialize a new Git repo locally in your project root. You can do so with the command below:
```bash
git init
```

How to add a file to the staging area in Git:
The command below will add a file to the staging area. Just replace filename_here with the name of the file you want to add to the staging area.
```bash
git add filename_here
```

How to add all files in the staging area in Git
If you want to add all files in your project to the staging area, you can use a wildcard . and every file will be added for you.
```bash
git add .
```

How to add only certain files to the staging area in Git
With the asterisk in the command below, you can add all files starting with 'fil' in the staging area.
```bash
git add filename*
```

How to check a repository's status in Git:
This command will show the status of the current repository including staged, unstaged, and untracked files.
```bash
git status
```

How to commit changes in the editor in Git:
This command will open a text editor in the terminal where you can write a full commit message.
(A commit message is made up of a short summary of changes, an empty line, and a full description of the changes after it.)
```bash
git commit
```

How to commit changes with a message in Git:
You can add a commit message without opening the editor. This command lets you only specify a short summary for your commit message.
```bash
git commit -m "your commit message here"
```

How to commit changes (and skip the staging area) in Git:
You can add and commit tracked files with a single command by using the -a and -m options.
```bash
git commit -a -m"your commit message here"
```

How to see your commit history in Git:
This command shows the commit history for the current repository:
```bash
git log
```

How to see your commit history including changes in Git:
This command shows the commit's history including all files and their changes:
```bash
git log -p
```

How to see a specific commit in Git:
This command shows a specific commit.
Replace commit-id with the id of the commit that you find in the commit log after the word commit.
```bash
git show commit-id
```

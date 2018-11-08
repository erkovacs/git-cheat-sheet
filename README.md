# Basic Git cheat sheet

This tutorial will basically let you version control using a single master branch, which is fine for personal projects or any sort of simple software.
To start, you only really need to know this to push:
```bash
git add . ( To add all your changes )

git commit -m "your message" ( To commit those changes locally )

git push -u origin master ( To push your commits to your git server - eg. Github )
```

And this to pull commits from your server:
```bash
git pull origin master
```

To set your remote url to your git url:
```bash
git remote add origin your-github-url.git 
```
or
```bash
git remote set-url origin change-your-origin-to-another-url.git
```

To initialise a git repo locally:
```bash
git init
```

To clone a repo:
```bash
git clone your-git-repo.git your-local-directory
```
To set up your credentials:
```bash
git config user.name "your username"
git config user.password "your password"
```
You can set these globally by adding the ```--global``` flag to the ```git config``` command.

# Credits
@Ryan Soury at [Quora](https://www.quora.com/As-a-Git-beginner-should-I-use-command-line-or-a-GUI-based-client)

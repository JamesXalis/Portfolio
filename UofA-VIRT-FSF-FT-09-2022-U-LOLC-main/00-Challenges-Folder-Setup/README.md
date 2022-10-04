# How to use this folder

Each folder represents one of the units in class.

* Oddly numbered folders will include both a README.md file explaining the challenge, as well as the starter code to work from.

* Evenly numbered folders will only include the README.md file explaining the challenge.

##### If you've already started some of these assignments

Feel free to replace the content of any of these folders with work you've already completed.

You can simply copy the contents of one file and use them to replace the contents of another using your file explorer program.

##### If you'd like to start working on a project from one of these folders

You should add git tracking to whichever folder you're working from. Follow these steps:

Start by changing directory in your terminal into whichever folder you want to work from.
```bash
cd <path-to-homework-folder>/Homework/<assignment-folder>
```

Initialize this folder as a Git tracked project
```bash
git init
```


Create a repository on GitHub which will serve as the remote for this project.
Copy the link from the Clone option in GitHub.

Associate your local folder to your new remote repository via the terminal
```bash
git remote add origin <paste>
```


Verify your connection
```bash
git remote -v
```


You should see some output similar to this:
```bash
origin  git@github.com:<repo-name>.git (fetch)
origin  git@github.com:<repo-name>.git (push)
```


Add your initial files to the repository
```bash
git add -A
git commit -m "Initial commit"
git push origin main
```

Do your work as normal from here

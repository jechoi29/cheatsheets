# git

### basic

`git init`: starts a git project in your current directory
`git add .`: add all your changges to git
`git commit -m "message"`: commit your changes
`git remote add origin https://..`: link your project to a repo on github
`git push origin master`: push to github
`git status`: check which files have changed

note: the `.gitignore` file lets you add "ignored" files and directories. ALWAYS add "node_modules" to `.gitignore`

### merging

`git checkout -b branch-name`: make a new branch-name
`git merge branch-name`: merge your current branch with branch-name

### cloning

`git clone https://...`: clone someone else's repo
`git remote set-url origin https://...`: to change the remote URL to your own github repo

### pulling

`git pull origin branch-name`: pull from github

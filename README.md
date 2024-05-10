**In this repository, you can find how to download and use git**

> ## Steps involved in git and github
> 1. Download git using [download git](https://git-scm.com/download/win)
> 2. Install git bash
> 3. Configure git bash using your information
> 4. Download [VS Code](https://code.visualstudio.com/) and check if it shows the presence of git or not
> 5. Make a new folder in your local computer and open it in VS Code
> 6. Clone your repository to VS Code
> 7. Make changes and perform add, commit and push to your github

## Git Configuration
Configure user information for all local repositories <br>
`$ git config --global user.name "[name]"`

Sets the name you want attached to your commit transactions <br>
`$ git config --global user.email "[email address]"`

<<<<<<< HEAD
### Check git status
Git status will displays you the status of current repository <br>
=======
### Check git status 
Git status will displays you the status of current repository.
>>>>>>> 59109b0 (changes)
`git status`

### Clone git with github
You can clone you github with VS Code by the  help of link address under "HTTPS" and paste it to terminal of in-build VS CODE <br>
`git clone [link address]`

### Add file to repository
`git add [file name]`

### Commit to GitHub
`git commit -m "your message about this change"`

### Push changes to GitHub
`git push origin main`

[!Note] 
Before you add your file to your repository, it will show status as **_modified_** in red color but will show **_modified_** in green after you add it to repository as check your status.
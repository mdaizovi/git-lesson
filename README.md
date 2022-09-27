# git-lesson
Simple repo for teaching git basics
NOTE: anything in <> is a placeholder. for example 
`<directory>` means there will be the name or a directory (or folder) there but I don't know which one.

 <p align="center">
  <img src="img/memorize.jpg"
     alt="When all else fails.."
     style="width: 33%;" />
 </p>


## Topics

 - What is git? Why use it?
 
 - How to ...
 
   - Make basic commands in the terminal (`ls`, `cd <directory>`, `cd..`, `mkdir <directory>`)
   
   - Check if git is already installed on your sytem
    `git --version`
    
     - [install if necessary](https://www.linode.com/docs/guides/how-to-install-git-on-linux-mac-and-windows/)
   
   - Clone a repo
    `git clone <repo url>`
        - [Caching your GitHub credentials in Git if necessary](https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git)
        - [Creating a personal access token if necessary](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
        - [Generate SSH key if necessary](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
   
   
   - Pull from a repo
    `git pull`
   
   - See what branch you're on
     `git branch`
      
   - Make a feature branch
     `git checkout -b <branch name>`
   
   - Change branches
     `git checkout <branch name>`

   - Add a file to staging area
     `git add <filename>`
     
   - Commit your changes on your branch
     `git commit -am<commit message>`
   
   - Push to the repo
        `git push origin`
        
   - Make a merge request
      (We will do this online at github.com)

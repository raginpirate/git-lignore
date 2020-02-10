## Why:
Sometimes your personal enviroment is different than other contributors in a project and you need to ignore generated assets. One may think to simply use the .gitignore file for this, but when a project scales to more than a handful of users, this would be a TON of fluff (and perhaps detrimental fluff!) for your .gitignore. This tool instead locally and personally ignores those files, without pushing that ignore on your team.
## Usage: 
Git lignore "filename"
## Installation:
Clone repo, chmod +x git-lignore, cp git-lignore /usr/local/bin, restart bash/zsh.
## How it works: 
Creates a symbol link to your .git/info/exclude file in your repo that ignores both itself and any files you wish to add to it. Add more files with further git lignore or just vi .local_gitignore.

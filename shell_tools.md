The purpose of this document is serve as a repository of the Unix shell commands and key bindings that either are the most useful or that I use the most.

## tmux
### Sessions
Start new session named *name*  
`tmux new -s name`  

Attach latest session  
`tmux a`  

Attach to session named *name*  
`tmux a -t name`  

Detach from session  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>d</kbd>  

List all sessions  
`tmux ls`  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>s</kbd>  

Rename current session  
`tmux rename-session newname`  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>$</kbd>  

Kill session named *name*  
`tmux kill-ses -t name`  
Kill all sessions except the current  
`tmux kill-ses -a`

### Windows

Create new window  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>c</kbd>  

Rename current window  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>,</kbd>  

Next window  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>n</kbd>  

Previous window  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>p</kbd>  

Select window by number  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>0</kbd>...<kbd>9</kbd>  

Close window  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>&</kbd>  

### Panes

Split pane vertically  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>%</kbd>  

Split pane horizontally  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>"</kbd>  

Toggle last active pane  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>;</kbd>  

Switch pane to the direction  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>&#8592;</kbd>  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>&#8593;</kbd>  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>&#8594;</kbd>  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>&#8595;</kbd>  

Convert pane into a new window  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>!</kbd>  

Close current pane  
<kbd>Ctrl</kbd>+<kbd>b</kbd>,<kbd>x</kbd>  

## git
### Basics
Initialize the current directory as git repository  
`git init`

Stage changes of a file or directory  
`git add <directory>`  

Commit changes with message  
`git commit -m <commit message>`  

List files staged, unstaged and untracked  
`git status`  

Display entire commit history in a nice way  
`git log --all --graph --decorate`  

### Branches
List all branches in current repo
`git branch`  

Create new branch named *branch_name* and checkout on it  
`git checkout -b <branch_name>`  


### Undoing stuff

### Remote repositories

## docker
## weechat
Switch between weechat core buffer and server buffer  
<kbd>Ctrl</kbd>+<kbd>x</kbd>  

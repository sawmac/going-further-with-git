Going Further With Git
=======================

##Configuration
```git config --global --list``` Display global configuration settings. Or just open the ```~/.gitconfig``` file

```git config --local --list``` Display local configuration settings. Or just open the ```.git/config``` file

```git config --global core.autocrlf input``` Strip carriage returns on saving file to repo.

```git config --global core.autocrlf true``` (Windows) Add carriage returns in when you check out files to the working directory.

```git config --global push.default simple``` Default in 2.0 (only push working branch).

```git config --global pull.rebase true``` Same as ```git pull --rebase``` Avoids additional commit for the merge.

###Aliases
```git config --global alias.s "status -s"``` Let's you type ```git s``` and get shorthand for git status

```git config --global alias.lg "log --oneline --decorate --all --graph"``` Let's you view log on single line with color and graph.



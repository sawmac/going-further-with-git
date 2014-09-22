Git Further
=======================

##Configuration
```git config --global --list``` Display global configuration settings. Or just open the ```~/.gitconfig``` file

```git config --local --list``` Display local configuration settings. Or just open the ```.git/config``` file

```git config --global core.autocrlf input``` Strip carriage returns on saving file to repo.

```git config --global core.autocrlf true``` (Windows) Add carriage returns in when you check out files to the working directory.

```git config --global push.default simple``` Default in 2.0 (only push working branch).

```git config --global pull.rebase true``` Same as ```git pull --rebase``` Avoids additional commit for the merge.

###Aliases
```

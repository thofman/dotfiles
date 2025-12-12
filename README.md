# Tim's dot files

This way my dot files are not only stored locally and someone else could use my dot files

## First things first

Clone this repository on your local machine to use the dot files.

### src/bash/.bash_aliases_git

Open (or add) the `~/.bash_aliases` file and add:

```
if [ -f /path/to/thofman/dotfiles/src/bash/.bash_aliases_git ]; then
    source /path/to/thofman/dotfiles/src/bash/.bash_aliases_git
fi

if [ -f /path/to/thofman/dotfiles/src/bash/.bash_aliases_git_ps1 ]; then
    source /path/to/thofman/dotfiles/src/bash/.bash_aliases_git_ps1
fi

if [ -f /path/to/thofman/dotfiles/src/bash/.bash_aliases_ubuntu; then
    source /path/to/thofman/dotfiles/src/bash/.bash_aliases_ubuntu
fi
```

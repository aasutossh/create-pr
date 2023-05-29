# create-pr

## Pre-requisites
* Install github-cli https://cli.github.com/
* (Optional, if you have multiple github accounts) https://github.com/gabe565/gh-profile

## Usage
Edit the file to update the variables `target_branch` and `branch_labels`.
Make sure the branch name and it's label's indexes are consistent.
You can add an alias for the `script` file and run it from anywhere.
Or you can soft link the file to the directory in path. For e.g. I have `export PATH="$HOME/.scripts:$PATH"`
in my config.
1. Clone the repo
```
cd ~
git clone git@github.com:aasutossh/create-pr.git
cd create-pr
```
2. Make s soft link
`ln -s script ~/.scripts/cpr`

OR in your `.bashrc` or `.zshrc` or any shellrc file make an alias
`alias cpr="$HOME/create-pr/script"`

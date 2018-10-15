# Git Aliases

## Speed up your git commands with aliases.

### [Git Basics - Git Aliases](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases)

#

#### Useful aliases:

Show current aliases
- `git config --get-regexp alias`

Concise git status, prefaced by date
- `git config --global alias.ss '!echo && date && git status -s && echo'`
- Use:&nbsp; `git ss`

Git add & commit
- `git config --global alias.ac !git add -A && git commit`
- Use:&nbsp; `git ac` &nbsp;*or*&nbsp; `git ac -m '...'`

Git add & commit w/ message
- `git config --global alias.acm !git add -A && git commit -m`
- Use:&nbsp; `git acm '...'`

Git pull & run npm script
- `git config --global alias.pr !echo && echo -Pull: && git pull && echo && echo -Run: && npm run`
- Use:&nbsp; `git pr SCRIPT_NAME`

Git status
- `git config --global alias.st !git add -A && git commit`
- Use:&nbsp; `git st`

Git branch
- `git config --global alias.br branch`
- Use:&nbsp; `git br`

Git checkout
- `git config --global alias.co checkout`
- Use:&nbsp; `git co BRANCH_NAME`

Push /build to gh-pages
- `git config --global alias.gh 'subtree push --prefix build origin gh-pages'`
- Use:&nbsp; `git co BRANCH_NAME`
- Replace *build* with project's build folder


#### Coming soon.


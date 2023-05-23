# learn-git

* Learn to use the `git` command line, because IDEs and "smart tools" just hide details
* Install `git-completion` and `git-prompt`: https://github.com/git/git/tree/master/contrib/completion . In some cases, you may need to ensure the version you grab is in sync with your `git` client version.
* Set up this `git lg` alias and use `git lg` over `git log`. 
```
[alias]
    lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
```
* Play this game as far as you can https://learngitbranching.js.org/
* Use `git` for a while
* Now read https://git-scm.com/book/en/v2 and stuff will make a lot more sense.

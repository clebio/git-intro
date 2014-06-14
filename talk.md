#Introduction to Git

A presentation on using [Git](http://git-scm.com/) for version control of source code and other files, covering beginner- to intermediate-level material.


#Outline

1. init, add, commit
2. log, status, diff
3. branch (for topics/tasks), checkout, reset (stash)
4. remote (and SSH keys), clone
5. pull, push, merge
6. [Pull Requests](https://help.github.com/articles/using-pull-requests)


#Starting out
![states and commands](git_init.png)


##Commands
```bash
init
add
commit
```


##States

- untracked
- staged
- commited


#Working Solo
![seeing history](git_single_user.png)


##Commands
```bash
status
log
checkout
reset (--hard)
```


#Branching and topics
![tasks and topics](git_branch.png)


##Commands
```bash
branch
checkout -b
merge
```


#Collaborating
![remotes and origin](git_remote.png)


##Commands
```bash
remote
  add
  remove
branch -a
fetch
push
pull
```


##Side-topic: SSH
```bash
ssh-keygen
ssh -T git@<server>
```


# Style

- Commit early and often
  - `git init` before anything else
  - Make a readme, `git add` it, and `git commit` 
  - see also [RDD](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)
- Make commit messages meaningful
  - use imperative verb forms
  - Use a consitent style (present or past tense, verb-subject, etc.)
- `Add` the minimal amount necessary
  - add specific files
  - Separate intents across commits
- Use multiple commits back-to-back for unrelated changes
- Use branches liberally -- for anything more than minor edits


# References

- [Version control best-practices](https://blog.rainforestqa.com/2014-05-28-version-control-best-practices/)
- [Git book](http://git-scm.com/book)
- [Git for windows](http://msysgit.github.io/)
[Git for Visual Studio](http://visualstudiogallery.msdn.microsoft.com/abafc7d6-dcaa-40f4-8a5e-d6724bdb980c)


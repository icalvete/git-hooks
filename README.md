#git-hooks

Git-hooks

##Actions

### pre-commit

* Check puppet style
* Check puppet syntax
* Check erb syntax

### commit-msg

* Check for string IssueID #[0-9]+ 

##Installation

```bash
ubuntu@yoda:~$ git clone https://github.com/icalvete/git-hooks.git
ubuntu@yoda:~$ cd git-hooks
ubuntu@yoda:~$ chmod 755 *
ubuntu@yoda:~$ cp -a * &lt;git_repo&gt;/.git/hooks
```

##Authors:

Israel Calvete Talavera <icalvete@gmail.com>

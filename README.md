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

1. https://github.com/icalvete/git-hooks.git
2. cd git-hooks
3. chmod 755 *
4. cp -a * &lt;git_repo&gt;/.git/hooks

##Authors:

Israel Calvete Talavera <icalvete@gmail.com>

#GR

Better `git remote`

Usage: `gr [OPTION] PARAMETER`

Examples:

	$ cat ~/.config/git-providers
	https://czipperz@github.com/
	bb:https://czipperz@bitbucket.org/
	$ gr ao czipperz/gr  # Same as `git remote add origin https://czipperz@github.com/czipperz/gr`
	$ gr a origin bb:czipperz/gr  # Same as `git remote add origin https://czipperz@bitbucket.org/czipperz/gr`

Options:

* a - add
* r - remove
* ao - add origin
* ro - remove origin
* sh - set-head
* sb - set-branches
* su - set-url
* sua - set-url --add
* sud - set-url --delete
* p - prune
* u - update
* anything else - directly passed through

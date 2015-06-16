#GR

Better `git remote`

Usage: `gr [OPTION] PARAMETER`

Examples:

	$ cat ~/.config/gr
	https://czipperz@github.com/
	c:https://czipperz@github.com/czipperz
	$ gr ao czipperz/gr  # Same as `git remote add origin https://czipperz@github.com/czipperz/gr`
	$ gr a origin c:gr  # Same as `git remote add origin https://czipperz@github.com/czipperz/gr`

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

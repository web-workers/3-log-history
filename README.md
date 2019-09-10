# Git Log and History
[Git - git-log Documentation](https://git-scm.com/docs/git-log)

Git log is a really useful tool in the Git toolbelt. It gives you the ability to see the history of this repo at this point.  Within `git log` you will be able to see all the commits and their messages that you have locally in your repository.

## Git Log
### The Command
The command is super simple:

```
git log [<options>] [<revision range>] [<path>]
```

#### Arguments
* Options:
  * There is a list at [Git - git-log Documentation](https://git-scm.com/docs/git-log#_options)
* Revision Range:
  * Here you can define two commit hashes to see the log between them
  * or two named commits `HEAD` `origin`

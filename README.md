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

## Git History
`git log` reveals the history but it’s the history itself that’s super important.  History is the culmination or group of commits from the initialization to now.  History is fixed, right? Wrong!

History for a series of commits is fluid.  This is honestly one of the most powerful things about `git` to me.  Because it’s fluid in a sense you can create a single source of truth without errors or blemishes in your history.

In the beginning you’ll make a lot of commits that look something like:
```
Fixed merge conflicts
```
```
Trying to figure out how this works
```

And that’s OK.  

But wouldn’t this:
```
 - Corrected weird bug in jest
 - Finally figured out what was up
 - Testing weird fix
 - Added a feature 
 ...
 - Initial commit
```

Look better when you pushed it up to your boss for code review like this:
```
 - Added my feature because people like selfies
   - Applied workaround for jest bug
 ...
 - Initial Commit
```


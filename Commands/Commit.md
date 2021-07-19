# git commit

The command `git commit` will take all tracked changes (items added with [git add](./Add.md)) and package them up in what is called commit.

Commits come with commit messages that are required for each commit. You add a message to a comnmit command by using `-m` flag followed by a message in quotes. 

A commit message _can_ be anything, but best practise dictates that you should use that message to indicate the changes inclued in the commit.

For example, if we have an application we are working on where we just build out the ability to resgister a new accounts, then you might have some variation of the followin:

```
git add .

git commit -m "Added new feature"
```

Then when viewing the history of a git respositpry, you can pinpoint where the registration funcionality was added.

## Resources

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)
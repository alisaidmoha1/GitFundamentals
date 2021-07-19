# git remote

When working with git, a **remote** is any git repository that is not on the machine you are working on. The counterpart to this is **local**, or the machine that is being developed on.

Take GitHub for exampe. While git is the technology that allows you to create locla repositories, GitHub ins the site that will host you remote respotories.

**Note**: While the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

## Adding a remote

A remote can be added with the `git remote add` command, followed by the name and locastion of the remote.

The name is a local name, meaning it is your label and does not impact the actual remote whatsoever.

```
git remote add orgin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```

### Removing a remote

A remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## Resources 

- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

---

[Back to home](../README.md)
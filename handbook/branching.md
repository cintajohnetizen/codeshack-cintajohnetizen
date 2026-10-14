# Git Branching

What Is a Branch?

A branch is an independent line of development in a Git repository. It allows developers to work on changes without immediately modifying the main branch.

Why Use Branches?

- Develop new features separately.
- Test changes before merging.
- Keep the main branch stable.
- Allow multiple developers to work in parallel.

Create a Feature Branch

```bash
git switch -c feature/new-documentation
```

This creates a branch and switches to it.

Check the Current Branch

```bash
git branch --show-current
```

Save Changes on the Branch

```bash
git add handbook/branching.md
git commit -m "Add branching guide"
```

Push the Branch to GitHub

```bash
git push -u origin feature/new-documentation
```

Merge a Branch

Switch to the branch that should receive the changes, then merge:

```bash
git switch main
git merge feature/new-documentation
```

In collaborative projects, changes should normally be reviewed through a pull request before merging.

Conclusion

Branches make development more organised and reduce the risk of unreviewed changes affecting the main project.
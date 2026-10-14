# Git Branching

What Is a Branch?

A branch is an independent line of development in a Git repository. It allows developers to work on changes without immediately modifying the main branch.

Why Use Branches?

- They help us to develop new features separately.
- They test changes before merging.
- Can keep the main branch stable.
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


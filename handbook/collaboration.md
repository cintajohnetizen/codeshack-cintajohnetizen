# Git Collaboration

## Why Collaboration Matters

Software projects often involve multiple developers working on the same codebase. Git and GitHub help them share changes and maintain project history.

## Clone a Repository

```bash
git clone https://github.com/TEAM/PROJECT.git
```

## Fetch Remote Changes

```bash
git fetch origin
```

This downloads remote updates without integrating them into the current branch.

## Update a Local Branch

```bash
git pull origin main
```

This fetches and integrates changes from the remote main branch into the current branch.

## Work on a Separate Branch

```bash
git switch -c feature/my-contribution
```

Each team member should use their own branch for their contribution.

## Push Your Work

```bash
git add .
git commit -m "Add my contribution"
git push -u origin feature/my-contribution
```

## Pull Requests

A pull request allows other team members to review proposed changes before they are merged into the main branch.

## Merge Conflicts

A merge conflict occurs when Git cannot automatically reconcile overlapping changes. Developers must inspect the conflicting sections, decide how to combine them, and then complete the merge.

## Good Collaboration Practices

- Use descriptive commit messages.
- Work on separate branches.
- Fetch updates regularly.
- Review changes before merging.
- Avoid direct commits to the shared main branch when team rules prohibit them.

## Conclusion

Good Git practices make team projects easier to maintain, review, and develop collaboratively.
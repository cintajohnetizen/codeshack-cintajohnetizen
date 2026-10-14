# Git Notes: Git Commands

## 1. git init

Initialises a new Git repository.

```bash
git init
```

## 2. git clone

Downloads a local copy of a remote repository.

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

## 3. git status

Shows the current branch and the status of files.

```bash
git status
```

## 4. git add

Stages changes for the next commit.

```bash
git add README.md
```

To stage all changes:

```bash
git add .
```

## 5. git commit

Records staged changes in the local repository.

```bash
git commit -m "Add project introduction"
```

## 6. git log

Displays commit history.

```bash
git log --oneline
```

## 7. git diff

Shows unstaged changes.

```bash
git diff
```

To see staged changes:

```bash
git diff --staged
```

## 8. git push

Uploads local commits to a remote repository.

```bash
git push origin main
```

To push a feature branch for the first time:

```bash
git push -u origin feature/handbook
```

## 9. git pull

Fetches remote updates and integrates them into the current branch.

```bash
git pull origin main
```

## 10. git fetch

Downloads remote updates without integrating them into the current branch.

```bash
git fetch origin
```

## 11. git branch

Lists local branches.

```bash
git branch
```

To create a branch:

```bash
git branch feature/documentation
```

## 12. git switch

Switches to another branch.

```bash
git switch main
```

To create and switch to a branch:

```bash
git switch -c feature/documentation
```

## 13. git merge

Integrates another branch into the current branch.

```bash
git merge feature/documentation
```

## 14. git remote -v

Shows configured remote repository URLs.

```bash
git remote -v
```

## 15. git restore

Discards unstaged changes to a tracked file.

```bash
git restore README.md
```

**Warning:** This command can permanently discard uncommitted changes to the specified file.

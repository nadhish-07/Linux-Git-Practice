# Git Day 1 Commands

## Initialize a Git repository

```bash
git init
```

---

## Check repository status

```bash
git status
```

---

## Add a single file to staging

```bash
git add newfile.txt
```

---

## Add all files

```bash
git add .
```

---

## Commit staged changes

```bash
git commit -m "Initial Commit"
```

---

## Commit tracked files without separate staging

```bash
git commit -am "Updated existing files"
```

Note:

This command works only for already tracked files.

---

## View commit history

```bash
git log
```

---

## View compact commit history

```bash
git log --oneline
```

---

## View unstaged changes

```bash
git diff
```

---

## View staged changes

```bash
git diff --cached
```

---

## Remove file from staging

```bash
git restore --staged file.txt
```

---

## Stop tracking a file

```bash
git rm --cached file.txt
```

---

## Git File States

Untracked

↓

Tracked

↓

Modified

↓

Staged

↓

Committed
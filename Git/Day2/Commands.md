# Git Day 2 Commands

## Show all branches

```bash
git branch
```

---

## Create a new branch

```bash
git branch feature-login
```

---

## Switch branch

```bash
git checkout feature-login
```

---

## Create and switch branch

```bash
git checkout -b feature-login
```

---

## Merge a branch

```bash
git merge feature-login
```

---

## Delete merged branch

```bash
git branch -d feature-login
```

---

## Add GitHub remote

```bash
git remote add origin https://github.com/username/repository.git
```

---

## View configured remotes

```bash
git remote -v
```

---

## Push changes

```bash
git push
```

---

## Push for the first time

```bash
git push -u origin main
```

---

## Pull latest changes

```bash
git pull origin main
```

---

## Clone a repository

```bash
git clone https://github.com/username/repository.git
```

---

## Rename branch to main

```bash
git branch -M main
```
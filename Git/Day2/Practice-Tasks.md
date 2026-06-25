# Git Day 2 Practice Tasks

## Task 1

Create a new Git repository.

### Solution

```bash
git init
```

---

## Task 2

Create a feature branch.

### Solution

```bash
git branch feature-login
```

---

## Task 3

Switch to the feature branch.

### Solution

```bash
git checkout feature-login
```

---

## Task 4

Create a file named app.txt and add content.

### Solution

```bash
echo "Login Page Added" > app.txt
```

---

## Task 5

Stage and commit the changes.

### Solution

```bash
git add app.txt
git commit -m "Added login feature"
```

---

## Task 6

Switch back to the main branch.

### Solution

```bash
git checkout main
```

---

## Task 7

Merge the feature branch.

### Solution

```bash
git merge feature-login
```

---

## Task 8

Delete the feature branch.

### Solution

```bash
git branch -d feature-login
```

---

# Merge Conflict Practice

## Task 9

Create a branch named feature-login.

Modify:

```text
app.txt
```

Content:

```text
Login Page Added
```

Commit the changes.

---

## Task 10

Switch to the main branch.

Modify the same file.

Content:

```text
Dashboard Page Added
```

Commit the changes.

---

## Task 11

Merge the feature branch.

```bash
git merge feature-login
```

Expected:

```text
CONFLICT (content): Merge conflict in app.txt
Automatic merge failed.
```

---

## Task 12

View the conflict.

```bash
cat app.txt
```

Expected:

```text
<<<<<<< HEAD
Dashboard Page Added
=======
Login Page Added
>>>>>>> feature-login
```

---

## Task 13

Resolve the conflict manually.

Final content:

```text
Dashboard Page Added
Login Page Added
```

---

## Task 14

Complete the merge.

```bash
git add app.txt

git commit -m "Resolved merge conflict"
```

---

## Task 15

View commit history.

```bash
git log
```

---

# GitHub Practice

## Task 16

Connect the local repository to GitHub.

```bash
git remote add origin https://github.com/username/repository.git
```

---

## Task 17

Verify the remote.

```bash
git remote -v
```

Expected:

```text
origin https://github.com/username/repository.git (fetch)

origin https://github.com/username/repository.git (push)
```

---

## Task 18

Push the repository to GitHub.

```bash
git push -u origin main
```

---

## Task 19

Pull the latest changes.

```bash
git pull origin main
```

---

## Task 20

Clone a GitHub repository.

```bash
git clone https://github.com/username/repository.git
```

---

# Mini Project

## Project Name

Feature Development Workflow

### Objective

Practice a complete Git workflow using feature branches.

### Steps

1. Create a repository.
2. Create a feature branch.
3. Develop a feature.
4. Commit the feature.
5. Switch back to the main branch.
6. Merge the feature.
7. Resolve merge conflicts if any.
8. Push the updated repository to GitHub.

---

## Workflow

```text
Create Repository
        │
        ▼
Create Branch
        │
        ▼
Develop Feature
        │
        ▼
Commit Changes
        │
        ▼
Switch to Main
        │
        ▼
Merge Branch
        │
        ▼
Resolve Conflicts
        │
        ▼
Push to GitHub
```

---

## Learning Outcome

After completing Day 2, I learned how to:

- Work with Git branches.
- Merge branches safely.
- Resolve merge conflicts manually.
- Connect a local repository with GitHub.
- Push and pull changes.
- Understand collaborative development using Git.
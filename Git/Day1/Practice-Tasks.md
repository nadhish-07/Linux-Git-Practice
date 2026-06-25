# Git Day 1 Practice Tasks

## Task 1

Initialize a Git repository.

### Solution

```bash
git init
```

---

## Task 2

Create a file named newfile.txt.

### Solution

```bash
touch newfile.txt
```

---

## Task 3

Add the following content.

```
Hello World
```

### Solution

```bash
echo "Hello World" > newfile.txt
```

---

## Task 4

Check repository status.

### Solution

```bash
git status
```

Expected

```text
Untracked files:
newfile.txt
```

---

## Task 5

Stage the file.

### Solution

```bash
git add newfile.txt
```

---

## Task 6

Verify staging.

### Solution

```bash
git status
```

Expected

```text
Changes to be committed:
new file: newfile.txt
```

---

## Task 7

Create the first commit.

### Solution

```bash
git commit -m "Initial Commit"
```

---

## Task 8

Modify the file.

Add

```
How are you?
```

### Solution

```bash
echo "How are you?" >> newfile.txt
```

---

## Task 9

Check modified status.

### Solution

```bash
git status
```

Expected

```text
modified: newfile.txt
```

---

## Task 10

View differences.

### Solution

```bash
git diff
```

---

## Task 11

Stage the modified file.

### Solution

```bash
git add newfile.txt
```

---

## Task 12

View staged differences.

### Solution

```bash
git diff --cached
```

---

## Task 13

Create the second commit.

### Solution

```bash
git commit -m "Second Commit"
```

---

## Task 14

View commit history.

### Solution

```bash
git log
```

---

## Task 15

View compact commit history.

### Solution

```bash
git log --oneline
```

---

## Task 16

Commit without using git add.

Modify the tracked file and run:

```bash
git commit -am "Updated tracked file"
```

Note:

This works only for files that are already tracked.

---

## Task 17

Remove a file from the staging area.

### Solution

```bash
git restore --staged newfile.txt
```

---

## Task 18

Stop tracking a file while keeping it locally.

### Solution

```bash
git rm --cached credential.txt
```

---

# Mini Challenge

## Objective

Practice the complete Git workflow.

### Steps

1. Create a repository.
2. Create a file.
3. Add content.
4. Stage the file.
5. Commit the file.
6. Modify the file.
7. View changes.
8. Stage changes.
9. Commit changes.
10. View commit history.

---

## Workflow

```text
Create File
      │
      ▼
git status
      │
      ▼
git add
      │
      ▼
git commit
      │
      ▼
git log
```

---

## Learning Outcome

After completing Day 1, I learned how to:

- Initialize a Git repository.
- Track files using Git.
- Move files from the working directory to the staging area.
- Create commits.
- View commit history.
- Compare file changes.
- Remove files from staging.
- Stop tracking files while keeping them locally.
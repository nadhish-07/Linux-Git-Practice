# Linux Day 1 Practice Tasks and Answers

## Task 1: Create a directory named `practice`

**Command:**

```bash
mkdir practice
```

---

## Task 2: Move inside the `practice` directory

**Command:**

```bash
cd practice
```

---

## Task 3: Create three files

Create:

```text
a.txt
b.txt
c.txt
```

**Command:**

```bash
touch a.txt b.txt c.txt
```

---

## Task 4: Write "Hello Linux" into `a.txt`

**Command:**

```bash
echo "Hello Linux" > a.txt
```

Verify:

```bash
cat a.txt
```

Expected Output:

```text
Hello Linux
```

---

## Task 5: Copy `a.txt` to `d.txt`

**Command:**

```bash
cp a.txt d.txt
```

---

## Task 6: Rename `b.txt` to `linux.txt`

**Command:**

```bash
mv b.txt linux.txt
```

---

## Task 7: Give full permission to the owner only for `c.txt`

**Command:**

```bash
chmod 700 c.txt
```

Verify:

```bash
ls -l c.txt
```

Expected Output:

```text
-rwx------
```

---

## Task 8: Find all `.txt` files

**Command:**

```bash
find . -name "*.txt"
```

---

## Task 9: Check the current user

**Command:**

```bash
whoami
```

---

## Task 10: Check disk usage

**Command:**

```bash
df -h
```

---

# Mini Practice Project - College Directory Structure

## Objective

Create the following directory structure:

```text
college
├── students
│   ├── student1.txt
│   └── student2.txt
└── teachers
    ├── teacher1.txt
    └── teacher2.txt
```

### Commands

```bash
mkdir college

cd college

mkdir students teachers

touch students/student1.txt students/student2.txt

touch teachers/teacher1.txt teachers/teacher2.txt
```

### Display the structure

On Windows (Git Bash):

```bash
cmd /c tree /F
```

On Linux:

```bash
tree
```

---

## Learning Outcome

After completing Day 1, I learned how to:

* Navigate between directories.
* Create and manage files and folders.
* Copy, rename, and delete files.
* View directory structures.
* Check the current user.
* Understand basic file permissions.
* Practice Linux file management commands.

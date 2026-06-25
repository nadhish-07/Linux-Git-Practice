# Linux Day 3 Practice Tasks

## Task 1

Create a directory named admin.

### Solution

```bash
mkdir admin
```

---

## Task 2

Move inside the directory.

### Solution

```bash
cd admin
```

---

## Task 3

Create three files.

```
user1.txt
user2.txt
user3.txt
```

### Solution

```bash
touch user1.txt user2.txt user3.txt
```

---

## Task 4

Give permission 700 to user1.txt.

### Solution

```bash
chmod 700 user1.txt
```

Verify

```bash
ls -l user1.txt
```

Expected Output

```text
-rwx------
```

---

## Task 5

Give permission 755 to user2.txt.

### Solution

```bash
chmod 755 user2.txt
```

Verify

```bash
ls -l user2.txt
```

Expected Output

```text
-rwxr-xr-x
```

---

## Task 6

Give permission 644 to user3.txt.

### Solution

```bash
chmod 644 user3.txt
```

Verify

```bash
ls -l user3.txt
```

Expected Output

```text
-rw-r--r--
```

---

## Task 7

Check the current logged-in user.

### Solution

```bash
whoami
```

---

## Task 8

Display user and group information.

### Solution

```bash
id
```

---

## Task 9

Display running processes.

### Solution

```bash
ps
```

---

## Task 10

Display all running processes with details.

### Solution

```bash
ps -ef
```

---

## Task 11

Open the interactive process monitor.

### Solution

```bash
top
```

Press

```text
q
```

to quit.

---

# Mini Challenge

## Objective

Create the following structure.

```text
secure_data
├── confidential.txt
├── reports.txt
└── public.txt
```

### Commands

```bash
mkdir secure_data

cd secure_data

touch confidential.txt reports.txt public.txt
```

---

## Apply Permissions

### confidential.txt

```bash
chmod 600 confidential.txt
```

---

### reports.txt

```bash
chmod 640 reports.txt
```

---

### public.txt

```bash
chmod 644 public.txt
```

---

## Verify

```bash
ls -l
```

Expected Output

```text
-rw------- confidential.txt
-rw-r----- reports.txt
-rw-r--r-- public.txt
```

---

# Questions Practiced

### What does 755 mean?

Owner → Read, Write, Execute

Group → Read, Execute

Others → Read, Execute

---

### What does 700 mean?

Owner → Read, Write, Execute

Group → No Permission

Others → No Permission

---

### What does 644 mean?

Owner → Read, Write

Group → Read

Others → Read

---

## Learning Outcome

After completing Day 3, I learned how to:

- Understand Linux permission values.
- Apply permissions using chmod.
- Read file permission symbols.
- Check current user information.
- View running processes.
- Monitor Linux system processes.

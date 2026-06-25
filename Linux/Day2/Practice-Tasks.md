# Linux Day 2 Practice Tasks

## Task 1

Create a file named linux.txt.

### Solution

```bash
touch linux.txt
```

---

## Task 2

Write the following contents:

```
Linux
AWS
DevOps
Docker
Kubernetes
```

### Solution

```bash
echo "Linux" > linux.txt
echo "AWS" >> linux.txt
echo "DevOps" >> linux.txt
echo "Docker" >> linux.txt
echo "Kubernetes" >> linux.txt
```

---

## Task 3

Display the file contents.

### Solution

```bash
cat linux.txt
```

---

## Task 4

Search for the word Docker.

### Solution

```bash
grep "Docker" linux.txt
```

---

## Task 5

Count the number of lines.

### Solution

```bash
wc -l linux.txt
```

---

## Task 6

Count the number of words.

### Solution

```bash
wc -w linux.txt
```

---

## Task 7

Create a file called app.log.

### Solution

```bash
touch app.log
```

---

## Task 8

Insert the following logs:

```
INFO Application Started
ERROR Database Failed
INFO User Login
ERROR API Timeout
```

### Solution

```bash
echo "INFO Application Started" > app.log
echo "ERROR Database Failed" >> app.log
echo "INFO User Login" >> app.log
echo "ERROR API Timeout" >> app.log
```

---

## Task 9

Display only ERROR logs.

### Solution

```bash
grep "ERROR" app.log
```

---

## Task 10

Store all files in a text file.

### Solution

```bash
ls > files.txt
```

---

## Mini Challenge

### Objective

Create the following project.

```
project
│
├── logs
│   ├── app.log
│   └── server.log
│
└── reports
    └── report.txt
```

Add log contents.

Search only ERROR messages.

Display the directory structure.

### Commands Used

```bash
mkdir project
cd project

mkdir logs reports

touch logs/app.log
touch logs/server.log
touch reports/report.txt

grep "ERROR" logs/app.log

grep "ERROR" logs/server.log

cmd /c tree /F
```

---

## Learning Outcome

After completing Day 2, I learned how to:

- Create and modify file contents.
- Search data using grep.
- Count lines and words.
- Redirect command output.
- Append data into files.
- Perform basic Linux log analysis.

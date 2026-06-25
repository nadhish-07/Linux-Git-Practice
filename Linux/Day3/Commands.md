# Linux Day 3 Commands

## Display detailed file permissions

```bash
ls -l
```

---

## Change file permission

```bash
chmod 700 file.txt
```

---

## Give permission 755

```bash
chmod 755 file.txt
```

---

## Give permission 644

```bash
chmod 644 file.txt
```

---

## Give full permission

```bash
chmod 777 file.txt
```

---

## Check current user

```bash
whoami
```

---

## Display user information

```bash
id
```

---

## Show running processes

```bash
ps
```

---

## Show detailed processes

```bash
ps -ef
```

---

## Interactive process viewer

```bash
top
```

Exit from top:

```text
q
```

---

## Permission Table

| Number | Binary Permission | Meaning |
|---------|-------------------|---------|
| 7 | rwx | Read + Write + Execute |
| 6 | rw- | Read + Write |
| 5 | r-x | Read + Execute |
| 4 | r-- | Read Only |
| 0 | --- | No Permission |

# Linux Day 2 Commands

## Display file content

```bash
cat filename.txt
```

---

## Create file with content

```bash
echo "Linux" > linux.txt
```

---

## Append content

```bash
echo "AWS" >> linux.txt
```

---

## View file

```bash
cat linux.txt
```

---

## Search text

```bash
grep "Linux" linux.txt
```

---

## Search ERROR logs

```bash
grep "ERROR" app.log
```

---

## Count number of lines

```bash
wc -l linux.txt
```

---

## Count words

```bash
wc -w linux.txt
```

---

## Count characters

```bash
wc -c linux.txt
```

---

## Redirect output

```bash
ls > files.txt
```

---

## Append output

```bash
ls >> files.txt
```

---

## Use Pipe

```bash
cat app.log | grep "ERROR"
```

---

## Display first few lines

```bash
head app.log
```

---

## Display last few lines

```bash
tail app.log
```
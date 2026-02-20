# 📘 README — Number Triangle Pattern Program (Python)

## 📌 Description
This Python program prints a **number triangle pattern** where each row displays numbers starting from **1 up to the row number**.

---

## ⚙️ Code

```python
rows = 5

for i in range(1, rows + 1):
    for j in range(1, i + 1):
        print(j, end="")
    print()
```

---

## 🧠 Step-by-Step Explanation

### 1️⃣ Define Number of Rows

```python
rows = 5
```

This means the pattern will have **5 rows**.

---

### 2️⃣ Outer Loop (Controls Rows)

```python
for i in range(1, rows + 1):
```

* Starts from **1**
* Runs until **5**
* Each loop represents a new row.

---

### 3️⃣ Inner Loop (Print Numbers)

```python
for j in range(1, i + 1):
```

* Prints numbers from **1 to i**
* So each row prints more numbers than the previous row.

---

### 4️⃣ Print Numbers in Same Line

```python
print(j, end="")
```

* Keeps numbers on the same line.

---

### 5️⃣ Move to Next Line

```python
print()
```

Moves to a new row after printing numbers.

---

## ▶️ Output

```
1
12
123
1234
12345
```

---

## 🔑 Concepts Used

* Nested loops
* Pattern printing logic
* Range function
* `end=""` in print

---

## 🎯 Logic Trick (Very Easy)

👉 Row number = how many numbers to print
👉 Always print from **1 to row number**

---

## 🚀 Why This Program is Important

This type of pattern helps beginners:

* Understand nested loops clearly
* Build logic for interviews
* Practice coding fundamentals

---

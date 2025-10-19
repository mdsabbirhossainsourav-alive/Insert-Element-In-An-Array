# 🧮 Insert Element in an Array (C Program)

## 📘 Description

This C program inserts a new element into a specific position (index) of an array.
It shifts the existing elements to the right to make space for the new value.

---

## 🧠 How It Works

1. Read the number of elements `n`.
2. Input `n` integers into the array.
3. Read `idx` (the index) and `val` (the new value).
4. Shift elements from the end toward `idx` by one position.
5. Insert `val` at the given index.
6. Print the updated array (size becomes `n + 1`).

## ⚙️ Algorithm Steps

1. Read integer `n`
2. Create array `a[n+1]`
3. Input `n` array elements
4. Read `idx` and `val`
5. For `i = n` down to `idx + 1`, shift `a[i] = a[i-1]`
6. Set `a[idx] = val`
7. Print updated array

---

## 💻 Sample Run

**Input:**

```
5
10 20 30 40 50
1 100
```

**Output:**

```
10 100 20 30 40 50
```



# 2ECEA Programming Assignment 1

This repository contains solutions to programming exercises implemented in Python using Jupyter Notebook. The problems focus on basic string manipulation and logical operations.

## Contents

* **Alphabet Soup Problem**
  A program that sorts the letters of a given string alphabetically and prints the result.

* **Emoticon Problem**
  A program that detects specific words in an input string (`smile`, `grin`, `sad`, `mad`) and replaces them with corresponding emoticons.

* **Unpacking List Problem**
  A program that detaches the first and last indexes of an array and displays it separately as **First**, **Middle**, and **Last**.

## File

* `2ECEA_PA1_Batallones.ipynb` — Jupyter Notebook containing the solutions.

## Example Usage

### Alphabet Soup

**Code:**

```python
alphabet_soup = "discombobulate"          # input string
print("".join(sorted(alphabet_soup)))     # sort letters and rejoin into a string
```

The input word is sorted alphabetically using `sorted()`, and `"".join()` combines the letters back into one string.

**Output:**

```
aabbcdeilmoostuu
```

---

### Emoticon

**Code (Input):**

```python
text = "I feel sad today"   # input string with a keyword
# program replaces 'sad' → ':(' and other words like
# 'smile' → ':)', 'grin' → ':D', 'mad' → '>:('
```

The program scans for specific words and swaps them with matching emoticons. In this case, `sad` is replaced with `:(`.

**Output:**

```
I feel :( today
```

---

### Unpacking List

**Code:**

```python
writeyourcodehere = [1,2,3,4,5,6]    # input list
first = writeyourcodehere[0]         # first element
last = writeyourcodehere[-1]         # last element
middle = writeyourcodehere[1:-1]     # all elements in between
print("first:", first, "\tmiddle:", middle, "\tlast:", last)
```

The list is split into three parts: the first value, the middle section, and the last value, then displayed neatly in a single line.

**Output:**

```
first:  1 	middle:  [2, 3, 4, 5] 	last:  6
```

---

## Author / Student Info

* **Name:** Yvan Reyan M. Batallones
* **Course:** 2ECEA
* **Activity:** Programming Assignment 1

---

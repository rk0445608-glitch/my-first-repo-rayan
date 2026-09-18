# Problem.md — Lab 03 Pseudocode

**Name:** Rayan khan  
**Roll No:** 26K-0578  
**Section:** 1B  

---

## Problem 1 — Display Student Information Using Different Data Types

### Pseudocode

```text
START

DECLARE name AS string
DECLARE rollNumber AS integer
DECLARE age AS integer
DECLARE height AS float
DECLARE gpa AS float
DECLARE section AS character

INPUT name
INPUT rollNumber
INPUT age
INPUT height
INPUT gpa
INPUT section

DISPLAY "STUDENT INFORMATION"
DISPLAY "Name: ", name
DISPLAY "Roll No: ", rollNumber
DISPLAY "Age: ", age
DISPLAY "Height: ", height
DISPLAY "GPA: ", gpa
DISPLAY "Section: ", section

END
```

---

## Problem 2 — Read and Display a Character Using `getchar()` and `putchar()`

### Pseudocode

```text
START

DECLARE ch AS character

DISPLAY "Enter a character: "
READ ch USING getchar()

DISPLAY "You entered: "
DISPLAY ch USING putchar()

END
```

---

## Problem 3 — Display a Floating-Point Value Using Different Precision Settings

### Pseudocode

```text
START

DECLARE value AS float

DISPLAY "Enter a floating-point value: "
INPUT value

DISPLAY "Default precision: ", value
DISPLAY "2 decimal places: ", value WITH 2 DIGITS AFTER DECIMAL
DISPLAY "4 decimal places: ", value WITH 4 DIGITS AFTER DECIMAL
DISPLAY "6 decimal places: ", value WITH 6 DIGITS AFTER DECIMAL

END
```

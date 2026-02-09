# Jest Workshop Submission

## Student Details
- Name: Tisha Kharade
- Roll Number: 2024-B-16082005A
- GitHub Username: ace-tk

---

## Tests Written

List each test you wrote and briefly explain **what bug or regression it prevents**.

### 1. Test Name:
**What it protects against:**  

---Ensures that when no coupon is provided the function returns the correct subtotal (after applying the automatic 5% discount for amounts ≥ 1000) and does not apply any extra discount accidentally

### 2. Test Name:
**What it protects against:**  

---Prevents incorrect discount calculation for the SAVE10 coupon ensures the 10% discount is capped at 100 and also verifies that the coupon is applied after the initial 5% discount

### 3. Test Name:
**What it protects against:**  
---Ensures that FLAT50 does not produce negative totals and correctly handles edge cases like very small subtotals

### 4. Test Name:
**What it protects against:**  

---Prevents invalid inputs such as negative numbers, strings, or NaN from being processed, ensuring proper error handling

### 5. Test Name:
**What it protects against:**  

---Ensures the function behaves correctly even if the user enters coupon codes in lowercase or mixed case

## CI Pipeline (if implemented)
- Did CI pass successfully? (Yes / No)    YES
- GitHub Actions Run URL:   https://github.com/ace-tk/jest-workshop/actions/runs/21825442660

---

## Reflection (1–2 lines)
What is **one thing** you understood better about testing or CI after this workshop?

I understood how unit tests help catch edge cases early and how CI ensures tests are automatically run on every push preventing broken code from being merged

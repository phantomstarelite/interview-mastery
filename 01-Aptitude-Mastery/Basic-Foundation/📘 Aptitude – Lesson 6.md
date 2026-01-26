
# 📘 Aptitude – Lesson 6

## Remainders (Modulus) – Absolute Beginner → Interview Level

> Remainder questions test **logic**, not calculation.

---

## 🧠 Part 1: What is a Remainder?

![Image](https://www.mathsisfun.com/numbers/images/remainder-7-2-pups.svg)

![Image](https://www.splashlearn.com/math-vocabulary/wp-content/uploads/2023/04/What-is-Remainder-2.png)

![Image](https://www.dreambox.com/wp-content/uploads/2024/10/how-to-do-long-division-12-min.jpg)

When a number is divided and **doesn’t divide completely**, what’s left is the **remainder**.

Example:

* 17 ÷ 5 = 3 remainder **2**
* 23 ÷ 4 = 5 remainder **3**

---

## 🧮 Part 2: Modulus Operator (%)

[
a \bmod b = \text{remainder when } a \text{ is divided by } b
]

Examples:

* 17 % 5 = **2**
* 23 % 4 = **3**
* 12 % 4 = **0**

📌 Remainder is **always less than the divisor**

---

## ⚡ Part 3: Basic Remainder Rules (VERY IMPORTANT)

### 🔹 Rule 1:

If **a < b**, then
[
a \bmod b = a
]

Example:

* 5 % 7 = **5**

---

### 🔹 Rule 2:

If **a is divisible by b**, remainder = **0**

Example:

* 24 % 6 = **0**

---

### 🔹 Rule 3:

[
(a + b) \bmod n = [(a \bmod n) + (b \bmod n)] \bmod n
]

Example:

* (14 + 19) % 6
  → (2 + 1) % 6 = **3**

---

### 🔹 Rule 4:

[
(a × b) \bmod n = [(a \bmod n) × (b \bmod n)] \bmod n
]

Example:

* (13 × 17) % 5
  → (3 × 2) % 5 = **1**

---

## 🔁 Part 4: Remainder Cycles (EXAM FAVORITE)

![Image](https://cdn.educba.com/academy/wp-content/uploads/2020/03/Handling-Cyclic-Patterns.jpg)

![Image](https://www.exploringbinary.com/wp-content/uploads/PosPO5Cycles.jpg)

![Image](https://ecdn.teacherspayteachers.com/thumbitem/Imaginary-Numbers-i-CHART-2141234-1484644341/original-2141234-3.jpg)

### Example: Powers of 2 divided by 3

| Power | Value | Remainder |
| ----- | ----- | --------- |
| 2¹    | 2     | 2         |
| 2²    | 4     | 1         |
| 2³    | 8     | 2         |
| 2⁴    | 16    | 1         |

🔁 Cycle: **2, 1**

---

### Interview Example:

👉 Find remainder when **2¹⁰⁰** is divided by **3**

* Cycle length = 2
* 100 mod 2 = 0
* Remainder = **1**

---

## 🧠 Part 5: Very Common Interview Question

👉 What is the remainder when **7²⁰** is divided by **6**?

7 mod 6 = 1
[
1^{20} \bmod 6 = 1
]

✔ **Answer = 1**

---

## 🧪 Practice (Do Slowly)

### Q1️⃣ Find remainder when **45** is divided by **7**

---

### Q2️⃣ Find remainder when **2³⁰** is divided by **3**

---

### Q3️⃣ Find remainder when **(17 × 19)** is divided by **5**

---

### Q4️⃣ Interview Question

👉 What is the remainder when **999⁹⁹** is divided by **9**?


✅ Quick Verification (Solutions)

Q1: 45 ÷ 7 → remainder 3 ✅

Q2: 2³⁰ ÷ 3 → cycle (2,1) → remainder 1 ✅

Q3: (17×19) % 5 → (2×4)%5 = 3 ✅

Q4: 999⁹⁹ % 9 → digit sum multiple of 9 → 0 ✅
# 📘 Aptitude – Lesson 6

## Remainders (Modulus) – Absolute Beginner → Interview Level

> Remainder questions test **logic**, not calculation.

---

## 🧠 Part 1: What is a Remainder?

![Remainder Illustration](https://www.mathsisfun.com/numbers/images/remainder-7-2-pups.svg)    

![Remainder Example](https://www.splashlearn.com/math-vocabulary/wp-content/uploads/2023/04/What-is-Remainder-2.png)    

![Long Division](https://www.dreambox.com/wp-content/uploads/2024/10/how-to-do-long-division-12-min.jpg    )

When a number is divided and **does not divide completely**, the leftover part is called the **remainder**.

**Examples:**
- 17 ÷ 5 = 3 remainder **2**
- 23 ÷ 4 = 5 remainder **3**

---

## 🧮 Part 2: Modulus Operator (%)

The modulus operator gives the **remainder** after division.

a % b = remainder when a is divided by b


**Examples:**
- 17 % 5 = **2**
- 23 % 4 = **3**
- 12 % 4 = **0**

📌 The remainder is **always less than the divisor**.

---

## ⚡ Part 3: Basic Remainder Rules (VERY IMPORTANT)

### 🔹 Rule 1
If **a < b**, then:



**Examples:**
- 17 % 5 = **2**
- 23 % 4 = **3**
- 12 % 4 = **0**

📌 The remainder is **always less than the divisor**.

---

## ⚡ Part 3: Basic Remainder Rules (VERY IMPORTANT)

### 🔹 Rule 1
If **a < b**, then:

a % b = a


**Example:**
- 5 % 7 = **5**

---

### 🔹 Rule 2
If **a is divisible by b**, then:

a % b = 0


**Example:**
- 24 % 6 = **0**

---

### 🔹 Rule 3

(a + b) % n = [(a % n) + (b % n)] % n


**Example:**
- (14 + 19) % 6  
  → (2 + 1) % 6 = **3**

---

### 🔹 Rule 4

(a × b) % n = [(a % n) × (b % n)] % n


**Example:**
- (13 × 17) % 5  
  → (3 × 2) % 5 = **1**

---

## 🔁 Part 4: Remainder Cycles (EXAM FAVORITE)

![Remainder Cycles](https://cdn.educba.com/academy/wp-content/uploads/2020/03/Handling-Cyclic-Patterns.jpg)
![Power Cycles](https://www.exploringbinary.com/wp-content/uploads/PosPO5Cycles.jpg)

### Example: Powers of 2 divided by 3

| Power | Value | Remainder |
|------|-------|-----------|
| 2¹   | 2     | 2         |
| 2²   | 4     | 1         |
| 2³   | 8     | 2         |
| 2⁴   | 16    | 1         |

🔁 Cycle: **2, 1**

---

### Interview Example
👉 Find the remainder when **2¹⁰⁰** is divided by **3**

- Cycle length = 2  
- 100 % 2 = 0  
- Remainder = **1**

---

## 🧠 Part 5: Very Common Interview Question

👉 Find the remainder when **7²⁰** is divided by **6**


**Example:**
- (13 × 17) % 5  
  → (3 × 2) % 5 = **1**

---

## 🔁 Part 4: Remainder Cycles (EXAM FAVORITE)

![Remainder Cycles](https://cdn.educba.com/academy/wp-content/uploads/2020/03/Handling-Cyclic-Patterns.jpg)     

![Power Cycles](https://www.exploringbinary.com/wp-content/uploads/PosPO5Cycles.jpg)    

### Example: Powers of 2 divided by 3

| Power | Value | Remainder |
|------|-------|-----------|
| 2¹   | 2     | 2         |
| 2²   | 4     | 1         |
| 2³   | 8     | 2         |
| 2⁴   | 16    | 1         |

🔁 Cycle: **2, 1**

---

### Interview Example
👉 Find the remainder when **2¹⁰⁰** is divided by **3**

- Cycle length = 2  
- 100 % 2 = 0  
- Remainder = **1**

---

## 🧠 Part 5: Very Common Interview Question

👉 Find the remainder when **7²⁰** is divided by **6**

7 % 6 = 1  
1²⁰ % 6 = 1


✔ **Answer = 1**

---

## 🧪 Practice (Do Slowly)

### Q1️⃣  
Find the remainder when **45** is divided by **7**

---

### Q2️⃣  
Find the remainder when **2³⁰** is divided by **3**

---

### Q3️⃣  
Find the remainder when **(17 × 19)** is divided by **5**

---

### Q4️⃣ Interview Question  
👉 What is the remainder when **999⁹⁹** is divided by **9**?

---

## ✅ Quick Verification (Solutions)

- Q1: 45 ÷ 7 → remainder **3** ✅  
- Q2: 2³⁰ ÷ 3 → cycle (2, 1) → remainder **1** ✅  
- Q3: (17 × 19) % 5 → (2 × 4) % 5 = **3** ✅  
- Q4: 999⁹⁹ % 9 → digit sum multiple of 9 → **0** ✅  

---

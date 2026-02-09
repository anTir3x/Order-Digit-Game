# 🎯 Order Digit Game

A fun and competitive **two‑player number guessing game** inspired by logic, deduction, and classic code‑breaking mechanics.

---

## 🚀 Game Overview

**Order Digit Game** is a turn‑based guessing game where players try to crack a **hidden 4‑digit number** chosen by their opponent.

Each guess is evaluated with precise feedback to help players narrow down the solution.

> 🏆 **Goal:** Be the first to correctly guess all 4 digits **in the correct order**.

---

## 🧠 Game Concept

* Two players (or Player vs Computer)
* Each player selects a **hidden 4‑digit number**
* Numbers must follow these rules:

  * ❌ Cannot start with `0`
  * ❌ No repeated digits
* Players take turns guessing the opponent’s number

---

## 🎮 Game Modes

### 🧍 Single‑Player

* Player vs Computer
* Computer generates a valid random 4‑digit number

### 👥 Multiplayer

* Two human players
* Each player chooses a hidden number
* Turns alternate automatically

---

## 📏 Gameplay Rules

* All guesses must be **4 digits**
* Guesses **may start with `0`**
* Digits **must not repeat**

### 🔍 Guess Evaluation

Each guess returns two values:

* **Orders** → Digits that are correct **and** in the correct position
* **Digits** → Digits that are correct but in the **wrong position**

📌 **Example:**

```
Hidden Number: 4271
Guess:         4172
Orders: 1
Digits: 2
```

---

## 🏁 Winning Condition

* A player wins by scoring **4 Orders**
* This means all digits are guessed **correctly and in order**

Upon winning:

* 🎉 Display a victory alert
* 🔓 Optionally reveal the hidden number

---

## 🛠️ Features to Implement

### 🔘 Mode Selection

* Single‑player
* Multiplayer

### ✅ Input Validation

* Exactly **4 digits**
* **No repeated digits**
* Hidden numbers **cannot start with `0`**

### 🧮 Evaluation Logic

* Calculate **Orders** and **Digits** accurately

### 🔄 Turn Management

* Alternate turns in multiplayer mode
* Disable input for the inactive player

### 📊 Guess History

* Display guesses in a **table format**

| Player | Guess | Orders | Digits |
| ------ | ----- | ------ | ------ |
| P1     | 1234  | 1      | 2      |
| P2     | 5678  | 0      | 1      |

### 🤖 Computer Logic (Single‑Player)

* Generate a valid random number
* Optional: smarter guessing logic (future enhancement)

---

## 💡 Future Enhancements (Optional)

* Difficulty levels for AI
* Timer‑based turns
* Hint system
* Online multiplayer support
* Mobile‑friendly UI

---

## 📌 Tech‑Stack Agnostic

This game can be implemented using:

* JavaScript / TypeScript
* Python
* Java
* C++
* Web, CLI, or Mobile platforms

---

## 📄 License

Open‑source. Free to modify, learn from, and improve.

---

🔥 *Crack the code. Outsmart your opponent. Claim victory.*

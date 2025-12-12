# 🏰 Fortress // Password Entropy Auditor

> **A scientific password strength analyzer that calculates Shannon Entropy and estimated GPU crack time in real-time.**

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Security](https://img.shields.io/badge/Security-Information%20Theory-red)
![GUI](https://img.shields.io/badge/UI-CustomTkinter-green)

## 📖 Overview

**Fortress** is not your standard "password checker." Most checkers just look for arbitrary rules (e.g., "Must have 1 number"). Fortress uses **Information Theory** to calculate the mathematical **Entropy (bits)** of your password string.

It features a reactive, modern GUI that updates as you type, providing immediate feedback on how long it would take a modern GPU cracking rig (capable of 100 Billion guesses/second) to brute-force your password.


*(Add a screenshot of your tool here)*

---

## ✨ Key Features

* **🧮 Real-Time Entropy Engine:** Calculates `Bits = Length * log2(Pool_Size)` instantly on every keystroke.
* **⏱️ Crack Time Estimation:** contextualizes the math by estimating time-to-crack against a powerful GPU cluster ($10^{11}$ guesses/sec).
* **🎨 Reactive Dashboard:** The interface shifts colors (Red $\to$ Yellow $\to$ Green) dynamically based on bit strength.
* **✅ Live Criteria Checklist:** Visually tracks requirements (Length, Special Chars, Uppercase, etc.).
* **👁️ Privacy Mode:** Toggle password visibility to audit safely.

---

## 🛠️ Prerequisites & Installation

### 1. Requirements
* **Python:** 3.8 or higher.
* **OS:** Windows, macOS, or Linux.

### 2. Install Dependencies
This project relies on `customtkinter` for its modern UI.
```bash
pip install customtkinter

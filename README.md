# 🔍 Network Port Scout – Python Utility

A lightweight and efficient network security tool designed to identify open ports on a target IP address, providing essential insights into active services.

---

## 🚀 Overview

This script automates the process of scanning network ports by attempting connections through socket programming:

### 📡 Scanning Logic
- **IP Targeting:** Allows user input to define the specific host to be analyzed.
- **Port Range:** Configured to iterate through standard or full-range ports (1-65535).

### ⏱️ Performance & Precision
- **Socket Control:** Implements timeout management to prevent the script from hanging on unresponsive ports.
- **Status Reporting:** Provides immediate console feedback, differentiating between open and closed connections.

---

## 💎 Technical Features
- **Library Integration:** Built using Python's native `socket` module for low-level networking.
- **Error Handling:** Optimized to handle connection exceptions and timeout events gracefully.
- **Data Conversion:** Ensures clean output by converting numerical port data into readable string formats.

---

## 📂 Project Structure
- portscanner.py     # Main scanning logic and network connection handling
- README.md          # Project documentation and technical guide

---

## 📋 Requirements
- **Python 3.x**
- Access to a **Terminal** or command-line interface.

---

## 👤 Author
[GitHub – entorpecimiento](https://github.com/entorpecimiento)

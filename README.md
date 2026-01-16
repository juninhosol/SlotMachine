# 🎰 Terminal Slot Machine (Python)

A fully functional, terminal-based Slot Machine game built with Python. This project demonstrates core programming concepts such as matrix manipulation, weighted probability, and real-time state management.

## 🚀 Overview

This simulator allows users to deposit a balance, choose the number of lines to bet on, and test their luck. The game calculates winnings based on symbol values and updates the player's balance dynamically.

## ✨ Features

- **Balance System:** Handle deposits, per-line bets, and total bet calculations.
- **Dynamic Grid Generation:** Generates a 3x3 grid using weighted symbol frequencies.
- **Win Detection:** Automatically checks for horizontal matches across selected lines.
- **Input Validation:** Robust handling of user inputs to prevent crashes and ensure valid game flow.
- **State Persistence:** Keeps track of the player's balance throughout the session.

## 🛠️ Technical Implementation

- **Data Structures:** Used dictionaries to map symbol frequency (`symbol_count`) and payout multipliers (`symbol_value`).
- **Matrix Logic:** Implemented logic to transpose columns into rows for visual display and win checking.
- **Randomization:** Utilized the `random` module to simulate fair slot spins.
- **Clean Code:** Structured with modular functions to ensure readability and maintainability.

## 🎮 How to Run

1. **Prerequisites:** Make sure you have [Python 3](https://www.python.org/) installed.
2. **Clone the repo:**
   ```bash
   git clone [https://github.com/juninhosol/SlotMachine.git](https://github.com/juninhosol/SlotMachine.git)
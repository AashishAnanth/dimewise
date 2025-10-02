# DimeWise

DimeWise is a gamified personal finance simulator designed to help teens and young adults build financial literacy in a safe, simulated environment. Players manage income, expenses, debt, savings, and investments — and face real-world challenges — while watching their net worth grow.

This project is in the works and will be updated as needed!

---

## 🎯 Purpose

- Offer hands-on experience with budgeting, loans, credit, and investing without real risk.  
- Encourage smart decision-making through feedback, achievements, and financial health scoring.  
- Provide a foundation for extending into web, database-backed, or multiplayer versions later.

---

## 🛠 Features (Core)

- Monthly simulation loop (income, expenses, interest, random events)  
- Multiple account types: Checking, Savings, Credit  
- Investment options with randomized returns  
- Random life events (car breakdowns, windfalls, etc.)  
- Achievement system and financial health score  
- Snapshot history (track progress over time)  
- Scenario & difficulty options for replayability  

---

## 🚧 Roadmap & Future Features

- Credit score modeling  
- Inflation adjustment  
- Save/load state (file or database)  
- REST API or web frontend using Spring Boot  
- More complex investment strategies/market models  
- GUI interface (JavaFX, web, or mobile)  
- Multiplayer / shared leaderboards  

---

## 🧩 Architecture Overview

- `model/` — domain classes (Account, Person, Expense, etc.)  
- `engine/` — simulation logic, event manager, game loop  
- `ui/` — console-based user interface  
- `util/` — helper utilities (e.g. formatting money)  

---

## 🎮 How to Run (Console Demo Version)

1. Clone the repo  
2. Navigate to project directory  
3. Compile:  
   ```bash
   javac src/**/*.java

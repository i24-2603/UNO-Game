# 🎮 UNO AI Game — Minimax vs Expectimax

## 📌 Overview
This project implements a simplified version of the UNO card game using **Adversarial Search Algorithms**. It features three players with different strategies and demonstrates how AI decision-making works in uncertain environments.

---

## 👥 Players

- **Player 1 — Minimax (Defensive AI)**
  - Focuses on minimizing opponent advantage
  - Uses worst-case assumptions

- **Player 2 — Expectimax (Offensive AI)**
  - Uses probability to handle uncertainty
  - Focuses on aggressive card shedding

- **Player 3 — User / AI**
  - Manual Mode (user plays)
  - Simulation Mode (AI plays using Minimax)

---

## 🃏 Game Rules (Simplified UNO)

- Match card by:
  - Same **color**
  - OR same **number**
- If no valid move → draw 1 card
- **Skip card** skips the next player’s turn
- Player wins when:
  - Hand size = 0

---

## 🧠 Algorithms Used

### 🔵 Minimax (Defensive Strategy)
- Assumes opponents play optimally against the AI
- Focuses on reducing risk and blocking opponents
- Depth = 3

### 🔴 Expectimax (Offensive Strategy)
- Handles uncertainty using probability
- Models draw actions as **chance nodes**
- Maximizes expected value
- Depth = 3

---

## 📊 Evaluation Function

Score is calculated as:

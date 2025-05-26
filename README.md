# blackjack

# 🃏 Blackjack (21) Terminal Game - Python

This is a simple **Blackjack game** (also known as 21) built with Python and played in the terminal. The game allows the user to compete against the computer in a turn-based card challenge, following basic Blackjack rules.

## 🎮 How to Play

- You and the computer are each dealt two cards.
- Cards have the following values:
  - Numbers (2-10): their face value
  - Face cards (J, Q, K): 10 points
  - Ace (A): 11 points (automatically becomes 1 if total score exceeds 21)
- The goal is to get as close as possible to 21 without going over.
- A score of exactly 21 with two cards (an Ace and a 10/face card) is called **Blackjack** and wins automatically.

## 🧠 Game Rules Implemented

- You can choose to draw another card (`hit`) or pass (`stand`).
- The computer will draw cards until its score is at least 17.
- If either player goes over 21, it's a bust and the other player wins.
- The game handles **Blackjack**, **draws**, **busts**, and **standard wins/losses**.

## 📦 Project Structure

- `deal_card()` → Randomly picks a card from the deck.
- `calculate_score(cards)` → Calculates the score of a given hand. Handles Aces and Blackjack.
- `compare(user_score, computer_score)` → Compares scores and determines the winner.
- `play_game()` → Main game logic.
- The `logo` is imported from `art.py` for a stylish terminal banner.


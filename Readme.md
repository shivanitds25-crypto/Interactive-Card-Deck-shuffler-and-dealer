# 🃏 Interactive Card Deck Shuffler & Dealer

## 📌 Project Description

Interactive Card Deck Shuffler & Dealer is a web-based application that simulates a standard 52-card deck. It provides an easy and interactive way to shuffle cards, deal cards among multiple players, draw additional cards, return cards to the deck, and find the player with the highest card.

The project is developed using HTML, CSS, and JavaScript. HTML creates the structure of the webpage, CSS provides the visual design and responsive layout, and JavaScript controls the card-deck logic and interactive features.

## ✨ Features

- 🃏 Standard 52-card deck
- 🔀 Random card shuffling
- 👥 Support for 2 to 6 players
- 🎴 Select the number of cards per player
- ➕ Draw an additional card
- ↩️ Return cards to the deck
- 🏆 Find the highest card
- 🤝 Detect ties between players
- 🔄 Reset the game
- 📊 Display remaining and dealt cards
- 📜 Activity history
- 📱 Responsive design

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript

## 🎮 How to Use

1. Select the number of players.
2. Select the number of cards each player should receive.
3. Click **Shuffle** to randomly shuffle the deck.
4. Click **Deal Cards** to distribute cards among the players.
5. Click **Draw Card** to give an additional card to Player 1.
6. Click **Find Highest** to identify the player with the highest card.
7. Click **Return Cards** to return player cards to the deck.
8. Click **Reset** to start a fresh game.

## 🏆 Card Ranking

The application uses the following ranking:

**2 < 3 < 4 < 5 < 6 < 7 < 8 < 9 < 10 < J < Q < K < A**

If two or more players have the same highest card, the application displays a tie.

## 📂 Project Structure

```text
interactive-card-deck/
│
├── index.html
└── README.md
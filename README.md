# Python Blackjack Game

A command-line implementation of the classic Blackjack card game built with Python.

## Description

This is a simple terminal-based Blackjack game where players can play against a computer dealer. The game follows standard Blackjack rules, featuring:

- Card dealing
- Score calculation
- Ace handling (11/1 value switch)
- Dealer AI with standard hit-below-17 rule
- Blackjack detection

## Project Structure

```
blackjack/
├── README.md
├── .gitignore
├── requirements.txt
├── src/
│   ├── main.py
│   └── art.py
└── LICENSE
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/python-blackjack.git
cd python-blackjack
```

2. No external dependencies are required as the game uses only Python standard library.

## How to Play

Run the game using Python:

```bash
python src/main.py
```

- Type 'y' to start a new game
- You'll be dealt two cards
- Choose to hit ('y') or stand ('n')
- Try to beat the dealer without going over 21
- Enjoy the game!

## Game Rules

- The goal is to get closer to 21 than the dealer without going over
- Number cards are worth their face value
- Face cards (J, Q, K) are worth 10
- Aces are worth 11 but change to 1 if you would bust
- Dealer must hit on 16 and stand on 17


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

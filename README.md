# 🐾 Meowgic-Mind

Welcome to **Meowgic-Mind**, an interactive, magical number prediction game! 🎩✨

This project takes the user on a mystical journey where the website seemingly reads their mind to guess the final number after a series of secret mathematical operations.

## ✨ Features
- **Magical Mind Reading**: A clever mathematical algorithm that always determines your final number.
- **Mystical Modern UI**: A sleek, neon-accented, magic-themed user interface with smooth animations and transitions.
- **Single Page Experience**: A seamless, connected flow without page reloads.
- **Cat-Themed Easter Egg**: Declining to play leads to a fun, feline surprise! 

## 🎮 How to Play
1. Open up `index.html` in your web browser.
2. Choose to play the game by clicking **YES**.
3. Follow the mystical prompts...
4. Think of a number between 1 and 100 and enter it.
5. Go through the steps mathematically in your head.
6. Be amazed as your mind is read!

## 🧠 The Math Behind the Magic
The game relies on a simple yet effective algebraic trick:
1. Pick a number: $x$
2. Multiply by a factor of 2: $2x$
3. Add a randomly generated number $R$: $2x + R$
4. Divide the total by 2: $(2x + R) / 2 = x + R/2$
5. Subtract your original number $x$: $(x + R/2) - x = R/2$

No matter what number you originally picked, the final answer will always be exactly half of the random number added in step 3!

## 🛠️ Built With
- Pure HTML5
- Responsive CSS3 (Glassmorphism & Neon Effects)
- Vanilla JavaScript (DOM manipulation & Game Logic)


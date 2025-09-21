# 5x5 Bomb Game (Educational / Entertainment)

## Description
This is a **5x5 bomb-flipping game** created for **entertainment and educational purposes** only.  
Players flip up to 5 cards in a 5×5 grid while avoiding bombs. The game uses **virtual tokens** to simulate a staking/reward system.  

> **Important:** You do **not** earn real money or any type of currency. This game is purely for personal use, learning, and fun.  

---

## Features

- **5×5 Grid:** 25 cards, 5 hidden bombs per round  
- **Flip Mechanic:** Flip up to 5 cards per round  
- **Additive Bomb Probability:** Bombs become more likely as the player approaches 200 tokens  
- **Adaptive Win Logic:** Early rounds are easier, later rounds are harder  
- **Token System:** Start with 100 tokens, spend 10 per round  
- **Round Rewards:** Survive flips to earn virtual tokens  
- **Withdraw Simulation:** Withdraw button appears at 200 tokens (simulation only)  
- **Password Renewal:** Reset tokens and rounds using a password  
- **Bomb Reveal:** Bombs remain hidden until hit or end of round  
- **Responsive UI:** Simple dark-themed interface with cards and status display  
- **Disclaimer:** Clear notice that the game is for entertainment/educational use  

---

## How to Play

1. Start with **100 virtual tokens**.  
2. Click **New Round** to start a round (costs 10 tokens).  
3. Flip up to **5 cards**. Avoid bombs 💣.  
4. Survive all 5 flips → gain 50 tokens (virtual).  
5. If you hit a bomb → round lost, bombs reveal automatically.  
6. Accumulate tokens until you reach 200 → **Withdraw button activates** (simulation only).  
7. Use the **Renew** button with the password to reset tokens and rounds.  

---

## Technology Stack

- **HTML** – Game structure and layout  
- **CSS** – Dark theme and card styling  
- **JavaScript** – Game logic, adaptive win algorithm, additive bomb placement, UI updates  

---

## Disclaimer

> **This game is for entertainment and educational purposes only.**  
> You do **not** earn real money or any type of actual currency by playing this game.  
> It is designed solely for personal use and learning purposes.  

---

## How to Run

1. Download or clone the project.  
2. Open the `index.html` file in any modern browser.  
3. Play the game directly — no server or installation required.  

---

## Customization

- **Number of bombs:** Change `NUM_BOMBS` in the JS code  
- **Token rewards:** Adjust `FLIPS_ALLOWED * 10` in `endRound()`  
- **Win probability curve:** Adjust `minProb` and `maxProb` in `generateBombsAdditive()`  
- **Renew password:** Change `RENEW_PASSWORD` in JS  

---

Enjoy the game and use it for **fun and learning**!

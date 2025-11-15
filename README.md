# Flags and Facts Matching Game

This project is a small browser game created as part of an academic assignment that focused on the use of GitHub Copilot.  
The game allows the user to match country flags with fun facts about each country.

The interface is in Hebrew and supports right-to-left layout.

---

## Main Features

- Random selection of countries for each round  
- Flags and facts are shuffled independently  
- Click to select a fact and a flag and check if they match  
- Score counter for correct matches  
- Timer that tracks round duration  
- Multiple rounds with different countries  
- Visual feedback for selected, matched and incorrect items  

---

## Technologies

- HTML5  
- CSS3  
- Vanilla JavaScript (DOM manipulation and game logic)

---

## How to Play

1. Each round displays a set of flags and a set of facts.  
2. Select a fact, then select the flag you think matches it.  
3. Correct matches update the score and mark the items as matched.  
4. Incorrect matches clear the selection and show a message.  
5. After all pairs are matched, you can continue to the next round.  
6. A timer tracks how long each round took.

---

## How to Run

No server is required.

1. Download or clone the project.  
2. Open the `index.html` file in any modern browser.

Optional (VS Code):
- Open the folder in VS Code  
- Use the "Live Server" extension to run the game with auto-refresh  

---

## Project Structure

- `index.html`  
  - Contains the page layout, styles and JavaScript logic (embedded scripts)  
- Inline `<style>`  
  - Handles layout, design, and RTL support  
- Inline `<script>`  
  - Implements the full game logic (rounds, shuffle, score, timer, matching)

---

## Notes

This project was created as part of an academic exercise that required using GitHub Copilot.  
Some parts of the code were generated with Copilot, as instructed in the assignment.

---

## Author

Maya Sofer  
Computer Science Student, Sapir College

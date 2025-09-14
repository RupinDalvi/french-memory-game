### **README: French Memory Game**

### **Project Title**
French Memory Game

### **Description**
This is a single-file HTML5 web application that serves as an interactive memory game for learning common French words and phrases. The game is designed to be visually appealing and offers a dynamic difficulty system that adjusts based on the user's performance. All code, including HTML, CSS, and JavaScript, is contained within a single `index.html` file, making it easy to deploy and share.

### **Features**
* **Two Game Modes:** Choose between a **Words** mode, featuring 50 common French nouns, verbs, adjectives, and prepositions, and a **Phrases** mode, with 50 useful conversational phrases.
* **Memory Gameplay:** Match English words/phrases with their French translations.
* **Dynamic Difficulty:** Select the number of pairs to play with (6, 8, 10, 12, up to 30). The game's difficulty automatically increases, stays the same, or decreases based on the number of mistakes you make.
* **Initial Reveal:** All cards are revealed for 15 seconds at the start of each game, giving you a chance to memorize their positions.
* **Responsive Design:** The game board and interface are designed to look great on both desktop and mobile devices.
* **Polished UI & Animations:** Enjoy smooth CSS transitions for card flips and a clean, modern aesthetic.
* **Audio Feedback:** Subtle sound effects provide satisfying feedback for card flips, correct matches, and game outcomes.

### **How to Play**
1.  Open the `index.html` file in any modern web browser.
2.  On the start screen, select your preferred **game mode** (Words or Phrases).
3.  Choose the number of **pairs** you want to play with.
4.  Click the **"Start Game"** button.
5.  All cards will be visible for 15 seconds. Try to memorize their locations!
6.  Once the cards flip over, click two cards at a time to find a matching English/French pair.
7.  If you make a match, the cards will stay face up. If not, they will flip back over.
8.  **Win Condition:** Find all the matching pairs to win the game.
9.  **Game Over Condition:** The game ends immediately if you make 3 or more mistakes.

### **Technical Details**
The program is a single, self-contained file.
* **HTML:** Provides the structure for the game interface, including the start screen, game board, and status displays.
* **CSS:** Manages all styling, layout, and animations for a polished look and feel.
* **JavaScript:** Handles all core game logic, including:
    * State management (tracking matches, mistakes, etc.).
    * Dynamic card generation and shuffling.
    * Event handling for card clicks.
    * Win/loss condition checking.
    * The dynamic difficulty adjustment system.
    * Audio playback.

### **Credits**
* **Game Logic & Design:** Created by a user request.
* **Sound Effects:** Sample audio files are sourced from SoundHelix for demonstration purposes. These can be easily replaced with custom audio files.

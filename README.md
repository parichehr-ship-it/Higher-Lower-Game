# 📈 Higher or Lower: Social Media Showdown 🎮

A terminal-based Python game where you test your knowledge of social media popularity. Do you know who has more followers: Cristiano Ronaldo or Ariana Grande? 

Built entirely in Python, this game features dynamic data, custom ASCII art, and a clean command-line interface.

## 🚀 Features
- **Dynamic Gameplay:** Randomly selects accounts from a dataset of global celebrities, brands, and organizations.
- **Custom ASCII Art:** Features a custom-designed logo and a stylish "VS" screen for an immersive terminal experience.
- **Cross-Platform:** Automatically detects the operating system to properly clear the console between rounds (works on Windows, macOS, and Linux).
- **Score Tracking:** Keeps track of your current winning streak. One wrong guess, and the game is over!

## 📂 Project Structure
- `Higher_lower_Game.py`: The main script containing the game logic and loops.
- `game_data.py`: A module containing the dictionary list of accounts and their follower counts.
- `Art.py`: A separate module holding the multi-line strings for the ASCII art graphics.

## 🛠️ Tech Stack & Concepts Used
- **Python 3**
- **Modules:** `random` (for unpredictable matchups), `os` (for system operations).
- **Data Structures:** List of Dictionaries (handling complex data).
- **Architecture:** Modular programming (separating data, art, and logic into different files).
- **Functions:** For formatting data and checking answers.

## 🎮 How to Play
1. Clone this repository to your local machine.
2. Navigate to the project folder and run the main file:
   ```bash
   python Higher_lower_Game.py

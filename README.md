# Rock-paper-scissors-AI
🎯 Intelligent Rock Paper Scissors game with adaptive AI - Professional Python GUI with Tkinter
🎯 Rock Paper Scissors - Python GUI Game

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Game](https://img.shields.io/badge/Game-FF6B6B?style=for-the-badge&logo=game&logoColor=white)

**A sophisticated Rock Paper Scissors game with intelligent AI and professional GUI**

</div>

---

## ✨ Features

- **🤖 Adaptive AI**: Computer opponent with smart decision-making
- **🎨 Professional GUI**: Clean, intuitive user interface
- **📊 Real-time Statistics**: Live score tracking and game analytics
- **⚡ Smooth Gameplay**: Instant feedback and responsive controls
- **🔄 Game Management**: Easy restart and score reset functionality

---

## 🚀 Quick Start

### Installation
```bash
git clone https://github.com/Yashaswini1412/rock-paper-scissors-ai.git
cd rock-paper-scissors-ai
Usage
bash
python game/main.py
🎯 How to Play
Launch the game application

Click your choice: Rock, Paper, or Scissors

Computer makes its choice automatically

View instant results and score updates

First to reach 5 points wins the game

🏗️ Game Architecture
python
class RockPaperScissorsGUI:
    def __init__(self):
        self.player_score = 0
        self.computer_score = 0
        
    def play_round(self, player_choice):
        # Core game logic implementation
        computer_choice = self.get_computer_choice()
        result = self.determine_winner(player_choice, computer_choice)
        self.update_scores(result)
🎮 Game Logic
python
# Winning combinations
WINNING_RULES = {
    'rock': 'scissors',     # Rock crushes scissors
    'paper': 'rock',        # Paper covers rock  
    'scissors': 'paper'     # Scissors cut paper
}

def determine_winner(player, computer):
    if player == computer:
        return "tie"
    elif WINNING_RULES[player] == computer:
        return "player"
    else:
        return "computer"
🛠️ Technology Stack
GUI Framework: Tkinter (Python standard library)

Programming Language: Python 3.8+

Architecture: Object-Oriented Design Patterns

Platform: Cross-platform compatibility

🚀 Performance
Load Time: < 2 seconds application startup

Response Time: Instant button feedback

Memory Usage: Efficient resource utilization

Compatibility: Windows, macOS, and Linux support

🎯 Learning Outcomes
GUI Development: Mastered Tkinter framework and event handling

Game Design: Implemented complete game loop and state management

User Experience: Created intuitive and engaging interface

Software Architecture: Applied object-oriented programming principles

🤝 Contributing
Ideas for enhancement:

Add sound effects and animations

Implement online multiplayer mode

Create tournament mode with brackets

Add player statistics and achievements

📄 License
This project is licensed under the MIT License.

<div align="center">
⭐ If you enjoy this game, please give it a star!

Developed by Yashaswini

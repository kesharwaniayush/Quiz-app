# 🧠 Kaun Banega Crorepati (KBC) - Quiz Game

This is a desktop-based quiz game inspired by the famous Indian TV show *Kaun Banega Crorepati (KBC)*. 
The application is built using Python's Tkinter library and features multiple-choice questions, a lifeline,
a quitting option, and a prize money system.

---

## 📂 Project Structure
KBC-Quiz-Game/

    ├── main.py # Core GUI logic using Tkinter
    ├── questions.py # Question bank with options, answers, and prize amounts


---

## 🎮 Features

- ✅ 15-level quiz with increasing difficulty and rewards
- 🧠 Lifeline support to eliminate two wrong options (usable once)
- 💰 Prize money tracking system
- 🚪 Option to quit the game and keep earned money
- 🧾 Final result display with total winnings
- 📌 GUI-based using Tkinter for user-friendly interaction

---

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **GUI Library**: Tkinter (standard Python library)

---

## ▶️ How to Run

1. Ensure Python 3.x is installed. Download from: [python.org](https://www.python.org/downloads/)
2. Clone or download this repository:
   ```bash
   git clone https://github.com/yourusername/KBC-Quiz-Game.git
   cd KBC-Quiz-Game

-----
## 📊 How It Works

The game simulates a multiple-choice quiz experience through the following flow:

- 🟢 **Start of Game**  
  - The first question is displayed along with four answer options.

- 👆 **Answer Selection**  
  - The player selects one option by clicking the corresponding button.
  - If the answer is correct:
    - A success message is shown.
    - The prize money is increased.
    - The next question is loaded.
  - If the answer is incorrect:
    - A "Game Over" popup is shown.
    - The game ends and the total money won is displayed.

- 🛟 **Using the Lifeline**  
  - Players can use the **Lifeline** once per game.
  - It disables two of the three incorrect options, making it easier to choose the correct one.
  - Once used, the lifeline button is disabled for the rest of the game.

- 🏳️ **Quitting the Game**  
  - Players can quit anytime by clicking the **"Quit"** button.
  - A popup shows the total prize money earned until that point.

- 🏁 **End of Game**  
  - Occurs either when:
    - The player answers all questions correctly (game completion), or
    - The player selects a wrong answer, or
    - The player chooses to quit.
  - A final message displays the **total money won**.
------
## 📄 Sample Question Format
```
{
    "name": "India's largest city by population",
    "option1": "Delhi",
    "option2": "Mumbai",
    "option3": "Pune",
    "option4": "Bangalore",
    "answer": 2,
    "money": 1000
}
```
## 📜 License
    This project is licensed under the MIT License.

-----

## ⚠️ Disclaimer:
    This game is created for educational and entertainment purposes only. 
    It is not affiliated with the actual "Kaun Banega Crorepati" show or its producers.

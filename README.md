# 🧩 Riddler's Retreat

## Overview

Riddler's Retreat is a console-based riddle game developed in C that challenges players with a variety of brain teasers and logical puzzles. Players can choose from multiple question sets, answer riddles within a time limit, earn points for correct answers, and compete on a leaderboard.

The game is designed to improve critical thinking, problem-solving skills, and logical reasoning while providing an engaging and entertaining experience.

---

## ✨ Features

* 🎯 Six different riddle sets
* ⏳ 30-second timer for each question
* 🏆 Real-time leaderboard system
* 📊 Score tracking and ranking
* 🔄 Replay functionality
* 🧠 Challenging riddles and brain teasers

---

## 🛠️ Technologies Used

* **Language:** C
* **Libraries:**

  * stdio.h
  * stdlib.h
  * string.h
  * time.h

---

## 🎮 Game Rules

1. Enter your name to begin.
2. Choose one of the six available riddle sets.
3. Answer each question within 30 seconds.
4. Earn 5 points for every correct answer.
5. Wrong answers or timeouts receive no points.
6. Your score is added to the leaderboard after completing the set.
7. Replay to improve your score and ranking.

---

## 📊 Scoring System

| Result         | Points |
| -------------- | ------ |
| Correct Answer | +5     |
| Wrong Answer   | 0      |
| Time Exceeded  | 0      |

**Maximum Score per Set:** 25 Points

---

## 📂 Project Structure

```text
Riddlers-Retreat/
│
├── main.c
├── README.md
└── assets/
```

---

## 🚀 Compilation and Execution

### Compile

```bash
gcc main.c -o riddlers_retreat
```

### Run (Linux/Mac)

```bash
./riddlers_retreat
```

### Run (Windows)

```bash
gcc main.c -o riddlers_retreat.exe
riddlers_retreat.exe
```

---

## 🏆 Leaderboard System

The game includes a dynamic leaderboard that:

* Stores player names and scores
* Sorts players based on highest score
* Displays the Top 30 players
* Tracks player rankings
* Supports multiple game sessions

---

## 🎯 Learning Outcomes

This project demonstrates:

* Modular Programming using Functions
* Arrays and String Manipulation
* Sorting Algorithms
* User Input Handling
* Time-Based Game Logic
* Basic Data Management in C
* Console-Based Game Development

---

## 🔮 Future Enhancements

* Difficulty Levels
* Randomized Question Generation
* File-Based Score Storage
* Hint System
* Category-Wise Riddles
* Multiplayer Mode
* Graphical User Interface (GUI)

---


# 🎯 Celebrity Follower Showdown

*A Python terminal game that challenges your pop culture knowledge — built with a clever use of lists of dictionaries to manage dynamic game logic!*

---

## 🎮 What is it?

**Celebrity Follower Showdown** is a fun command-line game where you're shown two Indian celebrities and asked to guess who has more Instagram followers. Think you know your celebs? Let’s find out!

---

## 🚀 How It Works

- In each round, two celebrities are randomly selected.
- You choose which one you think has more followers.
- A correct guess increases your score and continues the game.
- A wrong guess ends the game.
- Score 15 points to win!

---

## 🧠 Smart Use of Data Structures

This project uses an elegant and effective data structure — a **list of dictionaries** — to store and manage celebrity names and follower counts.

### 🔍 Structure Example:
```python
celebs = [
    {"Virat Kohli, Cricketer": 270000000},
    {"Shraddha Kapoor, Actor": 94200000},
    ...
]

---

💡 Why It Works Well:
Maintains strong key-value pairing (celebrity : followers).

Easy to extract and compare data using:

python
Copy
Edit
name = list(celebrity.keys())[0]
followers = list(celebrity.values())[0]
Ideal for random selection and comparisons using random.choice.

Introduces nested structures (list + dict) — great practice for real-world coding.

This shows that even simple games can reflect a thoughtful understanding of data management!

---

📦 Features
Engaging command-line interaction

Clean comparison logic

Score tracking and winning condition

Repetition avoidance to improve gameplay experience

Perfect for beginners learning Python structures

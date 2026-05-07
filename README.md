# 🎮 Cannon Game - Git Collaborative Project

## 📌 Project Description

This project is a modified version of the classic **Cannon game** from the `freegames` library. The objective is to practice **Git workflow, collaboration, and code modification**, while understanding and documenting an existing codebase.

The game was analyzed, tested, and modified by the team in order to apply version control practices and implement functional changes.

---

## 👥 Authors

- Mau  
- Javi (repository owner)

---

## 🎯 Objectives of the Activity

- Test and understand an existing video game by reading its source code.
- Analyze and document the code according to the Institute's standards.
- Practice collaborative work using Git and GitHub.
- Apply controlled modifications to an existing project.

---

## 🔧 Implemented Modifications

### 🧑‍💻 Javi (Repository Owner)
- Increased the movement speed of:
  - Projectiles (cannon shot)
  - Balls (targets)
- This was done by modifying the velocity parameters inside the game loop.

### 🧑‍🤝‍🧑 Mau (Partner)
- Modified the game logic so that:
  - The game **never ends**
  - Balls that exit the screen are repositioned back into the game area
- This ensures continuous gameplay instead of termination conditions.

---

## 🧠 Technical Notes

- Language: Python
- Library: freegames (Cannon module)
- Framework used: Turtle graphics (via freegames implementation)
- Version control: Git + GitHub

---

## 📂 Repository Structure
---

## 🚀 How to Run the Game

Make sure you have Python installed:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install freegames

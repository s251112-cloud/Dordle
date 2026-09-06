# 🧩 Dordle — 2 Words at Once

A dual-grid web application built with pure HTML5, CSS3, and modern vanilla JavaScript. Test your vocabulary and deduction skills by solving **2 hidden words simultaneously** using the same guesses across both grids in **7 attempts** or fewer!

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## ✨ Features

- ✌️ **Dual-Grid Input Sync:** Each 5-letter guess updates two independent game boards simultaneously.
- 🎯 **7 Attempts Limit:** Balanced row count tailored for solving two secret words.
- 🔒 **Individual Board Locking:** When a word is correctly guessed, its board locks with a green banner (`SOLVED! ✓`) while inputs continue on the remaining board.
- 🔤 **Accurate Duplicate-Letter Algorithm:** Two-pass evaluation logic preventing duplicate-letter rendering bugs across both words independently.
- 📱 **Mobile-Responsive Flex Layout:** Scales smoothly for mobile devices and desktop screens.

---

## 🎮 How to Play

1. Type any **5-letter word** using your physical keyboard or the virtual keyboard.
2. Press **ENTER** to submit your guess to **both boards** at the same time.
3. Observe the tile color feedback on each board:
   - 🟩 **Green:** Letter is in the word and in the correct position.
   - 🟨 **Yellow:** Letter is in the word but in the wrong position.
   - ⬛ **Gray:** Letter is not in the word.
4. Solve both secret words before using up all 7 rows!

---

## 👥 Collaborator

Co-created by:
- **Celine**

---

*Made with ❤️ for multi-grid word puzzle enthusiasts!*

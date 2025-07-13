# Rock-paper-scissors-using-openCV

A real-time interactive Rock-Paper-Scissors game where the player uses hand gestures via webcam, and an AI opponent plays in return. The project is built using Python, OpenCV, and the cvzone library, which leverages MediaPipe for accurate hand detection.
This project is a blend of Computer Vision, Human-Computer Interaction, and classic game logic. It offers an engaging, hands-free experience using gesture recognition to identify whether the player shows Rock, Paper, or Scissors.

---


# 🧩 Project Overview

- 📷 Detects real-time hand gestures using a webcam
-  ✊✋✌️ Maps specific finger patterns to Rock, Paper, or Scissors
-  🎲 AI opponent randomly selects a move
-  🏆 Scores are tracked live on a custom graphical interface
-  👩‍💻 Simple keyboard trigger to start game rounds ('s' key)
-  💻 No buttons or clicks required — completely gesture-based!

---

# 🔧 Technologies Used
- Python:	Core language for logic and integration
- OpenCV:	Webcam input, image processing, overlay rendering
- cvzone:	Easy hand detection & image overlay (on top of OpenCV)
- MediaPipe:	Underlying model used for tracking hand landmarks
- NumPy:	For image slicing and numerical operations
- Canva: images	For background (bg.png) and AI hand visuals

---

# 🕹 How the Game Works

1. Game Start
- Player presses the 's' key.
- A 3-second countdown begins, shown on the screen.

2. Gesture Detection
- The webcam detects your hand and identifies which fingers are raised.
- Based on this, your move is determined:
- ✊ Rock 
- ✋ Paper 
- ✌️ Scissors

---

# Outcome & Scoring

- Based on the classic rules, the winner is decided:
- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock
- The score is updated on the interface and displayed for both AI and Player.

---

# 🧠 Behind the AI (and What's Coming)

Currently, the AI uses random move selection, but here's what can be added:
- 🚀 Planned Enhancements:
- ✅ Markov Models: To analyze and predict the player's next move based on past gestures (sequence learning).
- ✅ Reinforcement Learning: AI learns over time by adapting to player behavior.
- ✅ Gesture Smoothing: Avoids false detections using moving average of gestures.
- ✅ Dual Hand Mode: Support two-player mode with both hands detected.
- ✅ Voice Feedback or Sound Effects: For a richer game feel.

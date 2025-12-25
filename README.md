# 🎮 Cake Pop Demon Hunters

## Overview
Cake Pop Demon Hunters is an interactive computer vision game built with Python and OpenCV that uses real-time webcam input to control gameplay. Players defeat demons through physical movement, creating a motion-based gaming experience.

The game detects the player’s face and movement via a webcam feed and translates real-world actions into in-game mechanics.

---

## Gameplay Mechanics
- **Corner Demons**  
  Demons appear in the corners of the screen and are defeated when the player moves in front of them.

- **Falling Demons**  
  Demons fall from the top of the screen. Colliding with one ends the game.

- **Motion-Based Controls**  
  Player movement and face position directly affect gameplay using computer vision.

- **Scoring System**  
  Points increase as demons are defeated.

- **Game Over Logic**  
  The game ends when a falling demon collides with the player.

---

## Technologies Used
- Python  
- OpenCV  
- NumPy  
- Webcam-based computer vision  

---

## Features
- Real-time face and motion detection  
- Responsive, camera-controlled gameplay  
- Dynamic visual elements and animations  
- Live scoring and collision detection  
- Runs locally with minimal setup  

---

## How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install opencv-python numpy
3. Run the game:
   ```bash
   python CakePopDemonHunters.py
4. Make sure webcam is accessible

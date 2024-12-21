# Real-Time-Dinosaur-Game-with-Motion-Controlled-Simulation

This project reimagines the classic Chrome dinosaur game by introducing motion-based controls powered by computer vision. Players use real-time physical movements, captured via a webcam, to control the in-game dinosaur's actions such as jumping and ducking, creating a dynamic and immersive gameplay experience.
---

## Introduction
This project leverages computer vision technologies to deliver an innovative motion-controlled gaming experience. It integrates real-world actions with in-game responses, showcasing the potential of gesture-based interfaces in gaming.

Key objectives:
- Transform physical movements into game controls.
- Provide an engaging and accessible experience for users of all skill levels.

---

## Features
1. **Motion Capture Module**:
   - Real-time pose detection using a webcam.
   - Detection of movements like jumps and ducks with high accuracy.

2. **Game Logic Module**:
   - Smooth horizontal scrolling and obstacle generation.
   - Dynamic difficulty adjustments to enhance replayability.

3. **Dinosaur Animation Module**:
   - Realistic animations triggered by player movements.

4. **User Interface**:
   - Start screen with calibration options.
   - Real-time webcam feed and score display.
   - Game-over screen with restart options.

5. **Configuration Module**:
   - Adjustable sensitivity for motion detection.
   - Debug mode for visualizing pose landmarks.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `Pygame` for game development and rendering.
  - `OpenCV` for video processing.
  - `MediaPipe Pose` for pose detection.
  - `NumPy` for data processing.

---

## Gameplay Instructions
1. Launch the game and calibrate motion sensitivity on the start screen.
2. Use your webcam to interact:
   - Jump to make the dinosaur jump.
   - Bow to make the dinosaur duck.
3. Avoid obstacles to score points. The game gets progressively faster!

---

## Results
- **Motion Responsiveness**: Achieved <100ms latency between user actions and in-game responses.
- **Pose Detection Accuracy**:
  - 90% accuracy in well-lit environments.
  - 75-80% accuracy in low-light conditions.
- **User Experience**: Testers found the game fun and engaging, appreciating the novelty of motion controls.

---

## Future Enhancements
1. **Multiplayer Mode**: Support for multiple players using individual webcams.
2. **Mobile Version**: Adapt the game for mobile platforms.
3. **Dynamic Obstacles**: Add moving or falling objects for increased challenge.
4. **Augmented Reality (AR)**: Integrate AR for immersive gameplay.

---

## Contributors
- **T. Naga Sai Anirudh** (21BAI1861)
- **K. Santosh Kumar Reddy** (21BAI1374)
- **B.S.R. Siddhardha** (21BAI1478)

---

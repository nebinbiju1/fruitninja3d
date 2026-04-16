# 🍉 Fruit Ninja 3D

A browser-based Fruit Ninja game using webcam hand tracking via MediaPipe.

## How to Play

- **Start/Restart:** Show a 👍 thumbs up to the camera
- **Slice fruits:** Move your index fingertip fast across a fruit
- **Lives:** You have 3 lives — don't let fruits fall!
- **Difficulty:** Fruits speed up as your score increases

## Run Locally

```bash
cd fruitninja
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080) in your browser.

## Tech

- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands) — real-time hand tracking
- Vanilla JS + HTML5 Canvas
- No frameworks, no build step

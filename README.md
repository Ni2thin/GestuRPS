# Rock, Paper, Scissors Game with Hand Gesture Recognition  

This project implements a real-time Rock-Paper-Scissors game using a webcam, OpenCV, and MediaPipe. The game recognizes hand gestures to detect the player's move and plays against the computer.

---

## Features  

- **Real-time hand gesture detection**: Detects gestures for Rock, Paper, and Scissors using MediaPipe.  
- **Computer opponent**: The CPU randomly selects its move for each round.  
- **Scorekeeping**: Tracks both player and CPU scores.  
- **Reliable detection**: Uses the mode of recent hand gestures for stable recognition.  
- **Dynamic overlay**: Displays scores, moves, and the winner on the webcam feed.  

---

## How It Works  

1. The program uses OpenCV to capture video from the webcam.  
2. MediaPipe detects hand landmarks and identifies gestures based on the position of fingers.  
3. Gestures correspond to the moves:  
   - **0 fingers up**: Rock  
   - **2 fingers up**: Scissors  
   - **5 fingers up**: Paper  
4. The CPU randomly selects its move, and the winner of each round is determined.  
5. Scores are updated, and the game continues until the user exits by pressing the **Escape key**.  

---

## Prerequisites  

### Libraries:  
Install the required libraries using pip:  

```bash  
pip install opencv-python mediapipe```

---

## demo
![Gameplay Video](https://github.com/yourusername/yourrepo/blob/main/Rock-Paper-Scissors/output/output.mp4)


# 🏎️ Gesture Car Game

A gesture-controlled car game built using HTML5 Canvas, JavaScript, and [MediaPipe Hands,tensorFlow](https://google.github.io/mediapipe/solutions/hands) for real-time hand gesture recognition. Players control the car by showing different hand gestures in front of the webcam to accelerate and jump over obstacles!

![Game Preview](https://i.ibb.co/qjM91np/car-top-view.png)

---

## 🎮 Features

- 🖐️ **Hand Gesture Controls** using MediaPipe
- 🚘 **Smooth Car Physics** with acceleration and jump
- 🌲 **Obstacles** like trees to avoid
- 💥 **Collision Detection & Game Over**
- 🧠 **Score & Personal Best Tracking**
- 🎨 **Stylish UI** with gradients, shadows, and responsive layout
- 📷 **Webcam Preview** for real-time gesture tracking
- 🔁 **Restart Button** for quick replays
- 🔊 *(Optional)* Sound Effects support
- 📱 Mobile-Friendly canvas rendering (responsive layout)

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **MediaPipe Hands API** (via CDN)
- **Canvas API**
- **Webcam API**

---

## 🧠 How It Works

- **Open Hand (3+ fingers up)** → Accelerate the car
- **Two Fingers Up (index + middle only)** → Jump the car
- If the car hits an obstacle → 💥 Game Over
- Restart to play again and beat your **Personal Best**

---

## 🧩 Controls

| Gesture           | Action         |
|------------------|----------------|
| ✌️ (Two fingers)  | Jump & Boost   |
| ✋ (Open hand)    | Accelerate     |
| 👊 (Closed hand)  | Brake / Coast  |

---

## 🖥️ Setup Instructions

1. **Clone or Download** this repository.
2. Place the following files in the same directory:
   - `index.html` (your main game file)
   - `car-top-view.png` and `tree.png` (or use external links as used in the code)
3. Open `index.html` in **any modern browser** (Chrome/Edge preferred).
4. Allow webcam access when prompted.

---

## 📂 Project Structure


---

## 🧪 Optional Enhancements

Here are some ideas already prepared in the game logic or ready to be added:

- 🔊 **Add Sound Effects**
  - Include `<audio>` tags in HTML:
    ```html
    <audio id="jumpSound" src="jump.mp3"></audio>
    <audio id="crashSound" src="crash.mp3"></audio>
    ```
  - Then trigger with JavaScript on jump/collision.

- 🧠 **Increase Difficulty Over Time**
  - Add more speed or obstacles after every 5 points.

- ⏸ **Pause/Resume Feature**
  - Add a button and a flag to pause game rendering.

- 🎵 **Background Music**
  - Loop background music and mute/unmute toggle.

- 🏁 **Leaderboard (with localStorage or backend)**

---

## 📱 Mobile View Tip

- You can make the game responsive by adjusting canvas and video dimensions:
  ```css
  canvas {
    width: 90vw;
    height: auto;
    max-width: 800px;
  }


Let me know if you'd like me to turn this into a downloadable `README.md` file or create a GitHub repo structure for you.

Deployment
To host online:

Upload to GitHub Pages, Netlify, or Vercel.

Just make sure webcam permissions are allowed via HTTPS.

Permissions
This game requires webcam access to detect your gestures using MediaPipe Hands. All processing is done locally in your browser – no data is uploaded.

Credits
MediaPipe Hands by Google

Car and Tree Icons from Flaticon

Developed by You 👩‍💻 / 👨‍💻

License
MIT License – Free to use, modify, and share.


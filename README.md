# 🧠 Cuboid – Brain-Controlled Game

![Cuboid](assets/Game.png)

Welcome to **Cuboid**, an innovative neurofeedback game where you control shapes using your brainwaves! Using real-time EEG signals, you guide geometric shapes to the goal by increasing your **beta brainwave activity** — a truly mind-powered experience.

----

## 🔗 Requirements

- Neuro PlayGround Lite (NPG Lite) hardware device
- Web Bluetooth-compatible browser (Chrome / Edge)
- Secure context (HTTPS or `localhost`) to access BLE

---

## 🧩 Features

- 🎯 Goal-based gameplay driven by your **brainwave focus**
- 📶 Real-time EEG streaming from BLE devices like NPG Lite
- 🎛️ Multiple difficulty levels:
  - Beginner, Easy, Medium, Hard, Pro
- 📊 Live brainwave band visualization:
  - Delta, Theta, Alpha, Beta, Gamma
- 🔌 Device control panel (Connect / Disconnect / Start / Stop)
- 🎉 Goal celebrations and a win state on achieving 5 goals

---

## 🧪 File Structure

```
Cuboid/
├── index.html         # Main game logic and UI
├── style.css          # Custom styles and animations
├── README.md          # Project documentation
└── assets/            # Add device images, icons, or EEG diagrams
```

---

## 🕹️ How to Play

### 🎯 Goal
Push the cuboid upward by staying focused.

---

### 📋 Steps

1. **Connect your NPG Lite device.**
2. **Run calibration** to set your personal threshold.
3. **Select a difficulty level.**
4. **Stay focused to rise — lose focus and you'll fall!**

---

### 🎮 Levels

- 🟢 **Beginner:** +10 / -2 — Easy climb.
- 🟡 **Easy:** +8 / -3 — Gentle challenge.
- 🟠 **Medium:** +6 / -4 — Balanced play.
- 🔴 **Hard:** +4 / -5 — Demands focus.
- 🟣 **Pro:** +3 / -6 — Elite level.

---

### 🎨 Progress Bar

- 🔴 **Red:** Low focus
- 🟠 **Orange:** Warming up
- 🟡 **Yellow:** Midway
- 🟢 **Green:** Near goal

---

### 💡 Tips

- Visualize success or numbers.
- Stay still, relaxed, alert.
- **To recalibrate:** Click the **Stop Stream** button, then click **Start Stream** again.
- Train your brain. Improve focus. Enjoy the journey.

---

## 👩‍💻 Author

Built with curiosity by [**Ritika Mishra**](https://github.com/Ritika8081)

> Decoding mindfulness with every brainwave 💫

---

## 🤝 Contributing

Contributions are welcome! 🎉  
If you have ideas for new features, want to improve UI/UX, or optimize EEG signal processing—feel free to fork the repo, create a branch, and submit a pull request.

Steps to contribute:
1. Fork this repository
2. Create your feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Open a pull request

---

## 📜 License

**MIT License** – use freely, but give credit!
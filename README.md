<div align="center">

# 🎁 Here Is Your Gift

### A tiny interactive surprise made to feel like a gift.

<br>

<a href="https://here-is-your-gift.vercel.app/">
  <img src="https://img.shields.io/badge/✨%20Open%20The%20Gift-Live%20Website-ff4d6d?style=for-the-badge" alt="Open the Gift">
</a>

<a href="https://github.com/Hidden-Rhythm/here-is-your-gift">
  <img src="https://img.shields.io/badge/💻%20Source-GitHub-181717?style=for-the-badge&logo=github" alt="GitHub">
</a>

<br><br>

**A playful birthday surprise with music, animated messages, cute GIFs, and a little bit of chaos. 😆💗**

</div>

---

## 💝 What Is This?

**Here Is Your Gift** is a lightweight interactive birthday surprise website.

Instead of simply displaying a birthday message, it turns the greeting into a small interactive experience:

> **Open → Birthday Greeting → Gift Question → Countdown → Fake Traffic Jam → Cute Ending**

The experience uses animated transitions, typewriter text, floating hearts, sound effects, stickers, and interactive buttons to make the surprise feel more alive.

---

## ✨ Features

| Feature                  | Description                                                |
| ------------------------ | ---------------------------------------------------------- |
| 🎂 Birthday Greeting     | Opens with a personalized birthday message                 |
| 🎁 Interactive Gift Flow | The visitor progresses through a playful sequence          |
| ⌨️ Typewriter Text       | Messages are revealed with animated typing                 |
| 🎵 Background Music      | Includes a local MP3 soundtrack                            |
| 🖼️ Cute GIFs            | Multiple reaction stickers throughout the experience       |
| 💗 Falling Hearts        | Animated hearts appear during the final sequence           |
| 🖱️ Click Effects        | Small visual effects appear when interacting with the page |
| ⏳ Countdown              | A short countdown builds anticipation                      |
| 😆 Fake Traffic Jam      | A playful twist before revealing the ending                |
| 📱 Responsive            | Designed to work across mobile and desktop screens         |
| 🌌 Animated Background   | Full-screen image background with visual effects           |
| 💬 SweetAlert Dialog     | Interactive popup for the alternate response               |

---

## 🎬 The Experience

```text
          ┌─────────────────────┐
          │   🎁 Open The Gift  │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │  👋 Birthday Wish   │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ 🎁 Want A Gift?     │
          └──────────┬──────────┘
                     │
                  YES│
                     ▼
          ┌─────────────────────┐
          │    ⏳ Countdown     │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ 🚦 Traffic Jam 😭   │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │   💗 Cute Ending    │
          └─────────────────────┘
```

---

## 🎨 Visual Experience

The page combines:

* 🌑 Dark full-screen background
* 🪟 Glassmorphism-style message cards
* 💗 Floating heart animations
* ✨ Animated circular elements
* 🎀 Cute reaction stickers
* ⌨️ Typewriter-style messages
* 🖱️ Interactive click feedback
* 🔄 Smooth scale and fade transitions

The design uses several playful fonts including **Poppins, Quicksand, Nunito Sans, Caveat, Itim, and Inter**.

---

## 🎵 Music & Assets

All main media used by the experience is stored locally inside `assets/`.

```text
assets/
├── angelbabydj.mp3
├── cinta.gif
├── cubit.gif
├── gemoy.gif
├── ledekin.gif
├── ledekin (1).gif
├── terlope.gif
└── wpeach.jpg
```

This keeps the core visual and audio assets bundled with the project.

---

## 🧩 Project Structure

```text
here-is-your-gift/
│
├── assets/
│   ├── angelbabydj.mp3
│   ├── cinta.gif
│   ├── cubit.gif
│   ├── gemoy.gif
│   ├── ledekin.gif
│   ├── ledekin (1).gif
│   ├── terlope.gif
│   └── wpeach.jpg
│
├── index.html
└── README.md
```

The project intentionally keeps things simple: there is **no backend, database, framework, or build system** required.

---

## 🛠️ Built With

* **HTML5**
* **CSS3**
* **JavaScript**
* **Swiper**
* **SweetAlert2**
* **TypeIt**
* **ScrollReveal**
* **Google Fonts**
* **HTML Audio API**

External libraries are loaded through CDN links, while the project's main images, GIFs, and music remain in the `assets/` directory.

---

## 🚀 Run Locally

Since this is a static website, you don't need Node.js or Python.

Clone the repository:

```bash
git clone https://github.com/Hidden-Rhythm/here-is-your-gift.git
cd here-is-your-gift
```

Then open:

```text
index.html
```

in your browser.

For the best experience, you can also use VS Code's **Live Server** extension.

---

## ✏️ Customization

Most of the experience can be personalized directly from `index.html`.

You can modify:

* Birthday messages
* Button text
* Countdown behavior
* GIFs and stickers
* Background image
* Audio
* Animation timing
* Fonts
* Colors
* Popup messages

The main message sequence is controlled through the JavaScript `texts` and `images` arrays.

---

## 🌐 Live Website

### 🎁 Open the surprise

**https://here-is-your-gift.vercel.app/**

### 💻 Source Code

**https://github.com/Hidden-Rhythm/here-is-your-gift**

---

<div align="center">

### made with a little code and a lot of intention. 💗

**If it made you smile, mission accomplished.**

</div>

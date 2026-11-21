# Siddhant Dubey — Personal Developer Portfolio

> Full-stack developer, builder, and tinkerer. Building things, learning deeply, and documenting the journey.

A modern, high-performance developer portfolio featuring interactive 3D graphics, physics-based scroll animations, and clean responsive design.

---

## 👨‍💻 About Siddhant

Hi, I'm **Siddhant Dubey**. I build tools, web applications, MVPs, and experiments that move from idea to real users.

* **What I Build:** Web applications, browser extensions, startup MVPs, and intelligent automations.
* **Tech Stack & Interests:**
  * **Languages & Core:** Python, JavaScript (ESNext), TypeScript, HTML5, CSS3 / Modern CSS.
  * **Data & Science:** NumPy, pandas, machine learning experimentation.
  * **Frontend & Graphics:** React 18, Three.js (WebGL), GSAP + ScrollTrigger, Lenis smooth scrolling, Tailwind CSS, SVG vector animations.
  * **Systems & Tools:** Linux / Arch Linux, Git & GitHub, Node.js.
* **Connect with Me:**
  * **Email:** [s1ddhnt.16@gmail.com](mailto:s1ddhnt.16@gmail.com)
  * **GitHub:** [@s1ddhnt](https://github.com/s1ddhnt)
  * **LinkedIn:** [Siddhant Dubey](https://www.linkedin.com/in/siddhant-dubey-764392340/)
  * **Discord:** `942579114093731850`

---

## ✨ Features & Architecture

* **Interactive 3D Laptop Experience:** Real-time 3D laptop with scroll-driven opening animation, perspective zoom, and live ASCII terminal loop.
* **3D Perspective Flip Card:** Interactive character card in the About section with mouse tracking and click-to-flip interaction.
* **Scroll-Driven Vector Signature:** Handcrafted cursive signature path (`siddhant-signature.svg`) animated with GSAP `stroke-dashoffset`.
* **Curated Projects Showcase:**
  * **MeetHub:** Modern meeting and scheduling web application.
  * **Paladin Project:** Immersive 3D interactive environment.
  * **Sowser:** Fast, lightweight browser tool.
  * **Unhider for Reddit:** Chrome extension for uncovering hidden reddit content.
* **Dynamic Interactive Story Page (`/my-story`):** Interactive Processing.js canvas sketch featuring an animated Star Wars BB-8 droid.
* **Seamless Email Direct Action:** Single-click email links with automatic clipboard copy and instant Gmail compose tab redirect.
* **High-Performance & Responsive:** Optimized to 70+ FPS with zero layout thrashing, zero dropped frames, and seamless touch responsiveness.

---

## 🚀 How to Run & Open the Website

### Prerequisites
* [Node.js](https://nodejs.org/) (version 16 or newer installed on your computer).

---

### 💻 1. Running on Laptop / PC

#### Method A: One-Click Launcher (Windows)
Simply double-click the **`start.bat`** file in the project folder. It will start the server and automatically launch the website in your default browser.

#### Method B: Terminal Command
Open a terminal (PowerShell, Command Prompt, or bash) in the project root directory and run:

```bash
npm start
```
*(or `node server.js`)*

Open your browser and navigate to:
👉 **`http://localhost:3000`**

---

### 📱 2. Opening on Mobile / Phone (Same Local Wi-Fi)

You can preview and test the complete portfolio on your phone with full mobile touch interactions:

1. **Start the server on your laptop** using `npm start` or `start.bat`.
2. Look at the terminal output. The server automatically detects your local network IP and prints:
   ```text
   ==============================================
     Portfolio Website is running!

     💻 Laptop / PC : http://localhost:3000
     📱 Phone / LAN : http://192.168.1.X:3000
        (Ensure phone is on the same Wi-Fi)
   ==============================================
   ```
   *(Note: If you need to find your laptop's IP manually, open Command Prompt on your laptop and run `ipconfig`. Look for the **IPv4 Address**, e.g., `192.168.1.34`).*
3. **Connect your phone** to the **same Wi-Fi network** as your laptop.
4. Open the web browser on your phone (Safari on iPhone, Chrome on Android, etc.).
5. Type your laptop's network address in the phone's browser bar:
   👉 **`http://<YOUR-LAPTOP-IP>:3000`** *(e.g., `http://192.168.1.34:3000`)*.
6. The website will load with touch-optimized controls, mobile typography, and responsive layouts!

> **Phone Tip:** The laptop terminal features a playful responsive message when viewed on mobile screens (`You are on phone dude. Try to open this on laptop or pc. Lot of cool stuff there.`), while all projects, bio, capability cards, and links remain fully accessible.

---

## 📁 Project Structure

```text
portfolio/
├── .gitignore               # Ignores dependencies and the local _quarantine folder
├── README.md                # Project documentation and setup guide
├── avatar.webp              # Favicon and navbar avatar
├── bb8.js                   # Interactive Star Wars BB-8 Processing sketch
├── index.html               # Main HTML entry point & Gmail toast handler
├── package.json             # NPM metadata and scripts (npm start)
├── processing.min.js        # Processing canvas runtime for /my-story
├── server.js                # Lightweight Node.js static SPA HTTP server
├── start.bat                # Windows one-click startup batch script
├── _quarantine/             # Safely preserved unneeded files (kept locally)
└── assets/                  # Core application assets
    ├── Switzer-*.otf        # Local branding fonts
    ├── index-BDHMsrRa.js    # React 18, Three.js, GSAP & router bundle
    ├── index-CmQ7yN4u.css   # Optimized stylesheet and responsive rules
    ├── siddhant-signature.svg # Animated vector signature
    ├── profile_photo*.webp  # 3D character portrait textures
    ├── meethub*, paladin*, sowser*, unhider* # Project showcase preview images
    └── *.webp / *.svg       # Service and tech stack icons
```

---

## 📄 License

This project is licensed under the MIT License — see the [package.json](package.json) file for details.

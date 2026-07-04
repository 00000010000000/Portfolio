# Minimalist Glassmorphic Personal Portfolio

[cite_start]A premium, highly customized, single-page responsive portfolio website built with a clean white minimalist aesthetic and a soft mint green glassmorphic interface[cite: 3]. [cite_start]The project integrates an elegant user experience with smooth interactive elements inspired by modern Apple web designs [cite: 4, 30][cite_start], specifically tailored to showcase the academic and professional achievements of **Song Xinyan**[cite: 4].

---

## 🌟 Key Features & Interactive Highlights

### 1. Minimalist Glassmorphic Aesthetic & Micro-interactions
* [cite_start]**Theming:** Designed with a premium, clean white canvas layered with ambient mint green highlights (`#34d399` / `#a7f3d0`) and translucent containers using CSS `backdrop-filter`[cite: 5].
* [cite_start]**Custom Mint Green Cursor:** A custom, non-blocking circular cursor that follows the mouse movement smoothly and expands elegantly when hovering over clickable elements[cite: 6].
* [cite_start]**Typography:** Styled completely with **Source Han Sans (Noto Sans SC)** using ultra-light and thin weights (200/300) to mimic high-end physical paper layouts[cite: 7].

### 2. Multi-Section Smooth Scroll Journey
[cite_start]Users can seamlessly navigate through six distinct content sections using explicit mouse scroll-downs or the interactive menu[cite: 8]:

* [cite_start]**Hero / Home Section:** Features a large, fine-type centered name display: **Song Xinyan**[cite: 8]. [cite_start]Hovering over the name triggers a subtle mint green neon glow and gracefully rolls down a glassmorphic navigation menu (*About Me, Skills, Experience, Projects, Contact Me*)[cite: 9].
* [cite_start]**About Me Section:** Balanced layout showcasing a retro-filtered profile picture on the left [cite: 10][cite_start], perfectly aligned with structured cards on the right displaying **Profile, Education (CUHK-Shenzhen), Academic Honors (Dean's List), and Languages**[cite: 10].
* [cite_start]**Interactive MacBook Skills Terminal:** A beautifully rendered, minimalist CSS MacBook shape[cite: 11]. [cite_start]The display hosts a horizontal carousel of transparent round-corner containers (Languages, Hardware/Architecture, Tools, Frameworks) that support fluid dragging and touchpad scrolling[cite: 12].
* [cite_start]**Apple-inspired Experience Timeline:** Features high-fidelity toggle switches to swap dynamically between **Internship Experience** (ARM China, Hefei Comprehensive National Science Center) and **Project Experience**, preventing content clutter via smooth opacity transitions[cite: 13].
* [cite_start]**3D Physical Project Folders:** Features interactive, pure-CSS file folders[cite: 14]. [cite_start]Hovering raises the folder lid and tints the tab mint green [cite: 15][cite_start], while clicking seamlessly opens linked Feishu presentation slide documents[cite: 15].
* [cite_start]**One-Click Contact Copier:** Clean layouts for Email, Phone, and WeChat[cite: 16]. [cite_start]Clicking any item copies the text directly to the user's clipboard and triggers a sleek bottom micro-toast: *"Copied successfully, please contact me!~"*[cite: 17].

---

## 🛠️ Tech Stack & Implementation

* [cite_start]**Frontend Core:** HTML5, CSS3 (Flexbox, Grid, Custom Variables, Advanced Transitions) [cite: 18]
* [cite_start]**Interactions:** Vanilla JavaScript (ES6+) for cursor tracking, custom drag/carousel event handlers, clipboard API interactions, and navigation triggers[cite: 18].
* [cite_start]**Typography:** Google Fonts / Typekit (Noto Sans SC) [cite: 19]
* [cite_start]**Assets & Styling:** Inline SVG icons and pure CSS-drawn graphics (MacBook & Folders) ensuring lightning-fast load times and infinite resolution scaling[cite: 19].

---

## 📂 Project Structure

```text
├── index.html          # Main single-page web app containing HTML structure
├── css/
│   └── style.css       # Layout grids, glassmorphism, MacBook/Folder styles, animations
├── js/
│   └── main.js        # Scroll trackers, custom cursor, carousel physics, clipboard copy
└── README.md           # Documentation (This file)

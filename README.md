# HarShin-Portfolio
A Shinchan-themed interactive developer portfolio featuring a 3D model sandbox (Three.js / WebGL), a 3D endless runner arcade game, and a dynamic dual-mode content switcher. Built with HTML5, CSS3 (Tailwind), and vanilla JavaScript.
---

## 🎮 Portfolio Matrix — Harsh Singh

A Shinchan-themed, interactive developer portfolio featuring a **3D model viewer**, a **3D endless runner arcade game**, and a **dynamic dual-mode content switcher** (Funny / Flirty).

---

### 🛠️ Tech Stack & Technologies Used

- **HTML5** — Semantic structure, meta tags, embeds
- **CSS3** — Custom animations (`@keyframes`), grid layouts, transitions, pseudo-elements
- **Tailwind CSS (CDN)** — Utility-first styling, responsive breakpoints (`sm`, `md`, `lg`), backdrop blur, shadows
- **Vanilla JavaScript (ES6+)** — DOM manipulation, event listeners, state management, game loop logic
- **Three.js (r128)** — WebGL 3D rendering engine
  - `THREE.Scene`, `THREE.PerspectiveCamera`, `THREE.WebGLRenderer`
  - `THREE.AmbientLight`, `THREE.DirectionalLight`
  - `THREE.MeshStandardMaterial`, `THREE.BoxGeometry`, `THREE.SphereGeometry`, `THREE.DodecahedronGeometry`, `THREE.CylinderGeometry`, `THREE.ConeGeometry`
  - `THREE.Box3` — Bounding box calculations for model centering and scaling
- **GLTFLoader (Three.js addon)** — Loading `.glb` 3D models
- **Google Fonts** — Plus Jakarta Sans (variable weights 400–800)

---

### ✨ Features

- **🏠 Hero Section** — Animated intro card with Shinchan GIF embed, social links (LinkedIn, GitHub), and a Hindi dialogue banner
- **🔄 Mischief Mode Toggle** — Switches entire page content between "Funny" and "Flirty" modes dynamically (titles, descriptions, project cards, contact section)
- **🧊 3D Sandbox Viewer** — Interactive 3D viewport with drag-to-rotate, auto-rotation, and zoom in/out controls; loads `shinchan.glb` with a red cube fallback
- **🏃 3D Buri Buri Dash Game** — Endless runner built entirely in Three.js
  - Player character (GLB model or fallback block figure)
  - Procedurally spawned obstacles: **stones**, **rocks**, **books**, **fountains**
  - Jump physics (velocity + gravity simulation)
  - Collision detection (radial distance calculation)
  - Real-time score counter with zero-padded display
  - Start/restart overlay system
  - Keyboard (`Space`, `ArrowUp`) and click/tap input support
- **📊 Skills Matrix** — Categorized grid displaying Programming Languages, ML/AI, Data Science, Web Dev, Databases, Tools, and CS Fundamentals
- **📁 Projects Section** — Cards for **DoScree** (NLP Resume Screening) and **Aide** (System Automation Framework)
- **📬 Contact Hub** — Email, phone, and a themed flirt-script banner
- **🎨 Comic / Neo-Brutalist Design** — Thick borders, hard box shadows, dotted grid background, skewed/rotated elements, badge-style labels

---

### 🎨 Design System

- **Background** — Off-white (`#fcf9f2`) with radial dot grid pattern (`bg-comic-grid`)
- **Borders** — 4px solid black (`border-neutral-900`)
- **Shadows** — Hard offset shadows (`shadow-[10px_10px_0px_0px_rgba(0,0,0,1)]`)
- **Colors** — Yellow (`#facc15`), Red (`#ef4444`), Pink (`#ec4899`), Indigo (`#6366f1`), Emerald (`#34d399`)
- **Typography** — Plus Jakarta Sans, monospace for code/tags
- **Animations** — Floating pepper effect, text twist, pulse loader

2. Open `index.html` in any modern browser
3. (Optional) Add `shinchan.glb` to the root for 3D model support
4. No build tools or server required — fully static

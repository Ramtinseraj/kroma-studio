# KROMA STUDIO — Silk Creative Engine

A fully functional, tactile, **Neomorphic / Soft UI** web creative suite based on Google Stitch prototypes and `DESIGN.md` specifications.

---

## 🌟 Overview & Key Features

### 1. Studio Hub (Matches `screen.png` & Google Stitch)
- **Extruded Soft UI Neomorphic Design**: Pixel-perfect implementation of `DESIGN.md` guidelines ("Extruded Light", `#e8eaf0` surfaces, `#6366f1` Indigo primary accents, tactile raised shadows, and recessed sunken tracks).
- **Smart AI Quick-Splice Engine**: Generates one-touch rhythm alignments with real-time waveform progress, 128 BPM transients detection, and automatic beat cuts.
- **Synthesized Web Audio Engine**: Zero external audio downloads needed! Built with standard Web Audio API generating authentic Phonk Drill and Hyperpop stems with dynamic audio visualizer waveforms.
- **All 12 Creative Mode FX Engines**: Interactive gallery containing Velocity Beats, AI Face Sculpt, Cyber & Glitch, Smart Matting, VHS 90s Cam, CRT Scanlines, Golden Hour, Noir 35mm, Neon Edge Glow, Anime Cel Shading, Tilt-Shift, and Retro Synthwave.
- **Active Drafts Manager**: Preloaded projects (*Cyberpunk Tokyo Reel*, *Golden Hour Portrait*, *Club Hyper-Glitch Cut*) with in-place playback, timeline editing, color grading, and vault management.
- **Silk AI Copilot**: Interactive voice & text assistant with speech recognition (`Web Speech API`), voice synthesis, and one-tap quick action prompts.

### 2. Multi-Track Video Timeline Editor (`Video` Tab)
- Real-time HTML5 Canvas video monitor with animated cinematic lighting, neon reflections, and camera drift.
- Live shader-based visual FX toggles: **Glitch RGB Split**, **Velocity Ramp**, **CRT Scanlines**, and **VHS 90s**.
- Interactive draggable Playhead scrubber and time ruler.
- **Split at Playhead** tool (`content_cut`), speed controls (`0.5x`, `1.0x`, `2.0x`), and beat-drop indicators.
- **Import Media**: Drag & drop or upload your own `.mp4`, `.webm`, `.png`, or `.jpg` files directly into the timeline.

### 3. RAW Photo & Color Grading / LUT Studio (`Photo` Tab)
- Real-time hardware-accelerated color grading canvas.
- **Interactive Before/After Split Comparison Slider** to inspect grades in real time.
- One-touch 3D LUT Presets: *Golden Hour 04*, *Cyber Neon*, *Vintage 35mm*, *Emerald Moody*, and *Noir 35mm*.
- Tactile Neomorphic Tone Sliders: Exposure, Contrast, Saturation, and Warmth / Sepia.
- **AI Face Sculpt**: Real-time glow contour and skin smoothing.
- **Smart Matting**: 1-tap background keying and cutout extraction.
- Instant High-Res PNG / JPG download.

### 4. Export & Master Rendering Studio (`Export` Tab)
- Destination presets: *Instagram Reels*, *TikTok Viral (Beat Lock)*, *YouTube 4K*, and *Feed Square*.
- Resolution options: `4K UHD (2160p)`, `1080p Full HD`, and `720p HD`.
- Container format options: `MP4 (H.264)`, `WebM`, and `GIF`.
- Automated render pipeline simulation with celebratory tactile completion and instant master file download.

---

## 🚀 How to Run the App

### Option 1: Direct File Open (No Server Required)
Simply double-click `code.html` or `index.html` in Windows Explorer or open it in any modern browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local HTTP Server (Node.js)
From the project folder, run:
```bash
npm start
# or
node server.js
```
Then navigate to `http://localhost:3000` in your browser.

---

## 🎨 Design System Compliance (`DESIGN.md`)
- **Surface Color**: `#e8eaf0` consistent background across the app.
- **Raised Elements**: `box-shadow: 6px 6px 14px rgba(163, 168, 187, 0.45), -6px -6px 14px rgba(255, 255, 255, 0.9)`
- **Pressed/Sunken Tracks**: `box-shadow: inset 3px 3px 6px rgba(163, 168, 187, 0.45), inset -3px -3px 6px rgba(255, 255, 255, 0.85)`
- **Typography**: Plus Jakarta Sans
- **Accent**: Indigo `#6366f1` / Violet `#7c3aed`

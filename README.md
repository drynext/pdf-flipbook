# FlipOS

FlipOS is a high-performance, web-based PDF visualization engine. It transforms static documents into an interactive 3D flipbook, integrated with a secure AI-powered studio for geometric drafting and intelligent data analysis.

---

## CORE FEATURES

### ARCHITECTURE
* CLIENT-SERVER SECURITY: Backend proxy for API Key protection.
* PERSISTENT STORAGE: Files are stored locally using IndexedDB for session restoration.
* GRID LAYOUT: Hard-locked split interface ensuring zero UI obstruction.

### STUDIO TOOLS
* DRAWING ENGINE: Supports Pen, Highlighter, and Real-time Eraser with right-click toggle.
* GEOMETRY: Integrated drafting for 2D shapes and 3D wireframe models.
* SHAPE STABILIZATION: Automatic geometric correction for hand-drawn lines.
* UNDO SYSTEM: Precise state management for stroke reversal.

### INTELLIGENCE
* GEMINI AI INTEGRATION: Intelligent document summarization and analysis.
* VOICE CONTROL: Hands-free operation for navigation and system commands.
* AI SCAN: Selective region analysis powered by generative models.

---

## TECHNICAL SPECIFICATIONS

* FRONTEND: Vanilla ES6+ JavaScript, CSS Grid Level 3, Canvas API.
* BACKEND: Node.js, Express, dotenv.
* LIBRARIES: PDF.js (Rasterization), St.PageFlip (3D Physics).
* STORAGE: IndexedDB (Client-side persistence).

---

## COMMAND REFERENCE

* PREVIOUS PAGE: Left Arrow or Up Arrow.
* NEXT PAGE: Right Arrow or Down Arrow.
* UNDO ACTION: Ctrl + Z.
* ZOOM IN: Plus (+) key.
* ZOOM OUT: Minus (-) key.
* RESET VIEW: Double Click background.

---

## DEPLOYMENT GUIDE

1. BACKEND SETUP
   - Navigate to the server directory.
   - Run: npm install express cors dotenv @google/generative-ai
   - Set GEMINI_API_KEY in the .env file.
   - Execute: node server.js

2. FRONTEND SETUP
   - Open index.html in any modern web browser.
   - Upload PDF files directly to the local browser storage.

---

## AUTHOR

DANG DUC DAI
FlipOS Enterprise Edition | 2026

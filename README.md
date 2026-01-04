# FlipOS V24 (Stable Studio)

FlipOS V24 is an advanced web-based PDF visualization engine that transforms static PDF documents into a realistic 3D interactive flipbook with professional studio-grade annotation capabilities. Built on a robust Monolith Architecture with a Hard-Locked Split Layout, it ensures a seamless reading and drawing experience without UI overlaps.

## ✨ Features

* **Core Architecture:**
    * **Hard-Locked Split Layout:** Uses CSS Grid to separate the screen into rigid zones (Tools, Viewport, Navigation), ensuring UI elements never obstruct the book content.
    * **Dual UI Modes:** Automatically switches between **Desktop Mode** (Vertical sidebars) and **Mobile Mode** (Horizontal bars).
* **Reading Engine:**
    * **3D Page Flip:** Realistic physical page-turning effects.
    * **Smart Rendering:** Auto-calculates dimensions for Single or Dual-page spreads.
* **Advanced Ink Subsystem:**
    * **Seamless Handover:** Draw continuous lines across the book spine (from left page to right page) without interruption.
    * **Smart Tools:** Pen (Pressure simulated), Highlighter (Fixed opacity for visibility), and Real-time Eraser.
    * **Shape Snap:** Draw a rough line and hold the cursor still for 600ms to automatically straighten it.
    * **Advanced Undo:** Precise state management capturing canvas states before strokes are rendered.
* **Zoom & View:**
    * **Vector Zoom:** High-fidelity zooming without pixelation.
    * **Pan Interaction:** Drag-and-drop panning when zoomed in (similar to map applications).
    * **Spyglass:** A floating 5x magnifying lens with automatic cursor correction.
* **Interface:**
    * **Dark/Light Theme:** Toggle between deep space dark mode and clean light mode.
    * **Responsive Design:** Fully adapts to any screen size.

## 🛠️ Technology Stack

* **HTML5/CSS3:** Semantic markup with CSS Grid Level 3 Layout.
* **JavaScript (ES6+):** Pure Vanilla JS with Object-Oriented Architecture.
* **PDF.js:** Rendering PDF documents into HTML5 Canvases.
* **St.PageFlip:** Library for the 3D page-flipping physics.
* **FontAwesome:** Scalable vector icons.
* **JetBrains Mono & Inter:** Professional typography.

## 🚀 How to Use

1.  **Open the Application:** Open `index.html` in any modern web browser (Chrome, Edge, Safari).
2.  **Upload PDF:** Click the upload box to select a PDF file from your device.
3.  **Navigation:**
    * Use the on-screen arrows or keyboard arrow keys (`←`, `→`) to flip pages.
    * Toggle between **READ** and **STUDIO** (Draw) modes using the top-left switcher.
4.  **Drawing (Studio Mode):**
    * Switch to **STUDIO** mode.
    * Select a tool (Pen, Highlighter, Eraser) from the left sidebar.
    * Choose a color from the palette.
    * **Shape Snap:** Draw a line and hold the mouse button down at the end for ~600ms to snap it straight.
5.  **Zooming:**
    * Use the `+` and `-` buttons in the right sidebar.
    * **Pan:** When zoomed in (Read mode), click and drag the page to move around.
    * **Reset:** Double-click anywhere on the background to reset zoom to 100%.
6.  **Magnifier:** Click the search icon (`🔍`) to toggle the Spyglass lens.

## 📦 Installation

No installation is required. This is a client-side web application.

1.  Clone or download the repository.
2.  Ensure you have an internet connection (to load CDNs for PDF.js and PageFlip).
3.  Open `index.html` in your browser.

## 📝 License

This project is created by **Dang Duc Dai**.

---
*Note: This application relies on external CDN links for libraries. For offline use, you would need to download `pdf.js`, `pdf.worker.js`, and `page-flip.browser.js` locally.*

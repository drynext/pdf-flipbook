# FlipOS V12 (Final)

FlipOS V12 is a web-based PDF viewer that transforms static PDF documents into an interactive flipbook with drawing and annotation capabilities. It features a modern, clean interface inspired by operating system design, offering both "Read" and "Draw" modes.

## ✨ Features

* **PDF to Flipbook:** Automatically converts PDF files into a realistic 3D page-flipping experience.
* **Dual Modes:**
    * **READ Mode:** Optimized for reading with page navigation and zoom controls. Mouse interactions are used for page turning.
    * **DRAW Mode (Studio):** Unlocks a suite of drawing tools. Disables page turning via mouse drag to prevent conflicts.
* **Advanced Drawing Engine:**
    * **Pen Tool:** Smooth, pressure-simulated lines.
    * **Highlighter:** Translucent marker that blends with text (multiply mode).
    * **Eraser:** Removes strokes.
    * **Shape Snap:** Draw a rough line and hold the cursor still at the end to automatically straighten it.
    * **Undo:** Supports undoing previous strokes (Ctrl+Z).
* **Zoom & Pan:** Zoom in for detailed reading or drawing. Includes a pan overlay to move around the zoomed document.
* **Magnifying Glass (Spyglass):** A floating lens to inspect details with high precision, correcting cursor offsets.
* **Dark/Light Theme:** Toggle between dark and light modes for comfortable viewing.
* **Responsive Design:** Adapts to different screen sizes, with a mobile-friendly layout toggler.
* **Keyboard Shortcuts:**
    * `Arrow Left` / `Arrow Right`: Turn pages.
    * `Ctrl + Z`: Undo drawing.

## 🛠️ Technology Stack

* **HTML5/CSS3:** Core structure and styling.
* **JavaScript (ES6+):** Application logic.
* **PDF.js:** Rendering PDF documents into HTML5 Canvases.
* **St.PageFlip:** Library for the 3D page-flipping effect.
* **FontAwesome:** Iconography.
* **Inter Font:** Typography.

## 🚀 How to Use

1.  **Open the Application:** Open `index.html` in a modern web browser.
2.  **Upload PDF:** Click the upload box to select a PDF file from your device.
3.  **Navigation:**
    * Use the on-screen arrows or keyboard arrow keys to flip pages.
    * Toggle between **READ** and **DRAW** modes using the top bar.
4.  **Drawing:**
    * Switch to **DRAW** mode.
    * Select a tool (Pen, Marker, Eraser) from the side panel.
    * Choose a color.
    * Draw directly on the page.
    * To draw straight lines, draw a line and hold the mouse button down at the end point for about 600ms.
5.  **Zooming:**
    * Use the `+` and `-` buttons in the bottom bar.
    * When zoomed in (Read mode), click and drag to pan around the page.
6.  **Magnifier:** Click the search icon in the bottom bar to toggle the magnifying glass.

## 📦 Installation

No installation is required. This is a client-side web application.

1.  Clone or download the repository.
2.  Ensure you have an internet connection (to load CDNs for PDF.js, PageFlip, and FontAwesome).
3.  Open `index.html` in your browser.

## 📝 License

This project is created by **Dang Duc Dai**.

---
*Note: This application relies on external CDN links for libraries. For offline use, you would need to download `pdf.js`, `pdf.worker.js`, and `page-flip.browser.js` locally.*

# Simplifying Compliance for Research Analysts - Landing Page

A highly responsive, pixel-perfect landing page designed specifically for independent research analysts and firms. This project was meticulously translated from a high-fidelity Figma design into clean, maintainable vanilla HTML and CSS.

## 🚀 Features

- **Pixel-Perfect Fidelity**: Matches the original Figma design down to the exact hex codes, padding, typography, and overlapping background vectors.
- **Fully Responsive**: Features a robust CSS architecture with two strict layout breakpoints:
  - **Desktop (1440px)**: A wide, elegant layout with perfectly balanced hero elements, absolute-centered navigation, and a 2-column feature grid.
  - **Mobile (375px)**: A clean vertical stack with a custom full-screen mobile menu overlay and perfectly scaled assets.
- **Zero Dependencies**: Built entirely with Vanilla HTML5 and CSS3—no heavy frameworks or libraries, ensuring lightning-fast load times.
- **Custom Overlays**: Includes an interactive, animated mobile navigation menu that takes over the screen seamlessly.

## 💻 Tech Stack

- **Structure**: HTML5
- **Styling**: CSS3 (CSS Variables, Flexbox, CSS Grid)
- **Typography**: Google Fonts (`Inter`, `Roboto`, `Figtree`)
- **Assets**: Optimized PNGs exported directly from Figma

## 📂 Project Structure

```text
FigWeb/
├── index.html       # The main entry point containing the landing page structure
├── index.css        # Global styles, variables, desktop layout, and mobile media queries
├── README.md        # Project documentation
└── assets/          # Directory containing all high-fidelity images and decorative vectors
```

## 🛠️ Getting Started

Because this is a static site, you don't need any complex build tools to run it. 

### Prerequisites
- [Node.js](https://nodejs.org/) installed (for running a quick local server)

### Running Locally

1. Open your terminal and navigate to the project directory:
   ```bash
   cd path/to/FigWeb
   ```
2. Run a local development server using `npx`:
   ```bash
   npx serve .
   ```
3. Open your browser and navigate to `http://localhost:3000` to view the landing page.

## 🎨 Design Specifications

- **Primary Color**: `#4356D6`
- **Primary Hover**: `#051AA3`
- **Text Main**: `#000000`
- **Text Muted**: `#606060`
- **Background Tones**: `#FFFFFF`, `#FAFBFF`, `#F5F6FA`
- **Fonts**: 
  - `Roboto` (Main Body)
  - `Figtree` (Navigation)
  - `Inter` (Special Elements)

## 🔧 Recent Updates
- Refined absolute positioning for overlapping decorative vectors (`Vector1.png`, `Vector2.png`) to ensure they stay structurally clean and responsive across both desktop and mobile viewports without colliding with text or illustrations.
- Migrated composite badges to reduce DOM clutter and improve performance.
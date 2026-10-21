---
name: interactive-presentation-design
description: Guidelines and design system for building interactive, visually arresting web presentations, investor pitch decks, and regulatory dashboards with aeronautical HUD aesthetics, smooth micro-interactions, dynamic calculators, and instant GitHub Pages deployment.
---

# Interactive Presentation & Web Design Skill

Use this skill whenever creating rich, engaging web presentations, interactive slide decks, and data-driven dashboards.

## Core Architectural Principles

1. **Non-Generic Visual Identity:**
   - Avoid plain bootstrap/corporate templates.
   - Use thematic palettes: for drone/aeronautical projects, employ Deep Navy/Obsidian (`#080c16`, `#0e182a`), Cyan Radar Glow (`#00f2fe`), Emerald Status (`#10b981`), Warning Amber (`#f59e0b`), and Cyber Coral (`#ff4b4b`).
   - Use Glassmorphism with crisp sub-pixel borders (`border: 1px solid rgba(255, 255, 255, 0.08)` and `backdrop-filter: blur(16px)`).
   - Dynamic canvas backgrounds: HUD radar circles, animated telemetry grid lines, constellation particles.

2. **Presentation Modes:**
   - **Slide-Deck Mode:** Fullscreen keyboard-driven navigation (Arrow keys, Spacebar, Swipe) with progress bar and slide counter.
   - **Scrollable Dashboard Mode:** Comprehensive one-page executive overview with sticky navigation and floating table of contents.
   - **Interactive Widgets:**
     - Live Financial Simulator (adjust price, flights/day, days/month to calculate revenue, ROI, and break-even).
     - Filterable Matrix (Class A vs Class B comparison pills).
     - Step-by-Step Regulatory Roadmap (interactive stepper with document checklists and download triggers).

3. **Animation & Transition Architecture:**
   - Hardware-accelerated CSS keyframes (`transform`, `opacity`).
   - Staggered entry reveals on slide activation.
   - Smooth hover micro-interactions with glowing box-shadows (`box-shadow: 0 0 25px rgba(0, 242, 254, 0.25)`).

4. **Zero-Dependency Portability (GitHub Pages Ready):**
   - Pure modern HTML5, CSS3, and ES6+ JavaScript.
   - Fully responsive on mobile, tablet, and widescreen 4K displays.
   - Direct execution via double-click, local web server, or `gh-pages` deployment without Node/Webpack build steps.

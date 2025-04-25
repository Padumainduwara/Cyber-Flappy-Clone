# Cyber Flappy

A neon cyberpunk–themed endless-flappy game built with pure HTML, CSS, and JavaScript.

## Demo

![Gameplay Demo](screenshot.gif) *(Replace with your actual demo GIF or screenshot.)*

## Features

- **Retro Neon Aesthetic**: Futuristic grid background with glowing scanlines
- **Endless Gameplay**: Procedurally generated obstacles
- **Responsive Full-Screen Canvas**: Adapts to any viewport size
- **Trail & Glow Effects**: Dynamic particle trails and lighting
- **Audio Feedback**: Flaps, scoring chimes, hit explosions, and background music
- **High Score Persistence**: Saves best score in LocalStorage

## Tech Stack

- **HTML5 Canvas API** for rendering
- **Vanilla JavaScript (ES6+)** for game logic
- **Tailwind CSS** via CDN for utility-first styling
- **Google Fonts**: Orbitron for cyber-futuristic typography
- **Font Awesome** for UI icons

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari) with JavaScript enabled

### Run Locally

```bash
# Clone the repo
git clone https://github.com/Padumainduwara/Cyber-Flappy-Clone.git
cd cyber-flappy

# Open the game
# - Double-click `Cyber Flappy.html`, or
# - Run:
open "Cyber Flappy.html"    # MacOS
start "Cyber Flappy.html"   # Windows
```

## Controls

- **SPACE** or **Click/Tap**: Make the bird flap and ascend

## Folder Structure

```
cyber-flappy/
└── Cyber Flappy.html    # Main game file with embedded HTML, CSS, and JS
```

## Deployment

You can host this game using **GitHub Pages**:
1. Rename `Cyber Flappy.html` to `index.html`.
2. Push to your repository’s `main` branch.
3. In GitHub Settings → Pages, select `main` → `/ (root)`.
4. Visit `https://<your-username>.github.io/cyber-flappy/`.

## Customization

- **Styles**: Tweak colors, grid spacing, and flicker via the `<style>` block
- **Audio**: Swap out sound URLs in the `<audio>` tags
- **Gameplay**: Adjust `pipeGap`, `pipeInterval`, `gravity`, and `jumpForce` in the script

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.


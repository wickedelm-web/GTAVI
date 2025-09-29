# GTA VI Landing Page Clone

An interactive and animated landing page inspired by Grand Theft Auto VI, built with React, GSAP, and TailwindCSS.

## Features

- Dynamic intro animation with masking effect
- Parallax scrolling effects
- Interactive mouse movement animations
- Responsive design
- Custom font integration
- Smooth transitions and animations

## Tech Stack

- React 19
- GSAP (GreenSock Animation Platform)
- TailwindCSS
- Vite
- Remixicon

## Project Structure

```
GTAVI/
├── public/                # Static assets
│   ├── bg.png            # Background images
│   ├── girlbg.png        # Character image
│   ├── sky.png           # Sky background
│   ├── ps5.png           # PlayStation 5 logo
│   ├── imag.png          # Additional images
│   └── pricedown.otf     # Custom font file
├── src/
│   ├── App.jsx           # Main application component
│   ├── index.css         # Global styles
│   └── main.jsx          # Application entry point
└── package.json          # Project dependencies
```

## Setup & Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```
3. Start development server:
```bash
npm run dev
```

## Key Features Explained

### 1. Intro Animation
The landing page starts with a dramatic "VI" text reveal using SVG masks and GSAP animations.

### 2. Mouse Movement Effects
Interactive parallax effect on mouse movement affecting:
- Main text
- Sky background
- City background

### 3. Animations
Multiple GSAP animations including:
- Scale transitions
- Rotation effects
- Opacity changes
- Position animations

### 4. Responsive Design
- Flexible layouts using TailwindCSS
- Responsive image scaling
- Mobile-friendly interface

## Customization

### Font
The project uses "Pricedown" font, which is loaded via @font-face in index.css:

```css
@font-face {
    font-family: "pricedown";
    src: url("/pricedown.otf");
}
```

### Colors & Styling
The project uses TailwindCSS for styling. Major style elements can be modified in:
- index.css for global styles
- Tailwind classes in App.jsx for component-specific styling

## Build & Deployment

To build for production:
```bash
npm run build
```

To preview production build:
```bash
npm run preview
```

## License
This is a fan project for educational purposes only. GTA and all associated properties are trademarks of Rockstar Games.
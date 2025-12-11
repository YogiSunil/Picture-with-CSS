# Picture with CSS – Project Overview

This project is a pure CSS artwork: a cosmic galaxy scene with stars, nebulae, planets, a spaceship, asteroids, a comet, and a space station. It showcases modern CSS techniques like gradients, clip-path, transforms, and keyframe animations.

## What It Does
- Renders an animated space scene entirely with HTML/CSS (no images).
- Provides multiple visual themes (Cosmic, Midnight, Mars Sunset) by switching CSS custom properties.
- Persists your selected theme using localStorage.

## How It Works
- CSS Custom Properties: A `:root` block defines variables for colors, sizes, positions, animations, and effects. Theme classes on `<body>` override these variables to restyle the entire scene.
- Fallbacks: `var(--name, fallback)` ensures the scene renders even if a variable isn’t defined.
- Components:
  - Starfield and particles animate via keyframes.
  - Nebulae use blurred gradients for atmospheric depth.
  - Planets and comet combine radial, linear, and conic gradients.
  - Spaceship and station shapes use `clip-path`, transforms, and layered gradients.
- Theme Controls: Buttons call `switchTheme(theme)` to add/remove theme classes and save your preference.

Open `Index.html` to view and interact with the scene.

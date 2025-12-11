# Picture with CSS – Themed with Custom Properties

This project demonstrates a parameterized CSS picture using CSS custom properties (variables), theme overrides, and optional external styles.

## How to Switch Themes
- Use the buttons at the top-left of the page:
  - "Cosmic" (default): base `:root` variables
  - "Midnight": applies `.dark-theme` to `<body>`
  - "Mars Sunset": applies `.sunset-theme` to `<body>`
- Theme preference is saved in `localStorage` and loaded on page start.

## External Theme Override
- The link tag for `external-theme.css` is enabled in `Index.html`.
- This stylesheet overrides the same variables (with `!important`) to demonstrate how external styles can replace theme values.
- If you want to preview without external overrides, comment out the link in `Index.html`.

## Screenshots for Submission
- Capture and submit at least two screenshots:
  - One with the default Cosmic theme.
  - One with Midnight or Mars Sunset.
- Optionally include a third screenshot with `external-theme.css` enabled to show cyberpunk overrides.

## Notes
- Variables are grouped for colors, sizes, positions, animations, and effect intensities.
- Most `var(...)` usages include fallback values to ensure robust rendering if a variable is missing.
- Accessibility: reduced motion is respected via `prefers-reduced-motion`.

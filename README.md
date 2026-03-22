# Truly Whiteboard

A minimal, zero-dependency whiteboard app built with vanilla HTML, CSS, and JavaScript. Single file, no build step — just open and go.

## Usage

Open `index.html` in any modern browser. That's it.

Or serve locally:

```bash
python3 -m http.server 8000
```

## Features

- **Background color** — pick any color via hex input; grid contrast auto-adapts to luminance
- **Grid patterns** — dots, lines, or cross overlays (toggle from the FAB menu)
- **Pixel rulers** — left and bottom rulers with major/minor tick marks, high-DPI aware
- **Responsive** — full-viewport canvas that adjusts on resize

## Tech

- Pure HTML5 / CSS3 / JavaScript — no frameworks, no dependencies
- Canvas API for ruler rendering
- CSS gradients for grid patterns
- Single `index.html` file (~365 lines)

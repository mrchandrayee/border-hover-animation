# Border Hover Animation

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/border-hover-animation/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A runnable reconstruction of the border-drawing hover effect shown in the supplied video.

## What it does
- Displays a dark “Hover Me” button on a deep navy background.
- On hover or keyboard focus, a thin white rectangular border animates into view.
- The vertical and horizontal border strokes grow from the centre using CSS pseudo-elements.
- Responsive and supports reduced-motion preferences.

## Run

No install or build step is required. Open `index.html` directly, or run:

```bash
python -m http.server 8000
```

Visit http://localhost:8000

## Project structure

```text
border-hover-animation/
├── index.html
├── style.css
└── README.md
```

## Source reconstruction note

The recording shows the rendered button and a partially readable CSS panel. The visible code indicates a pseudo-element with `width: 0`, `height: 100%`, `left: 50%`, and a transition. The project recreates the resulting centre-out border animation; it is not represented as the creator's exact complete original source.

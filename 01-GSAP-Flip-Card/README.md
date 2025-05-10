# Front-End Deep Practice: 01-GSAP-Flip-Card

## Features
- Interactive **3D card flip animation** triggered by custom buttons using **GSAP**.
- Uses `rotateY` and `rotateZ` transforms for a more dynamic flip effect than standard CSS flips.
- Smooth and customizable transitions with **GSAP easing functions** (`power2.in`, `power2.out`).
- Includes both a **front and back face**, each with distinct styling and content.
- **Buttons control direction**, letting users flip back and forth at will.
- Built with **pure HTML, CSS, and JavaScript** — no frameworks required.
- Fully responsive layout that fills the viewport and centers content using **Flexbox**.
- Styled with a **monospace UI**, subtle border accents, and consistent spacing.
- Uses **CSS `perspective` and `transform-style: preserve-3d`** for authentic 3D depth.

## Methods and Techniques Used
- **GSAP `.to()` Animations** control 3D rotation of the container element (`rotateY`, `rotateZ`).
- **CSS 3D Transforms** give depth and realism to the card flip effect.
- **Modular Event Listeners** provide clean separation of actions for "flip" and "flip back" buttons.
- **Backface Visibility** ensures that only one side of the card is visible at a time.
- **Responsive Flexbox Layout** centers content and adapts to any screen size.
- **Custom CSS Variables** (`--fg`, `--bg`) define foreground/background colors for easy theming.
- **Inline Rotation Compensation** (on `.back span`) ensures flipped text stays readable.
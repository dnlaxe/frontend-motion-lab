# Frontend Motion Lab: 02-Timeline-Entrance-Animation

## Features
- A rich, **multi-phase animation sequence** controlled by a single GSAP timeline.  
- Starts with a **scale-up and fade-in**, drawing attention to the element on load.  
- Includes full **360° rotation**, **background color shift**, and **vertical bounce**.  
- Executes a **3D flip (`rotateY`)** to add dimensionality.  
- Morphs from a square to a **circle**, then stretches into a **full-width bar**.  
- Finishes with a **text reveal** (`"Hello, world!"`) using GSAP’s `TextPlugin`.  
- Built with **vanilla HTML/CSS/JS** and styled using **CSS variables** for theming.  
- Uses a **monospace aesthetic**, minimal layout, and responsive design via flexbox.

## Methods and Techniques Used
- **GSAP Timeline (`gsap.timeline()`)** for ordered animation control.  
- **Transform Properties**: `scale`, `rotate`, `rotateY`, `borderRadius`, `width`, `height`.  
- **Yoyo & Repeat**: adds bounce and reverse-motion effects.  
- **Easing Functions**: `back.out`, `power2.out`, `sine.inOut` for natural motion timing.  
- **GSAP TextPlugin** for dynamic text rendering at the end of the sequence.  
- **CSS Flexbox Layout** for perfect centering on any screen size.  
- **CSS Custom Properties** (`--fg`, `--bg`) for centralized color management.  
- All animations fire automatically, forming a complete entrance interaction.
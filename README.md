# Simple Portfolio Website

## Overview
A clean, responsive personal portfolio website built with semantic HTML5, modern CSS, and a hint of vanilla JavaScript. It includes an About Me section, a projects showcase, and a contact form, all designed to be lightweight and easy to customize.

Key features:
- Responsive layout that adapts from mobile to desktop
- Accessible navigation with skip link and keyboard-friendly controls
- Clean visual design using CSS variables for quick theming
- About, Projects, and Contact sections ready for your content

## Setup
No build tools or dependencies are required.

Option 1: Open directly
1. Download this repository’s files.
2. Open index.html in any modern web browser.

Option 2: Serve locally (recommended for testing)
- Python 3: `python -m http.server 8000` then visit http://localhost:8000
- Node (serve): `npx serve` then follow the URL shown

## Usage
Customize content:
- Name/Brand: In index.html, replace “Your Name” in the header brand and the avatar initials (YN).
- About Me: Edit the heading and paragraph in the About section to describe yourself.
- Skills: Update the skill chips to reflect your stack.
- Projects: Replace placeholder project cards with your project titles, descriptions, and links (wrap cards in anchors if desired).
- Contact: Update the email address and social links. The form submit is a demo alert; connect it to your backend or a service like Formspree/Netlify Forms.

Style and theme:
- Colors and sizing are defined as CSS variables at the top of index.html. Adjust `--accent`, `--accent-2`, and `--panel` to quickly re-theme.
- The layout is responsive via CSS grid and flex; no changes needed for basic responsiveness.

Accessibility:
- A “Skip to content” link is provided.
- Interactive controls have focus styles and ARIA attributes. Keep these when customizing.

Deployment:
- Host the static files on GitHub Pages, Netlify, Vercel, or any static hosting provider. No special configuration is required.

## License
MIT License

Copyright (c) 2025 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
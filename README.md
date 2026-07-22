# Nick Playground

Static HTML pages and presentations.

## Devoxx UK 2026

Presentation: https://nicholascaplan.github.io/nick-playground/

The page is a single `index.html` file containing the slide data, rendering
templates and navigation logic. It uses vanilla JavaScript and Tailwind CSS
utility classes, with Tailwind, Font Awesome and Google Fonts loaded from CDNs.

### Page Features

- 18 slides, including MCP fundamentals, security controls and two technical appendices.
- Keyboard, touch-swipe, click-navigation and progress-bar navigation.
- Interactive slide content for the volunteer journey, keynote comparison, attack path and MCP controls.
- Browser fullscreen mode using the Fullscreen API.
- Responsive layout for presentation screens and smaller displays.
- External speaker, book-cover and profile images loaded from their supplied URLs.

### Deployment

GitHub Actions publishes the repository root to GitHub Pages whenever changes
are pushed to `main`. There is no build server or application backend.

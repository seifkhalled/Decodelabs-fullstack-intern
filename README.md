# DecodeLabs Project 1

A responsive frontend web application built with vanilla HTML5, CSS3, and JavaScript.

## Features

- **Responsive Layout**: Mobile-first design with breakpoints at 768px and 1024px
- **Fixed Navigation**: 50px navbar with hamburger menu for mobile
- **Hero Section**: Full-width with CTA buttons
- **Card Grid**: 3-column (desktop), 2-column (tablet), 1-column (mobile)
- **Sidebar**: 300px supplementary content panel (desktop only)
- **Interactive Components**: Tab switcher, accordion FAQ, modal dialog with form

## Design System

- **Colors**: 2025 Palette
  - Mocha Mousse: `#A8856F` (primary)
  - Ethereal Blue: `#A0D4E0` (accent)
  - Moonlit Grey: `#F2F0EA` (background)
- **Typography**: Montserrat (headings), Roboto (body) - loaded from Google Fonts
- **CSS Architecture**: Custom properties, CSS Grid, Flexbox

## Accessibility

- Skip-to-content link
- WCAG 2.1 AA compliant focus rings
- Semantic HTML5 elements
- ARIA attributes on interactive components
- Keyboard navigation support

## Sections

1. Hero - Main landing area
2. Features - 6-card grid showcase
3. About - Company stats
4. Contact - Call to action
5. Footer - Links and copyright

## Usage

Open `index.html` in any modern browser. No build step or dependencies required.

## File Structure

```
index.html  - Single self-contained file (CSS + JS embedded)
```
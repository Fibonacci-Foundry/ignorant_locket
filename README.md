# Fibonacci Foundry Website

A static website for the Fibonacci Foundry, a faith-based organization built on principles of decentralized authority, radical localism, and resistance to systemic corruption.

## Design Philosophy

- **Aesthetic**: Clean, functional, and humble design reflecting "Brilliance in the Basics"
- **Mathematics**: Incorporates the Fibonacci sequence and Golden Ratio in design ratios and layout
- **Typography**: Simple, readable fonts conveying professionalism without ostentation
- **Colors**: Grey and copper palette with earthy tones for authenticity and groundedness
- **Imagery**: Natural and cosmic imagery avoiding stock photos of people

## Technical Implementation

- **Static Site**: Pure HTML, CSS, and JavaScript for simplicity and performance
- **Responsive**: Mobile-first design with accessibility (WCAG 2.1 AA compliant)
- **Performance**: Lightweight, fast-loading pages optimized for all devices
- **Hosting**: Designed for GitHub Pages with custom domain support

## Features

- Responsive navigation with mobile hamburger menu
- Smooth scrolling with offset for fixed header
- Form handling with client-side validation
- Accessibility enhancements (skip links, keyboard navigation)
- Golden ratio and Fibonacci-based spacing and proportions
- CSS animations triggered by intersection observer
- Print-friendly styles

## Local Development

1. Clone the repository
2. Open `index.html` in a web browser
3. For development with live reload, use a simple HTTP server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (if you have http-server installed)
   npx http-server
   
   # PHP
   php -S localhost:8000
   ```

## Deployment

This site is configured for GitHub Pages deployment:

1. Push to the `main` branch
2. Enable GitHub Pages in repository settings
3. Set custom domain to `fibonaccifoundry.org` if desired

## Project Structure

```
├── index.html          # Main landing page
├── styles.css          # CSS with golden ratio-based design system
├── script.js           # JavaScript for interactivity and accessibility
└── README.md           # This file
```

## Design System

The website uses a design system based on the Golden Ratio (φ ≈ 1.618):

- **Spacing Scale**: 0.382rem, 0.618rem, 1rem, 1.618rem, 2.618rem, 4.236rem
- **Typography Scale**: Based on φ progression
- **Layout Proportions**: Grid systems using 1.618:1 ratios
- **Color Palette**: Copper (#B87333) as primary, with warm greys and earth tones

## Content Sections

1. **Hero**: "Brilliance in the Basics" with clear value proposition
2. **Mission**: Core values of growth, decentralized authority, and localism
3. **Principles**: Faith foundation, resistance to corruption, authentic community
4. **Community**: How to get involved and connect with others
5. **Contact**: Simple contact form and connection information

## Accessibility Features

- Semantic HTML structure
- Skip navigation links
- Keyboard navigation support
- ARIA labels where needed
- Color contrast meeting WCAG AA standards
- Responsive design for all screen sizes
- Print-friendly styles

## Performance Optimizations

- Minimal external dependencies (only Google Fonts)
- Optimized CSS with custom properties for consistency
- Efficient JavaScript with event delegation
- Compressed and optimized assets
- Fast-loading animations with `prefers-reduced-motion` support

---

*Built with integrity, designed with purpose.*

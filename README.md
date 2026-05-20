# DecodeLabs — Interactive Web Elements

A polished single-page frontend project built with pure **HTML**, **CSS**, and **JavaScript**.  
It demonstrates interactive UI behavior such as live counter updates, dynamic text changes, and light/dark theme switching without relying on any external framework.

## Overview

DecodeLabs is designed as a presentation-friendly project that focuses on:
- Clear visual hierarchy
- Responsive layout
- Real-time DOM manipulation
- Accessible, button-driven interactions
- A bold cartoon-brutalist visual style

The project is intentionally lightweight and easy to run locally in any modern browser.

## Features

- **Theme toggle** for switching between light and dark modes
- **Interactive counter** with increment, decrement, and reset actions
- **Dynamic content panel** that cycles through helpful design tips
- **Live interaction tracking** to show how many actions were performed
- **Responsive layout** optimized for desktop and mobile screens
- **Accessible live updates** using semantic HTML and `aria-live`

## Tech Stack

- **HTML5** — page structure and semantics
- **CSS3** — styling, responsive layout, and visual design
- **Vanilla JavaScript** — all interactive behavior and DOM updates

## Project Structure

```text
.
├── index.html
└── README.md
```

## How to Run

Since this is a static frontend project, no installation is required.

### Option 1 — Open directly
1. Download or clone the project.
2. Open `index.html` in your browser.

### Option 2 — Use a local server
If you want a smoother local development experience, run a simple static server:

```bash
npx serve .
```

Or use any other static hosting tool of your choice.

## Interaction Guide

### Theme Toggle
- Switches the entire page between light and dark mode
- Updates the button label and theme indicator dynamically

### Counter Playground
- **+1** increases the counter
- **-1** decreases the counter
- **Reset** returns the counter to zero

### Dynamic Content Panel
- **New Tip** cycles through a list of design and UX messages
- **Pulse Message** briefly changes the footer text
- **Focus Counter** scrolls smoothly to the counter section

## Accessibility Notes

This project includes:
- Semantic sections and articles
- Clear button labels
- Live regions for dynamic text updates
- Sufficient contrast and strong visual separation

## Browser Support

The project is compatible with all modern browsers that support:
- ES6 JavaScript
- CSS Grid
- `scrollIntoView`
- `prefers-color-scheme`

## Purpose

This page was created to demonstrate:
- DOM manipulation
- Interactive UI patterns
- Clean frontend structure
- A polished presentation-ready design

## License

This project can be used for educational, internship, or portfolio purposes unless otherwise specified by the project owner.

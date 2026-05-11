# Portfolio Homepage Design

## Overview
Personal portfolio site for Hadano Musashi (羽田野 武蔵) — clean, minimal, with light/dark mode.

## Tech Stack
- HTML5 + Tailwind CSS (CDN) + Vanilla JavaScript
- Single `index.html` + `assets/` directory
- Deployed via GitHub Pages

## Design Direction: Refined Minimal

### Color Palette
| Token | Light | Dark |
|-------|-------|------|
| Background | `#FAFAF8` | `#0F0F0F` |
| Text | `#1A1A1A` | `#E8E8E6` |
| Accent (Sage) | `#8B9E7E` | `#A3B895` |
| Muted | `#6B7280` | `#9CA3AF` |
| Border | `#E5E5E0` | `#262626` |

### Typography
- Headings: **Instrument Serif** (Google Fonts) — classic, dignified serif
- Body: **DM Sans** (Google Fonts) — clean sans-serif

### Layout
- Single-page vertical scroll, `max-w-3xl` centered
- 7 sections: Hero → About → Experience → Education → Research → Projects → Awards

### Sections
1. **Hero**: Centered name (large), title, one-liner, SNS icon links
2. **About**: Photo left, text right (age auto-calc JS, affiliation, hobbies)
3. **Experience**: Vertical timeline (date | content)
4. **Education**: Compact list
5. **Research**: Paper link cards ×2
6. **Projects**: Text-based descriptions with award badges
7. **Awards**: Chronological table

### Light/Dark Mode
- Toggle button (sun/moon icon) fixed top-right
- Toggles `dark` class on `<html>`
- Persists via `localStorage`

### Animations
- Intersection Observer: fade-in + `translateY(20px)` on each section
- Hover: subtle `opacity` + `transform` on links/cards
- `scroll-behavior: smooth`

### Responsive
- Mobile: 1-column, photo centered, simplified timeline
- Tablet/Desktop: centered layout with `max-w-3xl`

## Assets
- `assets/IMG_1385.jpg` — profile photo
- `assets/VORN_CHALLENGE/grand_prize.webp` — VORN award image
- `assets/VORN_CHALLENGE/finalist04.webp` — VORN finalist image

# US Debt Timeline — Design System

Professional, light-mode design system for the living curriculum timeline.  
Inspired by the clarity of America.gov and the type principles of the U.S. Web Design System (USWDS).

## Principles
- Clean white background, high contrast, generous whitespace
- Public Sans throughout (light weight on large headings to approximate America.gov)
- Gold and red used only as subtle timeline line accents — not as general accents
- Light mode only
- No timeline dots (clean vertical line only)
- Components defined so future changes stay consistent

## Colors
| Token | Value | Use |
|-------|-------|-----|
| `--color-bg` | `#ffffff` | Page background |
| `--color-text` | `#000c1f` | Primary text |
| `--color-text-muted` | `#3d4551` | Secondary text |
| `--color-border` | `#dfe1e2` | Borders, dividers |
| `--color-surface` | `#f8f9fa` | Subtle backgrounds |
| `--color-primary` | `#005ea2` | Links, active filters |
| `--color-gold` | `#ffbe2e` | Timeline line accent |
| `--color-red` | `#d83933` | Timeline line accent |
| `--color-green` | `#00a91c` | Future accent |

## Typography
- **Body / UI / Headings**: Public Sans
- Large headings use light weight (300) and tight tracking to echo America.gov

## Components defined
- Header (large light heading)
- Filter controls (pill buttons)
- Timeline line (no dots)
- Cards (hover, open state)
- Age tabs
- Facts callouts
- Footer

## Usage
Link `design-system.css` in any page:

```html
<link rel="stylesheet" href="design-system.css">
```

All component classes (`.timeline`, `.event`, `.card`, `.controls`, etc.) are styled by the system. Future iterations should extend these tokens and classes rather than introducing one-off styles.

## Tweaking
Adjust tokens in `:root` inside `design-system.css`. Component rules follow the tokens, so most visual changes require only token edits.

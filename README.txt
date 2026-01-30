# gpv-skin starter files (DS4 outline-only)

This zip contains two approaches:

## A) Minimal outline-only DS4 overlay (recommended)
- File: `minimal-ds4.css`
- Use with Gamepad Viewer **custom CSS mode** (`css=`). Do NOT add `s=5`.

Example URL (replace HOSTED_CSS_URL with your hosted URL):
https://gamepadviewer.com/?p=1&css=HOSTED_CSS_URL

## B) Outline-SVG body + GPV DS4 positions (experimental)
- File: `outline-svg-edit.css`
- File: `ds4-outline.svg` (stylized placeholder; replace with your own DS4 outline SVG)
- Use with **edit mode** (`editcss=`) so GPV keeps DS4 DOM positions.

Example URL:
https://gamepadviewer.com/?p=1&s=5&editcss=HOSTED_CSS_URL

Notes:
- `ds4-outline.svg` is NOT an exact Sony DS4 outline. Replace anytime.
- For hosting, GitHub Pages or any static host works. If using GitHub, prefer Pages or a CDN.

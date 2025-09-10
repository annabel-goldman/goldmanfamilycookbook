# Goldman Family Cookbook

A digital viewer for the Goldman family recipe collection.

## Features

**Performance**
- Preloads images for smooth page transitions
- Shows loading indicators while images load
- Handles large SVG files efficiently (2-3MB each)

**Navigation**
- Arrow buttons for page navigation
- Keyboard shortcuts: arrow keys (left/right), A/D keys
- Touch and swipe gestures on mobile
- Home/End keys jump to first/last page
- Escape key returns to welcome screen

**Mobile Support**
- Works on desktop, tablet, and mobile devices
- Responsive layout adapts to screen size
- Touch-friendly controls

**Interface**
- Family cookbook styling
- Progress bar tracks reading position
- Page counter display
- Smooth page transitions

## GitHub Pages Setup

1. Upload the files to your repository with `index.html` in the root directory
2. Enable GitHub Pages in repository settings:
   - Go to Settings > Pages
   - Set source to "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Save changes
3. The site will be available at `https://[username].github.io/[repository-name]`

## File Structure

```
GoldmanFamilyCookBook/
├── index.html          # Main cookbook viewer (this file)
├── README.md           # This file
└── svgs/
    ├── Icon.png        # Favicon
    ├── 1.svg           # Page 1
    ├── 2.svg           # Page 2
    └── ...             # Pages 3-29
```

## Technical Details

- Built with HTML, CSS, and JavaScript (no external dependencies)
- Works offline after initial load
- Designed for GitHub Pages hosting
- Preloads adjacent pages for faster navigation
- Responsive design optimized for all devices

## Navigation Controls

| Action | Method |
|--------|--------|
| Next page | Click right arrow, `→` key, `D` key, swipe left |
| Previous page | Click left arrow, `←` key, `A` key, swipe right |
| First page | `Home` key |
| Last page | `End` key |
| Welcome screen | `Escape` key |
| Start reading | Click "Start Cooking!" or `Enter` key |

Happy cooking! 
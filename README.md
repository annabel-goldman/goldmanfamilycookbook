# Goldman Family Cookbook

A beautiful, fast-loading digital cookbook viewer for the Goldman family recipe collection.

## Features

✨ **Performance Optimized**
- Smart image preloading for smooth navigation
- Loading indicators for better user experience
- Optimized for large SVG files (2-3MB each)

🎯 **Navigation**
- Click arrow buttons to navigate
- Keyboard shortcuts: `←` `→` arrow keys, `A` `D` keys
- Touch/swipe support on mobile devices
- `Home`/`End` keys to jump to first/last page
- `Escape` to return to welcome screen

📱 **Responsive Design**
- Works beautifully on desktop, tablet, and mobile
- Adaptive layout and controls
- Touch-friendly interface

🎨 **Modern UI**
- Beautiful family cookbook theme
- Progress bar showing reading progress
- Page counter
- Smooth animations and transitions

## GitHub Pages Setup

1. **Upload your files**: Make sure this `index.html` file is in the root directory of your repository
2. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"
3. **Your site will be available at**: `https://[your-username].github.io/[repository-name]`

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

- Pure HTML, CSS, and JavaScript - no dependencies
- Works offline once images are cached
- Optimized for GitHub Pages hosting
- Preloads adjacent pages for instant navigation
- Mobile-first responsive design

## Navigation Controls

| Action | Method |
|--------|--------|
| Next page | Click right arrow, `→` key, `D` key, swipe left |
| Previous page | Click left arrow, `←` key, `A` key, swipe right |
| First page | `Home` key |
| Last page | `End` key |
| Welcome screen | `Escape` key |
| Start reading | Click "Start Cooking!" or `Enter` key |

Enjoy browsing the family recipes! 👨‍🍳👩‍🍳 
# The Swanson Sisters

A beautiful, modern website showcasing baking videos and recipes created by two sisters.

## Features

- Video-first design with YouTube embeds
- Year-based filtering
- Responsive design
- Clean, modern UI/UX
- Fast and lightweight

## Tech Stack

- HTML5
- CSS3 (Modern, no frameworks)
- Vanilla JavaScript
- Hosted on Vercel

## Local Development

1. Clone the repository
2. Start a local server:
   ```bash
   python3 -m http.server 8000
   ```
3. Visit `http://localhost:8000`

## Deployment

This site is automatically deployed to Vercel. Any push to the main branch will trigger a new deployment.

## Structure

- `index.html` - Homepage with video grid
- `style.css` - Main stylesheet
- `recipe.css` - Recipe page styles
- `script.js` - Interactive JavaScript
- `20XX-X.html` - Individual recipe pages
- `image/` - Recipe photos and assets

## Adding New Videos

1. Add the video thumbnail to `image/projects/`
2. Create a new recipe page (e.g., `2025-1.html`)
3. Update `index.html` to include the new video card
4. Commit and push changes

---

Made with love by The Swanson Sisters 💕

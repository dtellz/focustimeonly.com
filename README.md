# Focus Time Only - Landing Page

This is the landing page for the Focus Time Only iOS app, a productivity app that reached the top 5 in Spain.

## Project Overview

This is a simple static HTML/CSS website designed to showcase the Focus Time Only app, its features, and achievements. The site is ready to be deployed to Netlify.

## Features

- Responsive design that works on all devices
- Modern UI with gradient effects
- Video showcase section
- Features section highlighting app capabilities
- Achievement section showcasing top 5 ranking
- App Store download button

## Structure

- `index.html` - Main HTML file
- `styles.css` - CSS styling
- `assets/` - Contains media files:
  - `promo_video.MP4` - Promotional video
  - `top5_chart.PNG` - Screenshot of app ranking
  - `app-store-badge.svg` - App Store download button

## Deployment Instructions

### Deploy to Netlify

1. Create a Netlify account if you don't have one
2. From the Netlify dashboard, click "Add new site" > "Import an existing project"
3. Connect to your Git provider (GitHub, GitLab, etc.)
4. Select the repository containing this project
5. Configure build settings (not required for this static site)
6. Click "Deploy site"

### Manual Deployment

1. Run `netlify deploy` from the project directory (requires Netlify CLI)
2. Follow the prompts to complete deployment

## Local Development

To preview the site locally, you can use any simple HTTP server:

```bash
# Using Python
python -m http.server

# Or using Node.js with http-server
npx http-server
```

Then open your browser to `http://localhost:8000` or the port specified by your server.

## Customization

Feel free to modify the colors in the CSS variables at the top of the `styles.css` file to match your brand preferences.

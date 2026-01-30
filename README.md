# Personal Portfolio Website

A minimalist personal landing page for **Manish M. Shivanandhan** — Engineer, Product Manager, and Tech Writer.

🌐 **Live Site**: [manishshivanandhan.com](https://manishshivanandhan.com)

## Overview

A clean, responsive single-page portfolio showcasing professional background and providing quick access to various platforms and publications. Features a terminal-inspired design aesthetic with a blinking cursor effect.

## Features

- **Responsive Design** — Mobile-first layout that adapts seamlessly across devices
- **Profile Section** — Photo, name, and professional summary
- **Publication Links** — Direct links to FreeCodeCamp and DataScienceCollective articles
- **Social Integration** — Quick access buttons for Newsletter, YouTube, and LinkedIn
- **Contact Form** — Integrated YouForm widget for visitor inquiries
- **Analytics** — Google Analytics tracking

## Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| CSS3 | Custom styling & animations |
| Bootstrap 5.2 | Grid system & responsive utilities |
| Font Awesome 6 | Icons |
| Google Fonts | Typography (Roboto Slab, Ubuntu Mono) |
| jQuery | DOM manipulation |
| YouForm | Contact form widget |
| Google Analytics | Site analytics |

## Project Structure

```
website/
├── index.html      # Main HTML file
├── style.css       # Custom styles
├── dp.jpeg         # Profile photo
├── CNAME           # Custom domain configuration
└── README.md       # This file
```

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/manishmshiva/website.git
   ```

2. Open `index.html` in your browser, or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

3. Visit `http://localhost:8000`

## Deployment

This site is deployed on **GitHub Pages** with a custom domain. The `CNAME` file configures the custom domain `manishshivanandhan.com`.

To deploy your own version:
1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Update the `CNAME` file with your domain (or remove it to use `username.github.io`)

## License

© Manish M. Shivanandhan. All Rights Reserved.

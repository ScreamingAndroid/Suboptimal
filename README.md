# Personal Portfolio Website

A modern, clean, and responsive personal portfolio website built with HTML, CSS, and vanilla JavaScript.

## Features

- 📱 Fully responsive design
- 🎨 Clean, modern UI with customizable color scheme
- ⚡ Fast-loading with no heavy frameworks
- 📧 Contact form (requires backend integration)
- 🎯 Smooth scrolling navigation
- 📦 Easy to customize

## Quick Start

1. Clone this repository
2. Edit the content in `index.html` (look for `<!-- EDIT -->` comments)
3. Customize colors in `style.css` (CSS variables at the top)
4. Add your profile photo to the project and update the image source
5. Open `index.html` in your browser

## Customization Guide

### Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --background: #f8f9fa;
    --text-primary: #2c3e50;
    --text-secondary: #5a6c7d;
    --accent: #3498db; /* Change this! */
    --white: #ffffff;
    --border: #e1e8ed;
}
```

### Content
Look for `<!-- EDIT -->` comments in `index.html` to update:
- Your name and bio
- Projects and descriptions
- Skills
- Social links

### Contact Form
The contact form currently shows a demo message. To make it functional:
- Integrate with a backend service (Formspree, EmailJS, etc.)
- Or update the form handler in `script.js`

## Deployment

### GitHub Pages
1. Push your code to GitHub
2. Go to Settings > Pages
3. Select your branch and save
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify / Vercel
Simply drag and drop your project folder or connect your GitHub repository.

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Free to use for personal projects.

---

Built with ❤️ using HTML, CSS, and JavaScript

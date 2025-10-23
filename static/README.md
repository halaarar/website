# Hala Arar - Portfolio Website

A clean, professional portfolio website built with pure HTML, CSS, and JavaScript. No build tools or frameworks required.

## Features

- ✨ Responsive design for mobile and desktop
- 🎨 Modern, professional aesthetic
- 📱 Mobile-friendly navigation
- 🎯 SEO optimized
- ⚡ Fast loading (no build process)
- 🎭 Smooth animations and transitions

## Structure

```
static/
├── index.html          # Home page
├── projects.html       # Projects showcase
├── about.html          # About/journey page
├── resume.html         # Skills and education
├── contact.html        # Contact form
├── styles.css          # All styles
├── script.js           # Interactive features
├── assets/             # Images and files
│   ├── profile.jpg     # Profile photo
│   └── resume.pdf      # Downloadable resume
└── README.md           # This file
```

## GitHub Pages Deployment

### Option 1: Direct Upload
1. Create a new repository on GitHub
2. Upload all files from the `static/` folder to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click Save
7. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: GitHub Desktop
1. Create a new repository
2. Clone it to your computer
3. Copy all files from `static/` to the repository folder
4. Commit and push
5. Enable GitHub Pages in Settings

### Option 3: Command Line
```bash
# Create new repo on GitHub first, then:
git clone https://github.com/yourusername/your-repo.git
cd your-repo
# Copy files from static/ folder here
git add .
git commit -m "Initial portfolio commit"
git push origin main
# Enable Pages in GitHub Settings
```

## Customization

### Update Personal Information
1. Replace `assets/profile.jpg` with your photo
2. Add your resume PDF to `assets/resume.pdf`
3. Update all placeholder links:
   - GitHub: `https://github.com/halaarar` → your GitHub
   - LinkedIn: `https://linkedin.com/in/halaarar` → your LinkedIn
   - Email: `hala.arar@example.com` → your email

### Modify Content
- Edit the HTML files to update text, projects, and timeline
- Adjust colors in `styles.css` (see CSS variables at top)
- Update project links and descriptions

### Colors
Change the color scheme by editing CSS variables in `styles.css`:

```css
:root {
  --color-primary: hsl(222, 47%, 35%);    /* Navy blue */
  --color-accent: hsl(174, 62%, 75%);     /* Pastel teal */
  /* ... other colors */
}
```

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Contact Form

The contact form currently logs to console. To make it functional:

1. **Use a form service** (Formspree, Netlify Forms, etc.)
2. **Add backend** (if you have server access)
3. **Use mailto** (simple but limited):
   ```html
   <form action="mailto:your@email.com" method="post" enctype="text/plain">
   ```

## License

Free to use and modify for your own portfolio.

## Credits

Designed for Hala Arar - Data Scientist

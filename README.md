# Personal Website

A modern, responsive personal website built with HTML, CSS, and JavaScript. This website showcases your professional experience, education, skills, and projects.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth scrolling and animations
- 🎯 Easy to customize
- 🚀 Ready for GitHub Pages deployment

## Customization Guide

### 1. Update Personal Information

Edit `index.html` and update the following sections:

- **Hero Section**: Update your name, title, and description
- **About Section**: Add your personal bio
- **Experience**: Add your work experience
- **Education**: Add your educational background
- **Skills**: Update with your technical skills
- **Projects**: Add your portfolio projects
- **Contact**: Update email and social media links

### 2. Update Social Links

In the hero section, update the social media links:

```html
<a href="https://github.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer">
<a href="https://linkedin.com/in/YOUR_PROFILE" target="_blank" rel="noopener noreferrer">
<a href="mailto:your.email@example.com">
```

### 3. Update Resume PDF

Replace `PranitChawla_Resume_11_25.pdf` with your own resume PDF file, or update the filename in the HTML if you use a different name.

### 4. Customize Colors

Edit `styles.css` and modify the CSS variables at the top:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --primary-dark: #1e40af;        /* Darker shade */
    --secondary-color: #64748b;     /* Secondary color */
    /* ... other colors */
}
```

### 5. Add Your Projects

Update the projects section with your actual projects, including:
- Project name
- Description
- Technologies used
- Links to GitHub and live demos

## Deployment to GitHub Pages

### Option 1: Using GitHub Repository Settings (Recommended)

1. **Create a GitHub Repository**
   - Go to GitHub and create a new repository
   - Name it `yourusername.github.io` (replace `yourusername` with your GitHub username)
   - Make it public

2. **Initialize Git and Push**
   ```bash
   cd personal_website
   git init
   git add .
   git commit -m "Initial commit: Personal website"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on **Settings**
   - Scroll down to **Pages** section
   - Under **Source**, select `main` branch
   - Click **Save**
   - Your site will be live at `https://yourusername.github.io` in a few minutes

### Option 2: Using a Custom Domain

If you want to use a custom domain:

1. Follow Option 1 steps above
2. In the GitHub Pages settings, add your custom domain
3. Update your domain's DNS settings to point to GitHub Pages
4. Add a `CNAME` file in the repository root with your domain name

### Option 3: Using a Different Repository Name

If you want to use a different repository name (not `username.github.io`):

1. Create a repository with your desired name
2. Push your code to the `main` branch
3. In Settings → Pages, select `main` branch and `/ (root)` folder
4. Your site will be at `https://yourusername.github.io/repository-name`

## File Structure

```
personal_website/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript for interactivity
├── README.md           # This file
├── .nojekyll           # Disable Jekyll processing
├── 404.html            # Custom 404 page
└── PranitChawla_Resume_11_25.pdf  # Your resume PDF
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal use.

## Credits

- Fonts: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)
- Icons: [Font Awesome](https://fontawesome.com/)

---

**Note**: Remember to update all placeholder content with your actual information before deploying!

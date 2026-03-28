# Tarun Bagre - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases projects, skills, experience, and provides a way for potential clients or employers to get in touch.

## Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **Performance Optimized**: Fast loading with optimized code
- **Easy to Customize**: Well-structured code that's easy to modify

## Getting Started

### Prerequisites

- A modern web browser
- A text editor (VS Code recommended)
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. Download or clone this repository to your local machine
2. Open the `index.html` file in your web browser
3. That's it! The portfolio is ready to view

### File Structure

```
tarun-portfolio/
├── index.html          # Main HTML file
├── style.css           # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization

### Personal Information

1. **Name and Title**: Edit the hero section in `index.html`
   ```html
   <h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
   <p class="hero-subtitle">Your Title Here</p>
   ```

2. **About Section**: Update your bio and stats in the about section
   ```html
   <p>Your bio here...</p>
   ```

3. **Contact Information**: Update your contact details
   ```html
   <span>your.email@email.com</span>
   <span>+91 12345 67890</span>
   <span>Your City, Country</span>
   ```

### Projects

Add or modify projects in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-your-icon"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="project-link">Live Demo</a>
            <a href="your-github-link" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

### Skills

Update your skills in the skills section:

```html
<div class="skill-category">
    <h3>Category Name</h3>
    <div class="skills-list">
        <span class="skill-item">Skill 1</span>
        <span class="skill-item">Skill 2</span>
        <!-- Add more skills -->
    </div>
</div>
```

### Colors and Styling

To change the color scheme, modify these CSS variables in `style.css`:

```css
/* Primary color */
#2563eb -> your-primary-color

/* Gradient colors */
#667eea, #764ba2 -> your-gradient-colors

/* Accent color */
#fbbf24 -> your-accent-color
```

### Social Links

Update social media links in the contact section:

```html
<a href="your-linkedin-url" class="social-link"><i class="fab fa-linkedin"></i></a>
<a href="your-github-url" class="social-link"><i class="fab fa-github"></i></a>
<a href="your-twitter-url" class="social-link"><i class="fab fa-twitter"></i></a>
<a href="your-instagram-url" class="social-link"><i class="fab fa-instagram"></i></a>
```

## Deployment

### Option 1: GitHub Pages (Free)

1. Create a GitHub repository
2. Upload your files to the repository
3. Go to repository Settings > Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)

1. Create an account on [Netlify](https://netlify.com)
2. Drag and drop your project folder to Netlify
3. Your site will be deployed instantly with a custom URL

### Option 3: Vercel (Free)

1. Create an account on [Vercel](https://vercel.com)
2. Import your project from GitHub
3. Your site will be deployed automatically

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Performance

The portfolio is optimized for performance with:
- Minimal JavaScript
- Optimized CSS
- Lazy loading (for future image additions)
- Smooth animations that don't impact performance

## Contributing

If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue.

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing this portfolio or have questions, feel free to:
- Open an issue on GitHub
- Contact me through the portfolio contact form

---

**Made with ❤️ by Tarun Bagre**

*Feel free to use this portfolio template for your own website. Just remember to customize it with your own information!*
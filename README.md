# Modern Portfolio Website

A beautiful, responsive portfolio website built with HTML, CSS, and JavaScript. Features a modern design with smooth animations, mobile-friendly navigation, and interactive elements.

## Features

- 🎨 **Modern Design**: Clean and professional layout with gradient backgrounds
- 📱 **Responsive**: Fully responsive design that works on all devices
- ⚡ **Smooth Animations**: CSS animations and JavaScript interactions
- 🧭 **Navigation**: Fixed navigation with smooth scrolling
- 📝 **Contact Form**: Functional contact form with validation
- 🎯 **Interactive Elements**: Hover effects and dynamic content
- 🌟 **Loading Animation**: Professional preloader
- 📊 **Skills Section**: Organized skill categories with icons
- 💼 **Projects Showcase**: Project cards with technology tags

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Getting Started

1. **Download or clone** the files to your local machine
2. **Open `index.html`** in your web browser
3. **Customize** the content to match your information
4. **Deploy** to your preferred hosting service

## Customization Guide

### Personal Information

Update the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<h2 class="hero-subtitle">Frontend Developer</h2>
<p class="hero-description">
    I create beautiful, responsive, and user-friendly web experiences. 
    Passionate about clean code and modern design.
</p>
```

#### About Section
```html
<p>
    I'm a passionate frontend developer with a strong foundation in modern web technologies. 
    I love creating intuitive user interfaces and bringing designs to life with clean, efficient code.
</p>
```

#### Statistics
```html
<div class="stat">
    <h3>2+</h3>
    <p>Years Experience</p>
</div>
<div class="stat">
    <h3>20+</h3>
    <p>Projects Completed</p>
</div>
<div class="stat">
    <h3>15+</h3>
    <p>Happy Clients</p>
</div>
```

### Projects

Replace the project cards with your own projects:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-laptop"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Description of your project and what technologies you used.</p>
        <div class="project-tech">
            <span class="tech-tag">React</span>
            <span class="tech-tag">Node.js</span>
            <span class="tech-tag">MongoDB</span>
        </div>
        <div class="project-links">
            <a href="your-live-demo-url" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="your-github-url" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
        </div>
    </div>
</div>
```

### Skills

Update the skills section with your actual skills:

```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <div class="skill-item">
            <i class="fab fa-html5"></i>
            <span>HTML5</span>
        </div>
        <!-- Add more skills -->
    </div>
</div>
```

### Contact Information

Update your contact details:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, Country</span>
</div>
```

### Social Links

Update your social media links:

```html
<div class="social-links">
    <a href="your-github-url" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="your-linkedin-url" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <!-- Add more social links -->
</div>
```

## Styling Customization

### Colors

The main color scheme is defined in `styles.css`. You can customize:

- **Primary Blue**: `#2563eb`
- **Gradient Colors**: `#667eea` to `#764ba2`
- **Accent Yellow**: `#fbbf24`
- **Text Colors**: Various shades of gray

### Fonts

The website uses the Inter font family. You can change it by updating the Google Fonts link in the HTML head:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

Then update the font-family in CSS:

```css
body {
    font-family: 'YourFont', sans-serif;
}
```

## Adding Images

### Profile Picture

Replace the placeholder in the hero section:

```html
<div class="hero-image">
    <img src="path/to/your/profile-image.jpg" alt="Your Name" class="profile-image">
</div>
```

Add corresponding CSS:

```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}
```

### Project Images

Replace project placeholders with actual screenshots:

```html
<div class="project-image">
    <img src="path/to/project-screenshot.jpg" alt="Project Name" class="project-screenshot">
</div>
```

Add CSS:

```css
.project-screenshot {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

## Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Upload your files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify

1. Drag and drop your folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. You'll get a custom URL

### Vercel

1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Deploy automatically on every push
3. Get a custom domain

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. **Optimize Images**: Compress images before uploading
2. **Minify CSS/JS**: Use minified versions for production
3. **CDN**: Use CDN for external libraries
4. **Lazy Loading**: Implement lazy loading for images
5. **Caching**: Set up proper caching headers

## Customization Tips

1. **Keep it Simple**: Don't overcrowd with too many elements
2. **Consistent Branding**: Use consistent colors and fonts
3. **Quality Content**: Write compelling project descriptions
4. **Regular Updates**: Keep your portfolio current
5. **Test Responsiveness**: Check on different devices

## Support

If you need help customizing your portfolio:

1. Check the HTML comments for guidance
2. Review the CSS classes for styling options
3. Test changes in a development environment
4. Use browser developer tools for debugging

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding! 🚀**


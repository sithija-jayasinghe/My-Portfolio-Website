# Harshana Jayasinghe - Portfolio Website

A modern, animated portfolio website showcasing my work as a Full-Stack Software Engineer. Built with pure HTML, CSS, and vanilla JavaScript - no frameworks required.

![Portfolio Preview](https://via.placeholder.com/800x400/5f9ea0/FFFFFF?text=Portfolio+Preview)

## ✨ Features

### Visual Effects
- **Animated Preloader** - Elegant letter-by-letter text animation on page load
- **Custom Cursor** - Interactive cursor that expands on hover over clickable elements
- **Floating Particles** - 30 animated particles that float upward with glowing effects
- **Animated Background Grid** - Subtle moving grid pattern for depth
- **Scroll Progress Bar** - Gradient progress indicator at the top of the page
- **3D Tilt Effect** - Project cards tilt in 3D based on mouse position
- **Shimmer Effect** - Light shimmer animation passes over cards on hover
- **Gradient Text** - Hero title features a gradient color transition
- **Smooth Animations** - Hardware-accelerated transitions throughout

### Interactive Elements
- **Theme Toggle** - Switch between light and dark modes with rotating icon animation
- **Scroll Reveal** - Elements fade in and slide up as you scroll
- **Animated Navigation** - Nav links with sliding underline effects
- **Button Ripple Effect** - CTA buttons with expanding circle hover effect
- **Frosted Glass Header** - Header with backdrop blur that gains shadow on scroll
- **Animated Arrows** - Repository links with sliding arrow animations

### Responsive Design
- Fully responsive layout that works on all devices
- Mobile-optimized with simplified effects for better performance
- Flexible grid system for project cards
- Fluid typography using CSS clamp()

## 🚀 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Advanced animations, transitions, and effects
- **Vanilla JavaScript** - No frameworks or libraries
- **Google Fonts** - Space Grotesk font family
- **CSS Custom Properties** - Theme variables for easy customization

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # All styles and animations
├── script.js           # JavaScript functionality
└── assets/
    ├── scl.png        # Nalanda College project image
    └── burger.png     # POS System project image
```

## 🎨 Color Scheme

### Light Mode
- Background: `#f8f8f8`
- Text: `#1a1a1a`
- Primary: `#5f9ea0` (Cadet Blue)
- Secondary: `#333333`

### Dark Mode
- Background: `#1a1a1a`
- Text: `#f0f0f0`
- Primary: `#87ceeb` (Sky Blue)
- Secondary: `#aaaaaa`

## 🛠️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/sithija-jayasinghe/portfolio.git
   ```

2. **Navigate to project directory**
   ```bash
   cd portfolio
   ```

3. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

4. **View the site**
   - Open `http://localhost:8000` in your browser

## 📝 Customization

### Changing Colors
Edit the CSS custom properties in the `:root` section:

```css
:root {
  --color-bg: #f8f8f8;
  --color-text: #1a1a1a;
  --color-primary: #5f9ea0;
  --color-secondary: #333333;
  --color-border: #e0e0e0;
}
```

### Adding Projects
Add new project cards in the `#work` section:

```html
<div class="project-card reveal custom-cursor-target">
    <img src="path/to/image.png" alt="Project Description">
    <div class="project-info">
        <h3>Project Title</h3>
        <p>Project description goes here.</p>
        <a href="#" class="view-link custom-cursor-target">Go To Repository</a>
    </div>
</div>
```

### Modifying Animations
Animation timings can be adjusted in the CSS:

```css
.reveal {
    transition: opacity 1s cubic-bezier(0.17, 0.84, 0.44, 1),
                transform 1s cubic-bezier(0.17, 0.84, 0.44, 1);
}
```

### Particle Settings
Modify particle count and animation in JavaScript:

```javascript
function createParticles() {
    for (let i = 0; i < 30; i++) { // Change particle count here
        // Particle creation logic
    }
}
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

**Note:** Custom cursor is disabled on mobile devices for better user experience.

## ⚡ Performance

- Hardware-accelerated animations using `transform` and `opacity`
- Lazy loading of scroll animations with Intersection Observer API
- Optimized particle system
- Minimal JavaScript for fast load times
- CSS animations for smooth 60fps performance

## 🎯 Features Breakdown

### Preloader (1.5s)
Displays animated name letter-by-letter before revealing the main content.

### Custom Cursor
- 15px default size with primary color border
- Expands to 40px with fill on hover
- Smooth easing animation (0.1 factor)
- Automatically hidden on mobile

### Scroll Reveal
- Elements fade in when they enter viewport
- Uses Intersection Observer for performance
- Staggered delays for child elements
- Threshold: 10% visibility required

### Theme Toggle
- Saves preference to localStorage
- Respects system preference on first visit
- Smooth 0.5s transition between themes
- Rotating icon animation on hover

## 📄 Sections

1. **Hero** - Large animated title with call-to-action
2. **Work** - Grid of featured projects with hover effects
3. **About** - Skills and experience overview
4. **Contact** - Email and social media links

## 🔗 Links

- **LinkedIn:** [Sithija Harshana Jayasinghe](https://www.linkedin.com/in/sithija-harshana-jayasinghe-552822340/)
- **GitHub:** [sithija-jayasinghe](https://github.com/sithija-jayasinghe)
- **Email:** hello@example.com

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) by Google Fonts
- Inspiration: Modern web design trends and minimalist aesthetics
- Built with attention to detail and user experience

## 📈 Future Enhancements

- [ ] Add blog section
- [ ] Implement project filtering
- [ ] Add contact form with backend
- [ ] Include more projects
- [ ] Add testimonials section
- [ ] Implement multi-language support
- [ ] Add loading animations for images

## 🐛 Known Issues

- Custom cursor may have slight lag on lower-end devices (by design for smooth animation)
- Particles disabled on mobile for performance

## 💡 Tips

- **Best viewed on desktop** for full animation experience
- **Dark mode** recommended for the best visual effects
- **Use Chrome or Firefox** for optimal performance
- Images should be optimized (WebP format recommended)

---

**Made with ❤️ by Harshana Jayasinghe**

*Last Updated: November 2025*

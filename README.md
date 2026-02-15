# Manohar NM - Portfolio Website

## Project Description

A modern, responsive portfolio website showcasing professional skills and projects. Built with HTML5, CSS3, and vanilla JavaScript, demonstrating full-stack web development capabilities with focus on user experience and responsive design.

### Key Features
- **Responsive Design**: Desktop, tablet, and mobile optimized
- **Modern UI**: Professional gradient design with smooth animations
- **Interactive Navigation**: Smooth scrolling and mobile burger menu
- **Project Showcase**: Grid layout for multiple projects
- **Professional About Section**: Comprehensive background information
- **Contact Section**: Easy visitor engagement

---

## Technology Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic markup and structure |
| **CSS3** | Styling, animations, and responsive design |
| **JavaScript** | Interactive features and smooth scrolling |

---

## Setup Instructions

### Quick Start
```bash
# Clone repository
git clone https://github.com/Manohar-NM/week1-portfolio.git
cd week1-portfolio

# Start local server with Python
python -m http.server 8000

# Open http://localhost:8000 in browser
```

### Project Structure
```
week1-portfolio/
├── index.html          # Main portfolio page
├── css/
│   └── style.css      # All styling and animations
├── js/
│   └── navigation.js  # Interactive features
└── README.md          # Documentation
```

---

## Features Detailed

### Hero Section
- Full viewport height with purple-to-violet gradient
- Professional introduction and tagline
- Clear call-to-action button

### About Me Section
Highlights professional strengths:
- **Problem-Solving**: Rapid analysis and efficient solutions
- **Technical Skills**: Full-stack web development expertise
- **Collaboration**: Dependable team player mentality
- **Quality**: Commitment to highest standards and timelines

### Projects Gallery
- Responsive grid (auto-fit with 300px minimum)
- Individual project cards with hover effects
- Technology stack information displayed
- Smooth animations on interaction

### Interactive Features
- **Smooth Scrolling**: Click navigation links for smooth page scroll
- **Mobile Menu**: Burger menu appears on screens < 768px
- **Header Effects**: Dynamic shadow on scroll
- **Touch Friendly**: All features work on mobile/tablet

---

## Responsive Breakpoints

| Device | Width | Adjustments |
|--------|-------|------------|
| Desktop | 1200px+ | Full layout |
| Tablet | 768px-1199px | Grid adjusts |
| Mobile | <768px | Burger menu, single column |
| Small Mobile | <480px | Smaller fonts/buttons |

---

## How to Customize

### Change Colors
Edit gradient in `css/style.css`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Update Contact Email
In `index.html`, change:
```html
<a href="mailto:your-email@example.com" class="btn">Get In Touch</a>
```

### Add New Projects
Insert in projects section:
```html
<div class="project-card">
    <div class="project-placeholder"><span>Your Project</span></div>
    <h3>Project Title</h3>
    <p>Built with Technology Stack</p>
</div>
```

---

## Browser Compatibility

| Browser | Status |
|---------|--------|
| Chrome | ✅ Full Support |
| Firefox | ✅ Full Support |
| Safari | ✅ Full Support |
| Edge | ✅ Full Support |
| IE 11 | ⚠️ Limited |

---

## Performance

- ⚡ Fast load times (no external dependencies)
- 📱 Mobile-first responsive design
- ♿ Semantic HTML structure
- 🎨 Hardware-accelerated CSS animations

---

## Deployment Options

### GitHub Pages (Free & Recommended)
1. Go to Settings → Pages
2. Select `main` branch as source
3. Site will be live at `https://Manohar-NM.github.io/week1-portfolio`

### Alternative Hosting
- **Netlify**: Drag & drop deployment
- **Vercel**: Automatic Git deployments
- **Web Host**: Any standard web hosting service

---

## File Details

**index.html** (86 lines)
- Header with sticky navigation
- Hero section with introduction
- About me with professional description
- Project showcase grid
- Contact section
- Footer

**css/style.css** (280+ lines)
- Global styles and CSS reset
- Mobile-first responsive design
- Gradient backgrounds and animations
- Flexible grid layout
- Hover effects and transitions

**js/navigation.js** (45+ lines)
- Mobile burger menu toggle
- Smooth anchor scrolling
- Header scroll effects
- Auto-close mobile menu on link click

---

## Future Enhancements

- [ ] Add real project images
- [ ] Implement contact form
- [ ] Add blog section
- [ ] Dark mode toggle
- [ ] Social media links
- [ ] SEO optimization
- [ ] Google Analytics integration

---

## Screenshots & Walkthrough

### Hero Section
Purple gradient background with centered text and CTA button introducing "Manohar NM - Computer Science Engineer | Full Stack Developer"

### About Section
Light gray background with company-wide view of professional qualifications and expertise

### Projects Section
Grid of project cards (responsive - 3 columns on desktop, 1 on mobile) with hover lift effects

### Navigation
Desktop: Horizontal menu with all links visible
Mobile: Burger menu icon that toggles dropdown navigation

---

## Quick Links

- 🔗 **GitHub**: https://github.com/Manohar-NM/week1-portfolio
- 💼 **Portfolio**: [Live Link - Add after deployment]
- 📧 **Email**: [Add your contact email]
- 🐙 **GitHub Profile**: https://github.com/Manohar-NM

---

## License

MIT License - Open source and free to use

---

**Version**: 1.0
**Last Updated**: February 15, 2026
**Author**: Manohar NM - Computer Science Engineer & Full Stack Developer
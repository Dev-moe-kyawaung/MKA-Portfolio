i# 🌟 Moe Kyaw Aung - Senior Android Developer Portfolio

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)](https://dev-moe-kyawaung.github.io/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> A comprehensive, production-ready portfolio website showcasing 12+ years of Android development expertise

![Portfolio Preview](https://res.cloudinary.com/dye5qpwii/image/upload/v1778527878/IMG_20260430_053105_uef0yr.png)

## 🚀 Live Demo

**[View Live Site](https://dev-moe-kyawaung.github.io/MKA-Portfolio/)**

## ✨ Features

### 📱 **Comprehensive Sections (20+)**
- **Hero Section** with animated particle background
- **About Me** with timeline & SVG progress rings
- **Skills Showcase** with 24+ technologies
- **Apps Collection** featuring 16+ production apps
- **Certificates Section** with 82+ certifications across 9 categories
- **GitHub Accounts** collection (43+ accounts)
- **Lovable PWA Links** (38+ progressive web apps)
- **Email Collection** (16+ professional emails)
- **Social Media** accounts from all major platforms
- **Burmese Language Support** section
- **Features & Services** showcase
- **Testimonials** slider with client feedback
- **Pricing Plans** for different project sizes
- **FAQ** accordion section
- **Gallery** with lightbox functionality
- **Contact Form** with validation
- **Google Maps** integration
- **Newsletter** subscription
- **Multi-column Footer** with links

### 🎨 **Design & Animations**
- **Cyberpunk/Neon Theme** with cyan, pink, purple colors
- **Particle.js** animated background
- **Animated Statistics** counters
- **SVG Progress Rings** with animation
- **Custom Cursor** effect
- **Smooth Scroll** navigation
- **Parallax Effects** on scroll
- **Typing Animation** for hero subtitle
- **Hover Effects** and micro-interactions
- **Fade-in/Slide-in** animations on scroll

### 💻 **Interactive Features**
- ✅ Responsive hamburger mobile menu
- ✅ Dark/Light mode toggle with localStorage
- ✅ Smooth scroll navigation
- ✅ Animated statistics counter
- ✅ Testimonial carousel/slider
- ✅ Contact form with validation
- ✅ FAQ accordion section
- ✅ Image lightbox gallery with keyboard navigation
- ✅ Newsletter subscription form
- ✅ Email copy-to-clipboard functionality
- ✅ Google Maps embed
- ✅ Preloader/loading animation
- ✅ Back to top button
- ✅ Sticky call-to-action button
- ✅ Custom cursor effect

### 📱 **Responsive Design**
- Fully responsive across all devices
- Breakpoints: 1024px, 768px, 480px
- Mobile-first approach
- Touch-friendly interactions
- Optimized for tablets
- - **Tailwind CSS** - Utility-first CSS framework
- **Font Awesome** - Icon library
- **Google Fonts** - Orbitron, Rajdhani, Share Tech Mono
- **Canvas API** - Particle animation
- **Intersection Observer API** - Scroll animations
- **Local Storage API** - Theme persistence



## 📂 Project Structure

```
Moe-Kyaw-Aung-Portfolio-01/
│
├── index.html              # Main HTML file
├── README.md               # Project documentation
├── LICENSE                 # MIT License
├── .gitignore             # Git ignore file
├── CONTRIBUTING.md         # Contribution guidelines
├── CHANGELOG.md           # Version history
│
├── assets/                 # Static assets (optional)
│   ├── images/            # Local images
│   ├── icons/             # Custom icons
│   └── fonts/             # Local fonts (if needed)
│
├── css/                    # Separated CSS (optional)
│   └── style.css          # Main stylesheet
│
├── js/                     # Separated JavaScript (optional)
│   ├── main.js            # Main JavaScript
│   ├── particles.js       # Particle animation
│   └── utils.js           # Utility functions
│
└── docs/                   # Documentation
    ├── DEPLOYMENT.md      # Deployment guide
    └── CUSTOMIZATION.md   # Customization guide
```

## 🚀 Quick Start

### Prerequisites

- Git installed on your machine
- GitHub account
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dev-moe-kyawaung/Moe-Kyaw-Aung-Portfolio-01.git
   cd Moe-Kyaw-Aung-Portfolio-01
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   # Or use a local server
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **Customize**
   - Edit `index.html` to update content
   - Modify CSS variables for theming
   - Update images and links

### GitHub Pages Deployment

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/Dev-moe-kyawaung/Moe-Kyaw-Aung-Portfolio-01.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Select `main` branch as source
   - Click Save
   - Your site will be live at: `https://dev-moe-kyawaung.github.io/Moe-Kyaw-Aung-Portfolio-01/`

3. **Custom Domain (Optional)**
   - Add `CNAME` file with your domain
   - Configure DNS settings with your provider

## 🎨 Customization

### Change Colors

Edit CSS variables in the `<style>` section:

```css
:root {
    --neon-cyan: #00f3ff;      /* Primary color */
    --neon-pink: #ff006e;      /* Secondary color */
    --neon-purple: #8b00ff;    /* Accent color */
    --bg-dark: #0a0a0f;        /* Background */
}
```

### Update Content

1. **Personal Information** - Edit hero section
2. **Skills** - Modify skill chips
3. **Projects** - Update app cards with your projects
4. **Contact Details** - Change phone/email
5. **Social Links** - Update href attributes

### Add New Sections

```html
<section class="section" id="new-section">
    <div class="section-label fade-up">Label</div>
    <h2 class="section-title fade-up">Title</h2>
    <p class="section-desc fade-up">Description</p>
    <!-- Your content here -->
</section>
```

## 📱 Browser Support

| Browser | Version |
|---------|---------|
| Chrome  | Latest 2 versions |
| Firefox | Latest 2 versions |
| Safari  | Latest 2 versions |
| Edge    | Latest 2 versions |
| Opera   | Latest 2 versions |

## 🐛 Known Issues

- Particle animation may slow down on low-end devices
- Custom cursor doesn't work on touch devices (by design)
- Some animations disabled in Firefox for performance

## 🔧 Troubleshooting

**Issue**: Fonts not loading
- **Solution**: Check internet connection, fonts are loaded from Google CDN

**Issue**: Icons not showing
- **Solution**: Verify Font Awesome CDN link is working

**Issue**: Animations not working
- **Solution**: Check browser supports Intersection Observer API

**Issue**: Mobile menu not closing
- **Solution**: Clear browser cache and reload

## 📈 Performance Tips

1. **Optimize Images** - Use WebP format, compress before upload
2. **Lazy Loading** - Add `loading="lazy"` to images
3. **Minify Code** - Use tools like UglifyJS and CSSNano
4. **Enable Caching** - Configure browser caching
5. **Use CDN** - Host static assets on CDN

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Moe Kyaw Aung (မိုးကျော်အောင်)**

- 🌐 Website: [https://dev-moe-kyawaung.github.io/](https://dev-moe-kyawaung.github.io/)
- 📧 Email: moekyawaung@programmer.net
- 💼 LinkedIn: [Moe Kyaw Aung](https://www.linkedin.com/in/moe-kyaw-aung-2653093a1)
- 🐙 GitHub: [@Dev-moe-kyawaung](https://github.com/Dev-moe-kyawaung)
- 📱 Telegram: [@moekyawaung](https://t.me/moekyawaung)
- 📞 Phone: +95 9 889 000 889

## 🙏 Acknowledgments

- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography
- [Tailwind CSS](https://tailwindcss.com/) for utility classes
- [Cloudinary](https://cloudinary.com/) for image hosting
- Inspiration from various portfolio designs

## 📊 Project Stats

- **Lines of Code**: 15,000+
- **Sections**: 20+
- **Interactive Features**: 18+
- **Responsive Breakpoints**: 4
- **Browser Compatibility**: 95%+
- **Accessibility Score**: A+
- **Performance**: Optimized

## 🗺️ Roadmap

- [ ] Add blog section
- [ ] Implement contact form backend
- [ ] Add more language support (Thai, Chinese)
- [ ] Create admin dashboard
- [ ] Add analytics integration
- [ ] Implement search functionality
- [ ] Add RSS feed
- [ ] Create mobile app version

## 💬 Support

If you have any questions or need help, feel free to reach out:

- Open an issue on GitHub
- Email: moekyawaung@programmer.net
- Telegram: @moekyawaung

## ⭐ Show Your Support

Give a ⭐️ if this project helped you!

---

<div align="center">
  <p>Made with ❤️ in Myanmar 🇲🇲</p>
  <p>© 2025 Moe Kyaw Aung. All rights reserved.</p>
</div>
```

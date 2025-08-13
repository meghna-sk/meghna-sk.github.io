# Meghna Suraj Kashyap - Portfolio Website

A modern, responsive portfolio website showcasing front-end development skills with interactive animations, dark mode, and cutting-edge web technologies.

## ✨ Features

### 🎨 Design & UX
- **Modern Design**: Clean, professional layout with beautiful gradients and animations
- **Dark/Light Mode**: Toggle between themes with persistent preference storage
- **Responsive Design**: Fully responsive across all devices and screen sizes
- **Smooth Animations**: CSS animations, transitions, and interactive hover effects
- **3D Tilt Effects**: Interactive 3D card tilting on mouse movement
- **Particle Background**: Animated floating particles for visual appeal

### 🚀 Interactive Components
- **Animated Skill Bars**: Progress bars that animate when scrolled into view
- **Typewriter Effect**: Animated text typing effect for the main heading
- **Scroll Progress Bar**: Visual progress indicator at the top of the page
- **Smooth Scrolling**: Smooth navigation between sections
- **Hover Effects**: Interactive hover states on all clickable elements
- **Form Validation**: Contact form with proper validation and styling

### 📱 Sections
1. **Hero Section**: Introduction with animated greeting and social links
2. **Skills Section**: Animated skill bars and technology icons
3. **Education**: Academic background with interactive cards
4. **Experience**: Work history with detailed achievements
5. **Projects**: Portfolio of featured projects with links
6. **Contact**: Contact form and social media links

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern HTML features
- **CSS3**: Advanced styling with custom animations and effects
- **Tailwind CSS**: Utility-first CSS framework for rapid development
- **JavaScript (ES6+)**: Modern JavaScript for interactivity
- **Font Awesome**: Icon library for social media and UI icons
- **Google Fonts**: Plus Jakarta Sans for typography

## 🎯 Front-End Skills Demonstrated

### CSS & Styling
- Custom CSS animations and keyframes
- CSS Grid and Flexbox layouts
- CSS custom properties (variables)
- Advanced selectors and pseudo-elements
- Responsive design principles
- Dark mode implementation
- Custom scrollbar styling
Meghna Suraj Kashyap Product Workbook.docx
### JavaScript
- DOM manipulation and event handling
- Intersection Observer API for scroll animations
- Local Storage for theme persistence
- Smooth scrolling implementation
- Dynamic content generation (particles)
- Form handling and validation

### Performance & UX
- Optimized animations with `will-change` property
- Passive event listeners for scroll performance
- Lazy loading with Intersection Observer
- Smooth transitions and micro-interactions
- Accessibility considerations (ARIA labels, semantic HTML)

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Customize the content to match your information

## 📝 Customization Guide

### Personal Information
Update the following sections in `index.html`:

1. **Name and Title**: Update the `<title>` tag and main heading
2. **Contact Information**: Replace email and social media links
3. **Profile Picture**: Replace the base64 image with your own photo
4. **About Section**: Update the description and tagline

### Skills Section
Modify the skills in the skills section:
```html
<div class="flex justify-between text-sm mb-1">
  <span>Your Skill</span>
  <span>95%</span>
</div>
<div class="skill-bar h-2">
  <div class="skill-progress" data-width="95"></div>
</div>
```

### Projects
Add your own projects by duplicating the project card structure:
```html
<article class="tilt group rounded-2xl bg-gradient-to-br from-white to-white dark:from-white/5 dark:to-white/10 p-[1px] glow">
  <div class="rounded-2xl bg-white dark:bg-slate-900/60 p-5 tilt-child">
    <!-- Project content -->
  </div>
</article>
```

### Colors and Styling
The portfolio uses a violet/purple color scheme. To change colors:
1. Update the gradient classes (e.g., `from-violet-500 to-violet-600`)
2. Modify the CSS custom properties in the `<style>` section
3. Update the particle colors and glow effects

## 🌐 Deployment to GitHub Pages

### Method 1: Direct Upload
1. Create a new repository on GitHub
2. Upload the `index.html` file to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Method 2: Using GitHub CLI
```bash
# Initialize git repository
git init
git add .
git commit -m "Initial portfolio commit"

# Create repository on GitHub
gh repo create your-portfolio --public

# Push to GitHub
git push -u origin main

# Enable GitHub Pages
gh repo edit --enable-pages
```

### Method 3: Using GitHub Desktop
1. Open GitHub Desktop
2. Add the portfolio folder as a repository
3. Publish to GitHub
4. Enable GitHub Pages in repository settings

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ Internet Explorer (not supported)

## 🔧 Advanced Customization

### Adding New Sections
1. Create a new section with the `reveal` class
2. Add navigation link in the header
3. Update the JavaScript observer to handle the new section

### Custom Animations
Add new CSS animations in the `<style>` section:
```css
@keyframes yourAnimation {
  0% { /* initial state */ }
  100% { /* final state */ }
}
```

### Performance Optimization
- Compress images before adding them
- Consider lazy loading for images
- Minify CSS and JavaScript for production
- Use a CDN for external resources

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider sharing them with the community!

## 📞 Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

---

**Built with ❤️ and modern web technologies** 
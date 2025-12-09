# ShuttleLab - Modern Immersive Website Template

A state-of-the-art, fully responsive website template built with modern web technologies and industry best practices.

## ✨ Features

- **🚀 Modern Design**: Cutting-edge aesthetics with smooth animations and transitions
- **📱 Fully Responsive**: Seamless experience across all devices and screen sizes
- **⚡ Lightning Fast**: Optimized performance with efficient code
- **🎨 Customizable**: Easy to adapt with CSS custom properties
- **♿ Accessible**: Built with WCAG guidelines in mind
- **🔍 SEO Optimized**: Semantic HTML and proper meta tags
- **🎭 Smooth Animations**: Intersection Observer API for performant animations
- **🌈 Glassmorphism & Gradients**: Modern visual effects
- **📊 Interactive Components**: Testimonial slider, smooth scrolling, mobile navigation

## 🏗️ Structure

```
shuttle-lab/
├── css/
│   └── styles.css          # Main stylesheet with modern CSS features
├── js/
│   └── main.js             # Interactive features and animations
├── index.html              # Main HTML file with semantic markup
├── package.json            # Project configuration
└── README.md              # Documentation
```

## 🎯 Sections

1. **Hero Section**: Eye-catching landing area with gradient background and parallax effect
2. **Features**: Grid layout showcasing key features with icon cards
3. **Services**: Two-column layout with image and service list
4. **Portfolio**: Grid gallery of projects with hover effects
5. **Testimonials**: Auto-rotating carousel with client feedback
6. **Contact**: Form with contact information and map placeholder
7. **Footer**: Multi-column footer with social links and newsletter signup

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Node.js and npm (required for development server and scripts)
  - Download from [nodejs.org](https://nodejs.org/)
  - Verify installation: `node --version` and `npm --version`

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Jin-HoMLee/shuttle-lab.git
cd shuttle-lab
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
# Using modern serve (recommended)
npm run dev
```

4. Visit `http://localhost:5173` in your browser

## ⚡ Vite Usage

This project uses [Vite](https://vitejs.dev/) for a modern, lightning-fast development and build experience.

### Development
Run the development server with hot reload:
```bash
npm run dev
```
- Opens your site at `http://localhost:5173/` (default)
- Auto-reloads on file changes

### Production Build
Create an optimized production build:
```bash
npm run build
```
- Outputs static files to the `dist/` directory

### Preview Production Build
Serve the built site locally to test the production output:
```bash
npm run preview
```
- Opens your site at `http://localhost:4173/` (default)
- Serves files from `dist/`

**Note:** Always run `npm run build` before `npm run preview`.

For more details, see the [Vite documentation](https://vitejs.dev/guide/).

## 🎨 Customization

### Colors

Customize the color scheme by modifying CSS custom properties in `css/styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #ec4899;
    --accent-color: #f59e0b;
    /* ... more colors */
}
```

### Typography

Change fonts by updating the Google Fonts import in `index.html` and the CSS variables:

```css
:root {
    --font-primary: 'Inter', sans-serif;
    --font-display: 'Playfair Display', serif;
}
```

### Content

Edit the HTML content in `index.html` to match your needs. All sections are clearly marked with comments.

## 🌟 Modern Features Used

- **CSS Grid & Flexbox**: For flexible, responsive layouts
- **CSS Custom Properties**: For easy theming and customization
- **Intersection Observer API**: For efficient scroll-based animations
- **CSS Gradients**: For modern visual effects
- **CSS Transitions & Animations**: For smooth interactions
- **Mobile-First Responsive Design**: Optimized for all screen sizes
- **Semantic HTML5**: For better accessibility and SEO
- **Modern JavaScript (ES6+)**: Arrow functions, template literals, etc.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Icons: Custom SVG icons
- Fonts: Google Fonts (Inter, Playfair Display)
- Design Inspiration: Modern web design trends and best practices

## 📞 Contact

For questions or support, please open an issue on GitHub.

---

**Built with ❤️ using modern web technologies**
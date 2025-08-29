# Arpit Chaudhary - Personal Website

A clean, modern personal website built with vanilla HTML, CSS, and JavaScript. Designed to showcase professional experience, research, and contact information.

## 🚀 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI**: Clean, minimalist design with smooth animations
- **Fast Loading**: Vanilla web technologies for optimal performance
- **SEO Friendly**: Semantic HTML structure and meta tags
- **Accessible**: Built with accessibility best practices

## 🛠️ Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript**: Smooth scrolling and animations
- **Vercel**: Hosting and deployment platform

## 📁 Project Structure

```
personal-hub/
├── index.html          # Main HTML file
├── vercel.json         # Vercel deployment configuration
├── .gitignore          # Git ignore rules
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Git (for version control)
- Vercel CLI (optional, for local development)

### Local Development

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd personal-hub
   ```

2. **Open in browser**
   ```bash
   # Using Python (if installed)
   python -m http.server 8000
   
   # Using Node.js (if installed)
   npx serve .
   
   # Or simply open index.html in your browser
   ```

3. **View the website**
   - Navigate to `http://localhost:8000` (if using Python server)
   - Or open `index.html` directly in your browser

## 🌐 Deployment

### Deploy to Vercel

1. **Install Vercel CLI** (optional)
   ```bash
   npm i -g vercel
   ```

2. **Deploy**
   ```bash
   vercel
   ```

3. **Or connect to GitHub**
   - Push your code to GitHub
   - Connect your repository to Vercel
   - Vercel will automatically deploy on every push

### Manual Deployment

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Vercel will automatically detect it's a static site and deploy

## 📝 Customization

### Content Updates

- **Personal Information**: Update the content in `index.html`
- **Styling**: Modify CSS variables in the `:root` selector
- **Links**: Update social media and contact links

### Key Sections to Customize

1. **Hero Section**: Update name, title, and location
2. **About Section**: Modify professional background and personal story
3. **Research Section**: Add or update academic publications
4. **Contact Section**: Update email and social links

### Color Scheme

The website uses CSS custom properties for easy theming:

```css
:root {
    --bg-primary: #ffffff;
    --bg-secondary: #fafafa;
    --text-primary: #1a1a1a;
    --text-secondary: #666666;
    --accent: #0066ff;
    /* ... more variables */
}
```

## 🔧 Configuration

### Vercel Settings

The `vercel.json` file includes:
- Static file serving configuration
- Security headers
- Route handling for SPA-like behavior

### SEO Optimization

The HTML includes:
- Proper meta tags
- Semantic HTML structure
- Open Graph tags (can be added)
- Schema markup (can be added)

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

This is a personal website, but if you find any issues or have suggestions:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

- **Email**: achaudhary512@gmail.com
- **LinkedIn**: [Arpit Chaudhary](https://www.linkedin.com/in/arpit717)
- **Google Scholar**: [Academic Profile](https://scholar.google.com/citations?user=2OY8XlUAAAAJ)

---

Built with ❤️ using vanilla web technologies. Deployed on Vercel.

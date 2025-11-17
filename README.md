# Personal Portfolio Website

A clean, modern, and responsive personal portfolio website built from scratch using HTML5 and CSS3.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, minimalist design with smooth animations
- **Sticky Navigation**: Navigation bar stays at the top when scrolling
- **Smooth Scrolling**: Seamless navigation between sections
- **Accessible**: Built with semantic HTML5 for better accessibility
- **Fast Loading**: No external dependencies, pure HTML/CSS

## 📁 Project Structure

```
uniwebsite/
├── index.html      # Main HTML file with website structure
├── styles.css      # CSS stylesheet with all styling
└── README.md       # This file
```

## 🎨 Design Features

### Color Scheme
- Primary Color: Dark blue-gray (#2c3e50)
- Secondary Color: Bright blue (#3498db)
- Clean white background with subtle gray alternating sections

### Sections
1. **Header**: Eye-catching gradient header with name and tagline
2. **Navigation**: Sticky navigation menu for easy section access
3. **About**: Personal introduction and expertise
4. **Projects**: Showcase of work with card-based layout
5. **Contact**: Social links and contact information
6. **Footer**: Copyright information

### Responsive Breakpoints
- Desktop: > 768px
- Tablet: 768px - 481px
- Mobile: < 480px

## 🚀 How to Use

1. **View Locally**:
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Or using PHP
   php -S localhost:8000
   ```
   Then open `http://localhost:8000` in your browser

2. **Customize**:
   - Edit `index.html` to change content (name, bio, projects)
   - Modify `styles.css` to adjust colors and styling
   - Update CSS variables in `:root` for quick color theme changes

## 💡 Code Explanation

### HTML Structure
The HTML uses semantic elements for better SEO and accessibility:
- `<header>`: Contains the main title and tagline
- `<nav>`: Navigation menu with internal links
- `<main>`: Main content area with sections
- `<section>`: Individual content sections (About, Projects, Contact)
- `<footer>`: Copyright and footer information

### CSS Features
- **CSS Variables**: Easy theme customization
- **Flexbox & Grid**: Modern layout techniques
- **Media Queries**: Responsive design
- **Transitions**: Smooth hover effects
- **Box Shadow**: Depth and visual hierarchy

### Key CSS Techniques Used:
1. **Sticky Navigation**: `position: sticky; top: 0;`
2. **Smooth Scrolling**: `scroll-behavior: smooth;`
3. **CSS Grid**: `display: grid;` for project cards
4. **Gradient Background**: `linear-gradient()` for header
5. **Hover Effects**: `transition` properties for smooth animations

## 🎯 Customization Guide

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c3e50;     /* Main dark color */
    --secondary-color: #3498db;   /* Accent color */
    --text-color: #333;           /* Text color */
    --light-bg: #f8f9fa;          /* Light background */
}
```

### Update Content
Edit `index.html`:
- Line 13: Change the name
- Line 14: Update the tagline
- Lines 28-47: Modify the About section
- Lines 52-72: Update projects
- Lines 80-85: Change contact links

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

Feel free to use this template for your own portfolio website!

---

Built with ❤️ using pure HTML5 and CSS3

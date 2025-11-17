# Academic Personal Website

A modern, professional academic website built with HTML5 and CSS3, inspired by the Prologue template design with a fixed sidebar navigation.

## 🌟 Features

- **Prologue-Style Sidebar**: Fixed sidebar navigation with profile photo and social links
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Academic Sections**: About, Research, Publications, Teaching, and Contact
- **Modern UI**: Clean, professional design with smooth animations and hover effects
- **Accessible**: Built with semantic HTML5 for better accessibility
- **Fast Loading**: No external dependencies, pure HTML/CSS

## 📁 Project Structure

```
uniwebsite/
├── index.html      # Main HTML file with website structure
├── styles.css      # CSS stylesheet with Prologue-inspired sidebar layout
└── README.md       # This file
```

## 🎨 Design Features

### Layout
- **Fixed Sidebar** (350px width on desktop): Contains profile, navigation, and social links
- **Main Content Area**: Scrollable sections with alternating backgrounds
- **Mobile-Friendly**: Sidebar collapses with toggle button on smaller screens

### Color Scheme
- Primary Color: Bright blue (#4a90e2)
- Secondary Color: Green (#50c878)
- Accent Color: Red (#ff6b6b)
- Dark Background: Dark blue-gray (#2c3e50)
- Clean white and light gray backgrounds for content

### Sections
1. **Sidebar**: Profile photo, name, title, department, navigation, social links
2. **About**: Personal introduction, research interests, and education
3. **Research**: Current research projects with funding information
4. **Publications**: Journal articles and conference papers organized by year
5. **Teaching**: Current courses and student supervision (Ph.D. and M.S.)
6. **Contact**: Email, office location, phone, office hours, and prospective student info

### Responsive Breakpoints
- Desktop: > 980px (full sidebar visible)
- Tablet: 980px - 736px (sidebar toggleable)
- Mobile: < 736px (optimized mobile layout)

## 🚀 How to Use

1. **View Locally**:
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Or using PHP
   php -S localhost:8000
   ```
   Then open `http://localhost:8000` in your browser

2. **Customize Content**:
   - **Profile**: Edit lines 18-22 in `index.html` (name, title, department)
   - **About Section**: Lines 48-97 (bio, interests, education)
   - **Research Projects**: Lines 105-138 (project details and funding)
   - **Publications**: Lines 147-213 (papers, conferences, links)
   - **Teaching**: Lines 221-273 (courses, students)
   - **Contact Info**: Lines 281-316 (email, office, phone, hours)

3. **Customize Styling**:
   - Edit `styles.css` to adjust colors and styling
   - Modify CSS variables in `:root` for quick theme changes
   - Adjust sidebar width with `--sidebar-width` variable

## 💡 Code Explanation

### HTML Structure
The HTML uses semantic elements for better SEO and accessibility:
- `<div id="sidebar">`: Fixed sidebar with profile and navigation
- `<div id="main">`: Main content area with scrollable sections
- `<section class="main-section">`: Individual content sections
- `<header class="section-header">`: Section titles and descriptions

### CSS Features
- **CSS Variables**: Easy theme customization via `:root` properties
- **Fixed Sidebar**: `position: fixed` for persistent navigation
- **Flexbox & Grid**: Modern layout for responsive design
- **Smooth Scrolling**: CSS `scroll-behavior: smooth` for anchor navigation
- **Transitions**: Smooth hover effects on links and cards
- **Media Queries**: Responsive breakpoints for all devices

### Key CSS Techniques Used:
1. **Fixed Sidebar**: `position: fixed; left: 0; width: 350px;`
2. **Main Content Margin**: `margin-left: var(--sidebar-width);`
3. **Smooth Transitions**: `transition: all 0.3s ease;` for hover effects
4. **Gradient Backgrounds**: `linear-gradient()` for sidebar and special sections
5. **Responsive Toggle**: Hidden menu button on mobile with sidebar slide-in

## 🎯 Customization Guide

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #4a90e2;     /* Accent blue */
    --secondary-color: #50c878;   /* Green for highlights */
    --dark-bg: #2c3e50;           /* Sidebar background */
    --light-bg: #f8f9fa;          /* Light background */
}
```

### Replace Profile Image
Replace the placeholder URL in `index.html` line 19:
```html
<img src="YOUR_IMAGE_URL" alt="Profile Photo">
```
Recommended size: 200x200px (will be displayed as circular)

### Add/Remove Sections
- Copy an existing `<section>` block in `index.html`
- Add corresponding navigation link in the sidebar `<nav>` menu
- Style inherits from existing `.main-section` CSS class

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📖 Academic Use

This template is perfect for:
- Faculty personal websites
- Graduate student academic pages
- Researcher portfolio sites
- Academic lab group pages

## 📄 License

Feel free to use this template for your own academic website!

---

**Design Inspiration**: Prologue HTML5 Template  
**Built with**: Pure HTML5 and CSS3 (no frameworks or dependencies)

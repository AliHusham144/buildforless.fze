# BuildModular - Professional Commercial Website

A modern, minimalist commercial website for custom modular and smart building solutions. This is a fully responsive, professional design inspired by high-end architectural firms.

## Files Included

- **index.html** - Main website structure with all four sections
- **styles.css** - Complete styling with responsive design
- **script.js** - Interactive functionality and animations
- **README.md** - This documentation file

## Features

### 🎨 Design
- **Color Scheme**: White, gray, black with subtle green (#5a8c6f) and wood (#a89068) accents
- **Minimalist Layout**: Clean, elegant design inspired by methodhomes.net
- **Professional Typography**: Modern font stack with proper hierarchy
- **Responsive**: Fully optimized for desktop, tablet, and mobile devices

### 📱 Sections

1. **Navigation Bar**
   - Fixed, modern navbar with logo and section links
   - Mobile-responsive hamburger menu
   - Active link indicators
   - Call-to-action button

2. **Hero Section**
   - Full-height introductory section
   - Gradient background with subtle grid pattern
   - Clear brand message and primary CTA

3. **Residential Section**
   - Three featured project cards with hover effects
   - Feature highlights (Precision Engineering, Eco-Efficiency, Smart Integration)
   - Professional project descriptions

4. **Commercial Section**
   - Three commercial project showcases
   - Benefits grid with key advantages
   - Professional tone and messaging

5. **About Section**
   - Brand story and philosophy
   - Four core values (Innovation, Precision, Sustainability, Elegance)
   - Statistics showcase (450+ projects, 15+ years, 98% satisfaction, 60% faster delivery)
   - Background imagery with overlay patterns

6. **Get Started / Contact Section**
   - Professional contact form with validation
   - Multiple contact methods (email, phone, scheduling)
   - Form fields: Name, Email, Phone, Project Type, Message
   - Success feedback on submission

7. **Footer**
   - Company information
   - Quick navigation links
   - Service shortcuts
   - Social media links
   - Legal links

### ⚙️ Interactive Features

- **Mobile Menu Toggle**: Smooth hamburger menu for mobile devices
- **Smooth Scrolling**: All internal links use smooth scroll behavior
- **Form Validation**: Email validation with visual feedback
- **Scroll Animations**: Elements fade in as they come into view
- **Hover Effects**: Interactive project cards with elevation and color changes
- **Parallax Effect**: Subtle background movement on scroll
- **Active Navigation**: Current section highlighted in navbar

### 🎯 CSS Features

- **CSS Variables**: Organized color scheme and spacing system
- **Grid Layouts**: Modern CSS Grid for responsive design
- **Flexbox**: Flexible component layouts
- **Media Queries**: Breakpoints at 1024px, 768px, and 480px
- **Transitions**: Smooth animations throughout
- **Scalable Typography**: Responsive text sizing

### 🔧 Customization

#### Colors
Edit the CSS variables at the top of `styles.css`:
```css
:root {
    --primary-white: #ffffff;
    --light-gray: #f5f5f5;
    --accent-green: #5a8c6f;
    --accent-wood: #a89068;
    /* ... more colors */
}
```

#### Typography
Modify font sizes and weights in the Typography section of `styles.css`.

#### Content
Edit the HTML content in `index.html`:
- Company name: Change "BuildModular" in navbar and footer
- Project descriptions: Update project cards
- Brand story: Modify About section text
- Contact info: Update footer contact details

#### Images
Replace placeholder background gradients with actual images by updating the `.project-image` classes and `.about-image` div.

## Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px to 1024px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Live Server** (recommended): Use VS Code Live Server extension for best experience
3. **Customize**: Edit the HTML content and CSS variables as needed
4. **Add Images**: Replace gradient backgrounds with actual project photos

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Optimizations

- Lightweight CSS (no external dependencies)
- Smooth animations using CSS transforms
- Optimized responsive design
- Efficient JavaScript with minimal DOM manipulation
- Clean, semantic HTML

## Future Enhancements

- Image optimization and lazy loading
- Blog/Case studies section
- Team member profiles
- Client testimonials
- Newsletter signup
- CMS integration
- Analytics integration
- Multi-language support

## Notes

- The contact form currently logs to console. To make it functional, integrate with a backend service (email service, CRM, etc.)
- Placeholder image backgrounds use CSS gradients. Replace with actual project photography for maximum impact
- The design is fully accessible with semantic HTML and proper ARIA labels where needed

---

**Created**: February 2026
**Version**: 1.0
**Built with**: HTML5, CSS3, Vanilla JavaScript

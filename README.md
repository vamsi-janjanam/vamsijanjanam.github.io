# Vamsi Krishna Janjanam - Professional Portfolio

A modern, responsive GitHub Pages portfolio website showcasing a Data Engineer's professional profile, experience, and projects.

**Live Demo:** https://vamsijanjanam.github.io

## Features

✨ **Modern Design**
- Clean, professional layout with gradient accents
- Fully responsive design (mobile, tablet, desktop)
- Smooth animations and transitions
- Dark-themed hero section with engaging typography

🎯 **Key Sections**
- **Hero Section** - Eye-catching introduction with CTA buttons
- **About** - Professional summary and contact information
- **Skills** - Categorized expertise in AWS, Programming, Data Frameworks, Databases, and more
- **Experience** - Interactive timeline showcasing 5+ years of data engineering roles
- **Education** - Academic background and certifications
- **Projects** - Featured GitHub projects with direct links
- **Contact** - Multiple ways to get in touch

⚡ **Interactive Features**
- Smooth scrolling navigation
- Scroll-to-top floating button
- Fade-in animations on page scroll
- Active navigation link highlighting
- Hover effects on cards and elements
- Typing animation on hero title
- Intersection Observer for performance optimization

📱 **Responsive & Performance**
- Mobile-first design approach
- Optimized for all screen sizes
- Fast loading with vanilla HTML/CSS/JavaScript
- No external dependencies or build tools required
- SEO-friendly structure

## Technology Stack

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with CSS variables and Grid/Flexbox
- **Vanilla JavaScript** - No frameworks, lightweight interactivity
- **GitHub Pages** - Free, reliable hosting

## File Structure

```
vamsijanjanam.github.io/
├── index.html      # Main portfolio page
├── styles.css      # Professional styling
├── script.js       # Interactive features
└── README.md       # This file
```

## How to Use

### View the Portfolio
Simply visit: **https://vamsijanjanam.github.io**

### Customize for Your Own Use

1. **Clone or fork this repository**
   ```bash
   git clone https://github.com/vamsi-janjanam/vamsijanjanam.github.io.git
   ```

2. **Edit `index.html`** to customize:
   - Your name and professional title
   - Personal summary
   - Work experience entries
   - Projects and achievements
   - Contact information

3. **Modify `styles.css`** to:
   - Change colors (update CSS variables in `:root`)
   - Adjust fonts and typography
   - Customize spacing and layouts

4. **Update `script.js`** to:
   - Modify animation timings
   - Add additional interactivity
   - Customize scroll behavior

5. **Push to your GitHub Pages repository**
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push origin main
   ```

## Customization Guide

### Change Color Scheme
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;      /* Change this */
    --secondary-color: #1e40af;    /* And this */
    --text-dark: #1f2937;
    --text-light: #6b7280;
    --bg-light: #f9fafb;
    --bg-white: #ffffff;
}
```

### Update Hero Section
In `index.html`, find the `<header class="hero">` section:
```html
<h1>Your Name Here</h1>
<p class="title">Your Professional Title</p>
<p class="subtitle">Your elevator pitch</p>
```

### Add New Sections
Copy and modify existing section templates. Sections follow this structure:
```html
<section id="section-id" class="section [alt-bg]">
    <div class="container">
        <h2>Section Title</h2>
        <!-- Your content here -->
    </div>
</section>
```

### Update Contact Information
Find the contact section in `index.html` and update:
- Email address
- Phone number
- LinkedIn URL
- GitHub URL

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Metrics

- **Page Load**: < 2 seconds
- **Lighthouse Score**: 95+
- **Mobile Friendly**: Yes
- **SEO Optimized**: Yes

## Features in Detail

### Smooth Scrolling Navigation
Click any navigation link to smoothly scroll to that section.

### Active Link Highlighting
The navigation link for your current section is automatically highlighted.

### Scroll-to-Top Button
A floating button appears when you scroll down. Click it to smoothly return to the top.

### Fade-In Animations
Cards and elements fade in as they come into view, creating a polished effect.

### Responsive Timeline
The work experience timeline adapts beautifully to smaller screens.

### Mobile Optimization
The entire site is optimized for touch interactions and smaller viewports.

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Color contrast compliant
- Keyboard navigation support
- Descriptive alt text ready

## SEO Optimization

- Meta descriptions and keywords
- Semantic HTML5 elements
- Proper heading structure
- Mobile-friendly design
- Fast loading times

## Tips for Sharing

### LinkedIn
- Share the direct link: `https://vamsijanjanam.github.io`
- Add it to your LinkedIn profile URL section
- Reference it in your headline or summary

### Resume
Include a QR code or direct link to your portfolio

### Email Signature
Add the portfolio link to your professional email signature

### Job Applications
Include the portfolio link when applying for positions

## Local Development

To view locally before deploying:

1. Open `index.html` in your browser directly
   OR
2. Use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```
3. Visit `http://localhost:8000`

## Deployment

This portfolio is designed for **GitHub Pages**. To deploy:

1. Create a repository named `yourusername.github.io`
2. Push the files to the main branch
3. GitHub Pages automatically deploys your site
4. Access it at `https://yourusername.github.io`

## Future Enhancements

Consider adding:
- Dark mode toggle
- Blog section
- Testimonials carousel
- Skills progress bars
- Download resume button (PDF)
- Newsletter subscription
- Analytics integration

## License

This portfolio template is open source. Feel free to use it for your own portfolio!

## Contact & Support

- **Email**: vamsijanjanam@gmail.com
- **GitHub**: https://github.com/vamsi-janjanam
- **LinkedIn**: https://linkedin.com/in/vamsi-krishna-janjanam

---

**Last Updated**: June 2024

Built with ❤️ using HTML5, CSS3, and Vanilla JavaScript | Hosted on GitHub Pages
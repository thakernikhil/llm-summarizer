# Nikhil Thaker - Professional Portfolio Website

A modern, responsive, and professional portfolio website built with HTML, CSS, and JavaScript. This website showcases professional experience, projects, skills, and provides a contact form for potential clients or employers.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Animations**: Fade-in effects and scroll-triggered animations
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## File Structure

```
Nikhil Thaker Website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # This file
├── Prompt.docx         # Original requirements document
└── ~$Prompt.docx       # Temporary Word document
```

## Sections

1. **Hero Section**: Introduction with call-to-action buttons
2. **About Section**: Personal information and statistics
3. **Experience Section**: Professional timeline
4. **Projects Section**: Featured projects with technologies used
5. **Skills Section**: Technical skills organized by category
6. **Contact Section**: Contact information and contact form
7. **Footer**: Copyright information

## Customization Guide

### Personal Information

1. **Update the hero section** in `index.html`:
   - Change the name "Nikhil Thaker" to your name
   - Update the title and description
   - Modify the call-to-action buttons

2. **Update the about section**:
   - Replace the placeholder text with your personal information
   - Update the statistics (years of experience, projects, technologies)
   - Add your actual profile picture (replace the placeholder icon)

3. **Update experience section**:
   - Replace the sample job entries with your actual work experience
   - Update company names, positions, dates, and descriptions

4. **Update projects section**:
   - Replace the sample projects with your actual projects
   - Update project descriptions, technologies, and links
   - Add real project images (replace the placeholder icons)

5. **Update skills section**:
   - Modify the skill categories and items to match your expertise
   - Add or remove skills as needed

6. **Update contact section**:
   - Replace the placeholder contact information with your actual details
   - Update social media links
   - Configure the contact form to work with your preferred backend

### Styling Customization

1. **Colors**: The website uses a blue color scheme (`#2563eb`). You can change this in `styles.css`:
   - Primary color: `#2563eb`
   - Secondary color: `#fbbf24`
   - Background gradients: `#667eea` to `#764ba2`

2. **Fonts**: The website uses Inter font from Google Fonts. You can change this by:
   - Updating the Google Fonts link in `index.html`
   - Changing the font-family in `styles.css`

3. **Layout**: Modify the grid layouts and spacing in `styles.css` to adjust the overall layout.

### Adding Images

1. **Profile Picture**: Replace the placeholder in the hero section:
   ```html
   <div class="profile-placeholder">
       <img src="path/to/your/image.jpg" alt="Your Name">
   </div>
   ```

2. **Project Images**: Replace the placeholder icons with actual project screenshots:
   ```html
   <div class="project-image">
       <img src="path/to/project-image.jpg" alt="Project Name">
   </div>
   ```

### Contact Form Configuration

The contact form currently shows an alert message. To make it functional:

1. **For a simple solution**: Use a service like Formspree or Netlify Forms
2. **For a custom solution**: Add backend code to handle form submissions
3. **For email integration**: Configure the form to send emails directly

Example with Formspree:
```html
<form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
```

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimization

The website is optimized for performance with:
- Minimal external dependencies
- Optimized CSS and JavaScript
- Responsive images
- Efficient animations

## Deployment

### Local Development
1. Download all files to your local machine
2. Open `index.html` in a web browser
3. Make your customizations
4. Test on different devices and browsers

### Web Hosting
1. Upload all files to your web hosting provider
2. Ensure the file structure is maintained
3. Test the website on the live server

### Recommended Hosting Options
- **GitHub Pages**: Free hosting for static websites
- **Netlify**: Free hosting with form handling
- **Vercel**: Fast deployment and hosting
- **Traditional web hosting**: Any provider that supports static websites

## SEO Optimization

The website includes basic SEO elements:
- Proper meta tags
- Semantic HTML structure
- Alt text for images
- Descriptive page titles
- Clean URL structure

## Accessibility

The website includes accessibility features:
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support
- High contrast colors
- Screen reader compatibility

## Future Enhancements

Consider adding these features:
- Blog section
- Portfolio gallery
- Testimonials section
- Downloadable resume
- Dark mode toggle
- Multi-language support
- Analytics integration

## Support

If you need help customizing the website:
1. Check the HTML comments for guidance
2. Review the CSS classes and structure
3. Test changes in a local environment first
4. Use browser developer tools for debugging

## License

This website template is free to use and modify for personal and commercial projects.

---

**Note**: Remember to replace all placeholder content with your actual information before publishing the website. Test thoroughly on different devices and browsers to ensure compatibility. 
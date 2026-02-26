# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript to showcase your skills, projects, and professional information.

## Features

- **Modern Design**: Clean, professional design with gradient accents and smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Animated typing effect
  - Scroll reveal animations
  - Interactive project cards
  - Animated skill counters
  - Contact form with validation
- **Sections**:
  - Hero section with call-to-action
  - About section with statistics
  - Skills & technologies showcase
  - Featured projects gallery
  - Contact form and information

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with animations and transitions
- **JavaScript**: Interactive features and animations
- **Google Fonts**: Inter font family
- **Font Awesome**: Icon library

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Complete styling
├── script.js           # Interactive JavaScript
└── README.md           # This file
```

## Customization

### Personal Information

Update the following in `index.html`:

1. **Name and Title**: Replace "Your Name" in the hero section
2. **Contact Information**: Update email, phone, and location in the contact section
3. **Social Links**: Replace `#` with your actual social media URLs
4. **Projects**: Modify project cards with your actual projects
5. **Skills**: Update skills and technologies to match your expertise

### Styling

The CSS uses CSS variables for easy customization:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    /* ... other variables */
}
```

### Images

Replace the placeholder icons with your actual profile photo and project screenshots:

1. Profile placeholder: Replace the `<i class="fas fa-user"></i>` in the hero section
2. Project images: Replace the placeholder icons in project cards

## Deployment

### Local Development

1. Clone or download the files
2. Open `index.html` in your web browser
3. No build process required - it's pure HTML/CSS/JS

### Hosting

Deploy to any static hosting service:

- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repository
- **GitHub Pages**: Enable in repository settings
- **Firebase Hosting**: Use Firebase CLI
- **Any static hosting service**

## Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized animations using CSS transforms
- Debounced scroll events for better performance
- Lazy loading animations
- Minimal external dependencies
- Efficient DOM manipulation

## Contact Form

The contact form includes client-side validation. To make it functional, you'll need to:

1. Connect it to a backend service (Formspree, Netlify Forms, etc.)
2. Or implement your own server-side processing
3. Update the form submission handler in `script.js`

## License

This portfolio template is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing or have questions, feel free to reach out or check the code comments for detailed explanations of each feature.

---

**Happy coding!** 🚀

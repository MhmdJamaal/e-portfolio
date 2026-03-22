# Portfolio Website

A modern, responsive portfolio website built with HTML5, CSS3, and JavaScript. Features a clean design with the #0B0BFF color theme and includes sections for About Me, Projects, Skills, and Contact information.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Navigation**: Fixed navbar with smooth scrolling to sections
- **Project Showcase**: Grid layout for displaying projects with hover effects
- **Skills Display**: Organized skills section with icons and categories
- **Contact Section**: Social media links and contact information
- **Mobile Menu**: Hamburger menu for mobile navigation
- **Scroll to Top**: Floating button for easy navigation

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js       # JavaScript functionality
├── assets/             # Images and documents
│   ├── resume.pdf      # Resume file (add your own)
│   ├── project1.jpg    # Project images (add your own)
│   ├── project2.jpg
│   ├── project3.jpg
│   └── project4.jpg
└── README.md           # This file
```

## Setup Instructions

1. **Clone or download** this repository to your local machine
2. **Add your assets**:
   - Replace `assets/resume.pdf` with your actual resume
   - Add project images (project1.jpg, project2.jpg, etc.) to the assets folder
   - Update the image paths in `index.html` if needed

3. **Customize content**:
   - Update the name, title, and bio in the HTML
   - Modify project descriptions and links
   - Update contact information and social media links
   - Adjust skills and technologies to match your expertise

4. **Test locally**:
   - Open `index.html` in a web browser
   - Test responsiveness by resizing the browser window
   - Verify all navigation links work correctly

## Customization Guide

### Updating Personal Information

1. **Hero Section**: Edit the name and title in the hero section
2. **About Section**: Update the bio text and statistics
3. **Contact Section**: Add your email, phone, and location
4. **Social Links**: Update href attributes with your social media profiles

### Adding Projects

1. **Images**: Add project images to the `assets/` folder
2. **HTML**: Update project cards with your project information
3. **Links**: Add links to live demos and GitHub repositories

### Modifying Colors

The primary color theme is #0B0BFF. To change it:

1. Search for `#0B0BFF` in `css/style.css`
2. Replace with your preferred color
3. Update hover states (`#0909e6`) accordingly

### Adding New Sections

1. Add the HTML structure in `index.html`
2. Add corresponding styles in `css/style.css`
3. Update navigation links in the navbar

## Deployment

### GitHub Pages

1. **Create a GitHub repository** for your portfolio
2. **Upload all files** to the repository
3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to Pages section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save settings
4. **Access your site** at `https://yourusername.github.io/repository-name`

### Other Hosting Options

- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Connect your GitHub repository
- **Firebase Hosting**: Use Firebase CLI to deploy

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- **Optimized CSS**: Efficient selectors and minimal redundancy
- **Smooth Animations**: Hardware-accelerated transforms
- **Lazy Loading**: Images load as they come into view
- **Debounced Scroll Events**: Optimized scroll performance

## Accessibility Features

- **Semantic HTML**: Proper heading hierarchy and landmarks
- **Keyboard Navigation**: All interactive elements are keyboard accessible
- **Alt Text**: Image alt attributes for screen readers
- **Color Contrast**: Meets WCAG guidelines

## Technologies Used

- **HTML5**: Semantic markup and modern features
- **CSS3**: Flexbox, Grid, animations, and responsive design
- **JavaScript**: ES6+ features and modern APIs
- **Font Awesome**: Icons for skills and social links
- **Google Fonts**: Inter font family

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you encounter any issues or have questions:

1. Check the browser console for errors
2. Ensure all file paths are correct
3. Verify that external resources (fonts, icons) are loading
4. Test in different browsers

## Future Enhancements

Consider adding these features:

- **Contact Form**: Working contact form with backend integration
- **Blog Section**: Add a blog or articles section
- **Dark Mode**: Toggle between light and dark themes
- **Animations**: More advanced scroll-triggered animations
- **CMS Integration**: Connect to a headless CMS for easy content updates

---

**Note**: Remember to replace all placeholder content with your actual information before deploying!

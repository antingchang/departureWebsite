# Modern Company Website

A clean, modern website template inspired by the Lost Communications design. This website features a responsive design with smooth animations and modern UI/UX practices.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, minimal design with smooth animations
- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Scroll Animations**: Sections animate in as you scroll
- **Modern Typography**: Uses Inter font family for clean readability

## File Structure

```
departureWebsite/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Local server** (recommended): Use a local server for better development experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

## Customization

### Company Information

1. **Company Name**: Replace "Your Company Name" in `index.html` with your actual company name
2. **Contact Information**: Update the contact details in the Contact section
3. **About Section**: Modify the content in the About section to match your company

### Team Members

In the People section, update the team member information:

```html
<div class="team-member">
    <div class="member-photo">
        <div class="photo-placeholder"></div>
    </div>
    <h3 class="member-name">Your Name</h3>
    <p class="member-role">Your Role</p>
</div>
```

### Projects/Works

In the Works section, update the project information:

```html
<div class="work-item">
    <div class="work-image">
        <div class="image-placeholder"></div>
    </div>
    <h3 class="work-title">Your Project</h3>
    <p class="work-description">Project description here.</p>
</div>
```

### Colors and Styling

The website uses a modern color palette. You can customize colors in `styles.css`:

- **Primary Colors**: Update the gradient colors in `.btn-primary` and `.photo-placeholder`
- **Background**: Modify the hero section background gradient
- **Typography**: Change font weights and sizes as needed

### Adding Images

1. **Team Photos**: Replace the `.photo-placeholder` divs with actual images:
   ```html
   <div class="member-photo">
       <img src="path/to/photo.jpg" alt="Team Member Name">
   </div>
   ```

2. **Project Images**: Replace the `.image-placeholder` divs with actual project images:
   ```html
   <div class="work-image">
       <img src="path/to/project-image.jpg" alt="Project Name">
   </div>
   ```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Features

- **Optimized CSS**: Minimal and efficient styles
- **Smooth Animations**: Hardware-accelerated animations
- **Responsive Images**: Placeholder system ready for actual images
- **Fast Loading**: Minimal JavaScript for better performance

## Deployment

To deploy this website:

1. **Static Hosting**: Upload all files to services like:
   - GitHub Pages
   - Netlify
   - Vercel
   - AWS S3

2. **Custom Domain**: Configure your domain name in your hosting provider

3. **SSL Certificate**: Ensure HTTPS is enabled for security

## Customization Tips

- **Logo**: Add your company logo in the navigation
- **Favicon**: Add a favicon.ico file for browser tab icon
- **Meta Tags**: Update meta tags in the HTML head for SEO
- **Analytics**: Add Google Analytics or other tracking codes
- **Social Media**: Add social media links in the footer

## Support

This is a static website template. For advanced features like:
- Dynamic content management
- User authentication
- Database integration
- E-commerce functionality

Consider integrating with a backend framework or CMS.

## License

This template is free to use and modify for your projects. 
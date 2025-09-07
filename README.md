# Personal Website

A clean, modern, and responsive personal website built with HTML, CSS, and JavaScript. Perfect for showcasing your skills, projects, and professional background.

## 🌟 Features

- **Modern Design**: Clean, professional layout with gradient backgrounds and smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Navigation**: Smooth scrolling navigation with active state indicators
- **Project Showcase**: Dedicated section to display your best work
- **Contact Integration**: Easy-to-update contact information with social media links
- **Performance Optimized**: Fast loading with efficient CSS and JavaScript
- **GitHub Pages Ready**: Configured for easy deployment on GitHub Pages

## 🚀 Quick Start

### Option 1: GitHub Pages Deployment (Recommended)

1. **Fork or Download** this repository
2. **Rename** the repository to `yourusername.github.io` (replace `yourusername` with your GitHub username)
3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"
4. **Customize** your content (see customization section below)
5. **Commit and push** your changes
6. **Visit** `https://yourusername.github.io` to see your live website!

### Option 2: Custom Domain

If you want to use a custom domain:

1. Follow steps 1-3 from Option 1
2. **Add CNAME file**:
   ```bash
   echo "yourdomain.com" > CNAME
   ```
3. **Configure DNS** at your domain provider:
   - Add a CNAME record pointing to `yourusername.github.io`
4. **Update GitHub Pages settings** to use your custom domain

## ✏️ Customization

### 1. Personal Information

Edit `index.html` and replace the following placeholders:

- `Your Name` - Replace with your actual name
- `your.email@example.com` - Your email address
- `https://linkedin.com/in/yourprofile` - Your LinkedIn profile
- `https://github.com/yourusername` - Your GitHub profile
- Update the hero description and about section with your information

### 2. Projects Section

In `index.html`, update the projects section:

- Replace project titles, descriptions, and technologies
- Update project links to point to your actual projects
- Replace placeholder images with screenshots of your projects

### 3. Skills and Technologies

Update the skills section in `index.html`:

```html
<div class="skill-tags">
    <span class="skill-tag">Your Skill 1</span>
    <span class="skill-tag">Your Skill 2</span>
    <!-- Add more skills -->
</div>
```

### 4. Color Scheme

To change the color scheme, edit the CSS variables in `styles.css`:

```css
/* Main gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Update these colors throughout the file for consistency */
```

### 5. Profile Image

Replace the SVG placeholder in the hero section with your actual photo:

```html
<div class="hero-image">
    <img src="your-photo.jpg" alt="Your Name" class="profile-image">
</div>
```

Then add CSS for the image:

```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
}
```

## 📁 File Structure

```
personal-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── CNAME              # Custom domain (optional)
```

## 🛠️ Technical Details

### Technologies Used

- **HTML5**: Semantic markup with accessibility considerations
- **CSS3**: Modern styling with Flexbox, Grid, and CSS animations
- **JavaScript**: Interactive features and smooth scrolling
- **Google Fonts**: Inter font family for clean typography

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

### Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript for fast loading
- Responsive images and scalable vector graphics
- Smooth animations with CSS transitions

## 🎨 Design Features

- **Gradient Backgrounds**: Modern gradient color schemes
- **Smooth Animations**: CSS transitions and hover effects
- **Mobile-First**: Responsive design starting from mobile
- **Typography**: Professional font choices with proper hierarchy
- **Accessibility**: Semantic HTML and proper contrast ratios

## 🔧 Advanced Customization

### Adding a Blog Section

To add a blog section, create a new section in `index.html`:

```html
<section id="blog" class="blog">
    <div class="container">
        <h2 class="section-title">Latest Posts</h2>
        <!-- Add blog posts here -->
    </div>
</section>
```

### Adding a Contact Form

Replace the contact links with a functional contact form:

```html
<form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="email" name="email" placeholder="Your Email" required>
    <textarea name="message" placeholder="Your Message" required></textarea>
    <button type="submit">Send Message</button>
</form>
```

### Analytics Integration

Add Google Analytics by inserting the tracking code in the `<head>` section:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 📱 Mobile Optimization

The website is fully responsive and includes:

- Mobile-friendly navigation menu
- Touch-optimized buttons and links
- Readable typography on small screens
- Optimized images for different screen densities
- Fast loading on mobile networks

## 🚀 Deployment Options

### GitHub Pages (Free)
- Automatic deployment from your repository
- Custom domain support
- SSL certificate included
- Global CDN for fast loading

### Alternative Hosting
- **Netlify**: Drag and drop deployment with form handling
- **Vercel**: Fast deployment with excellent performance
- **Firebase Hosting**: Google's hosting platform
- **Surge.sh**: Simple static site hosting

## 📞 Support

If you need help customizing your website or run into any issues:

1. Check the GitHub Issues for common problems
2. Review the customization section above
3. Look at the code comments for guidance
4. Create a new issue if you need additional help

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding!** 🎉 Don't forget to star the repository if you found it helpful!

# Future Stars Academy Website

A sleek, mobile-first website for Future Stars Academy, a premier youth baseball training facility for serious players ages 8U+.

## 🏟️ About

Future Stars Academy is dedicated to developing the next generation of baseball stars through comprehensive training programs, professional coaching, and state-of-the-art facilities. Our website showcases our programs, coaches, and success stories with a modern, athletic design.

## 🎨 Design Features

- **Mobile-First Responsive Design**: Optimized for all devices
- **Modern Athletic Aesthetic**: Clean, professional look with navy, red, and white color scheme
- **Smooth Animations**: Intersection Observer animations and parallax effects
- **Fast Loading**: Optimized performance with lazy loading
- **Accessible**: WCAG compliant with keyboard navigation support
- **SEO Optimized**: Proper meta tags and semantic HTML

## 🚀 Quick Start

### Prerequisites
- A modern web browser
- A web server (for deployment)

### Local Development
1. Clone or download the project files
2. Open `index.html` in your web browser
3. For live development, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

## 📁 File Structure

```
FSA/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎯 Website Sections

### 1. Hero Section
- **Location**: Top of page
- **Content**: "Train Like the Pros" tagline with call-to-action buttons
- **Media**: Placeholder for hero video/background image
- **Update**: Replace video placeholder with actual training footage

### 2. About Us
- **Location**: Second section
- **Content**: Mission statement and facility features
- **Media**: Placeholder for facility image
- **Update**: Add real facility photos and update mission statement

### 3. Programs
- **Location**: Third section
- **Content**: Three age divisions (8U-10U, 11U-13U, 14U+)
- **Features**: Program cards with descriptions and booking CTA
- **Update**: Modify program details, pricing, and schedules

### 4. Meet the Coaches
- **Location**: Fourth section
- **Content**: Coach bios with special spotlight on Pedro E. Martinez and Ariel Polonia
- **Media**: Placeholder images for all coaches
- **Update**: Add real coach photos and update bios

#### Featured Coaches:
- **Pedro E. Martinez**: Professional Development Coach with MiLB experience
- **Ariel Polonia**: Travel Ball & Skill Development Coach with extensive experience

### 5. Testimonials & Success Stories
- **Location**: Fifth section
- **Content**: Placeholder testimonials from parents and players
- **Update**: Replace with real testimonials and success stories

### 6. Gallery/Video
- **Location**: Sixth section
- **Content**: Training highlights and gallery
- **Media**: Placeholder for video and images
- **Update**: Add real training videos and photos

### 7. Contact & Lead Capture
- **Location**: Seventh section
- **Content**: Contact form and facility information
- **Features**: Form validation and notification system
- **Update**: Connect form to email service or CRM

## 🖼️ Media Placeholders

The website includes several placeholder elements that need to be replaced with real content:

### Images to Add:
1. **Hero Background**: Training action shot or video
2. **Facility Photos**: Batting cages, pitching mounds, training areas
3. **Coach Photos**: Professional headshots of Pedro E. Martinez and Ariel Polonia
4. **Gallery Images**: Training sessions, player highlights, facility tours
5. **Testimonial Photos**: Player and parent photos (with permission)

### Videos to Add:
1. **Hero Video**: Training montage or facility tour
2. **Gallery Video**: Player highlights or training demonstrations

## 📝 Content Updates

### Easy Updates (No Code Required)
- **Text Content**: Edit directly in `index.html`
- **Contact Information**: Update phone, email, address in contact section
- **Social Media Links**: Update Instagram handles
- **Program Details**: Modify descriptions and features

### Coach Information Updates
To update coach information, find the relevant sections in `index.html`:

```html
<!-- Pedro E. Martinez Spotlight -->
<div class="coach-spotlight">
    <!-- Update bio, stats, and credentials here -->
</div>

<!-- Ariel Polonia Spotlight -->
<div class="coach-spotlight">
    <!-- Update bio, stats, and credentials here -->
</div>
```

### Social Media Links
Current Instagram handles:
- **Academia Futura Estrellas 46**: @academiafuturaestrellas46
- **Ariel Polonia**: @arielpolonia

### Form Integration
The contact form currently shows a success message. To integrate with email services:

1. **EmailJS**: Add EmailJS integration
2. **Netlify Forms**: Deploy to Netlify for automatic form handling
3. **Custom Backend**: Connect to your own server

## 🚀 Deployment Options

### 1. Netlify (Recommended)
1. Create a Netlify account
2. Drag and drop the project folder to Netlify
3. Your site will be live instantly
4. Enable form handling in Netlify dashboard

### 2. Vercel
1. Create a Vercel account
2. Import the project from GitHub
3. Deploy automatically

### 3. GitHub Pages
1. Push code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch

### 4. Traditional Web Hosting
1. Upload files via FTP/SFTP
2. Ensure `index.html` is in the root directory
3. Configure domain if needed

## 🔧 Customization

### Colors
Update the color scheme in `styles.css`:

```css
:root {
    --primary-color: #1e3a8a;    /* Navy */
    --secondary-color: #dc2626;  /* Red */
    --accent-color: #fbbf24;     /* Gold */
    /* ... other colors */
}
```

### Fonts
The website uses Inter font from Google Fonts. To change:

1. Update the Google Fonts link in `index.html`
2. Modify font-family in `styles.css`

### Animations
Animation settings can be adjusted in `script.js`:

```javascript
const observerOptions = {
    threshold: 0.1,        // Animation trigger threshold
    rootMargin: '0px 0px -50px 0px'  // Animation offset
};
```

## 📱 Mobile Optimization

The website is fully responsive with:
- Mobile-first CSS approach
- Touch-friendly navigation
- Optimized images and videos
- Fast loading on mobile networks

## 🔍 SEO Optimization

The website includes:
- Proper meta tags
- Semantic HTML structure
- Alt text placeholders for images
- Structured data ready for implementation

To improve SEO:
1. Add real images with descriptive alt text
2. Update meta descriptions
3. Add Google Analytics
4. Submit sitemap to search engines

## 🛠️ Technical Features

### JavaScript Functionality
- Mobile navigation toggle
- Smooth scrolling navigation
- Form validation and submission
- Intersection Observer animations
- Parallax effects
- Notification system
- Scroll-to-top button
- Keyboard navigation support

### CSS Features
- CSS Grid and Flexbox layouts
- CSS Custom Properties (variables)
- Smooth transitions and animations
- Mobile-first responsive design
- Modern CSS features (backdrop-filter, etc.)

## 📞 Support & Updates

### Adding New Sections
To add new sections:
1. Add HTML structure to `index.html`
2. Add corresponding CSS to `styles.css`
3. Add any JavaScript functionality to `script.js`

### Performance Optimization
- Images are optimized for web
- CSS and JS are minified-ready
- Lazy loading implemented for images
- Efficient animations using CSS transforms

## 🎯 Next Steps

1. **Add Real Content**: Replace all placeholder content with actual information
2. **Integrate Forms**: Connect contact form to email service
3. **Add Analytics**: Implement Google Analytics or similar
4. **Optimize Images**: Compress and optimize all images
5. **Add Blog/News**: Consider adding a blog section for updates
6. **Booking System**: Integrate online booking functionality
7. **Social Media**: Add more social media integration

## 📄 License

This website template is created for Future Stars Academy. Customize as needed for your specific requirements.

---

**Future Stars Academy** - Train Like the Pros, Become a Champion! 🏆 
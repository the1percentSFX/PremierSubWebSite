# Commercial Construction Subcontractor Website

A modern, responsive website template designed specifically for commercial construction subcontractor businesses. Features a professional design with mobile-first approach, smooth animations, and conversion-focused layout.

## 🚀 Features

- **Responsive Design**: Mobile-first approach that looks great on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **SEO Optimized**: Semantic HTML structure with proper meta tags
- **Fast Loading**: Optimized CSS and JavaScript for quick page loads
- **Interactive Elements**: Smooth scrolling, mobile menu, form validation
- **Contact Form**: Professional contact form with validation
- **Service Showcase**: Dedicated sections for different construction services
- **Credibility Building**: Sections for licenses, insurance, and testimonials

## 📁 Project Structure

```
construction-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

### Option 1: Simple Setup (Recommended)
1. Download or clone this repository
2. Open `index.html` in your web browser
3. The website is ready to use!

### Option 2: Local Development Server
1. Install a local server (optional but recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have it installed)
   npx serve .
   
   # Using PHP (if you have it installed)
   php -S localhost:8000
   ```
2. Open your browser and navigate to `http://localhost:8000`

## ✏️ Customization Guide

### 1. Company Information
Replace placeholder content in `index.html`:

**Company Name & Logo:**
```html
<!-- Line 28: Update company name -->
<h2>YourCompany LLC</h2>

<!-- Line 7: Update page title -->
<title>Your Company Name | Professional Construction Subcontractor</title>
```

**Contact Information:**
```html
<!-- Lines 150-170: Update contact details -->
<p>(555) 123-4567</p>                    <!-- Phone -->
<p>info@yourcompanyllc.com</p>           <!-- Email -->
<p>Greater Metropolitan Area</p>          <!-- Service Area -->
```

### 2. Services Customization
Update the services section (lines 80-140) to match your specialties:

```html
<!-- Example: Replace "Electrical Work" with your service -->
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-bolt"></i>  <!-- Change icon -->
    </div>
    <h3>Your Service Name</h3>
    <p>Your service description...</p>
    <ul>
        <li>Service feature 1</li>
        <li>Service feature 2</li>
        <!-- Add more features -->
    </ul>
</div>
```

**Available Icons (Font Awesome):**
- `fas fa-bolt` - Electrical
- `fas fa-wrench` - Plumbing
- `fas fa-wind` - HVAC
- `fas fa-hard-hat` - General Construction
- `fas fa-hammer` - Carpentry
- `fas fa-paint-roller` - Painting
- `fas fa-tools` - General Tools

### 3. Color Scheme
Modify colors in `styles.css`:

```css
/* Primary brand color (blue) */
:root {
    --primary-color: #2563eb;    /* Change this */
    --secondary-color: #f59e0b;  /* Orange accent */
    --dark-color: #1e293b;       /* Dark text */
    --light-color: #f8fafc;      /* Light background */
}
```

### 4. Hero Section
Update the hero content (lines 35-65):

```html
<h1 class="hero-title">Your Custom Headline</h1>
<p class="hero-subtitle">Your company description...</p>

<!-- Update statistics -->
<div class="stat">
    <h3>15+</h3>                 <!-- Your years -->
    <p>Years Experience</p>
</div>
```

### 5. About Section
Customize your company story (lines 145-200):

```html
<h2>Your Company Story</h2>
<p class="lead">Your unique value proposition...</p>
<p>Detailed company description...</p>
```

### 6. Adding Your Logo
1. Save your logo as `logo.png` in the project folder
2. Replace the text logo in `index.html`:

```html
<!-- Replace this: -->
<h2>YourCompany LLC</h2>

<!-- With this: -->
<img src="logo.png" alt="Your Company Logo" style="height: 40px;">
```

### 7. Adding Real Images
Replace image placeholders:

1. Add your images to the project folder
2. Update the about section image:

```html
<!-- Replace the placeholder div with: -->
<img src="your-team-photo.jpg" alt="Our Construction Team" style="width: 100%; border-radius: 16px;">
```

## 📱 Mobile Optimization

The website is fully responsive and includes:
- Mobile-friendly navigation menu
- Touch-optimized buttons and forms
- Responsive grid layouts
- Optimized font sizes for mobile
- Fast loading on mobile networks

## 🔧 Advanced Customization

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation menu if needed

### Form Integration
The contact form currently shows a success message. To integrate with a backend:

1. **Using Formspree (Easy):**
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
   ```

2. **Using Netlify Forms:**
   ```html
   <form netlify class="contact-form">
   ```

3. **Custom Backend:**
   Modify the form submission handler in `script.js` (line 85)

### SEO Optimization
1. Update meta descriptions in `<head>`
2. Add structured data for local business
3. Optimize images with alt text
4. Add Google Analytics tracking code

## 🌐 Deployment Options

### 1. Netlify (Recommended - Free)
1. Create account at [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site is live!

### 2. GitHub Pages (Free)
1. Create GitHub repository
2. Upload files
3. Enable GitHub Pages in settings

### 3. Traditional Web Hosting
1. Upload files via FTP to your hosting provider
2. Point domain to the hosting directory

## 📞 Support & Customization

### Quick Customization Checklist
- [ ] Update company name and contact info
- [ ] Replace placeholder text with your content
- [ ] Customize services to match your offerings
- [ ] Add your logo and images
- [ ] Update colors to match your brand
- [ ] Test on mobile devices
- [ ] Set up contact form integration
- [ ] Deploy to web hosting

### Need Help?
This template is designed to be easily customizable. Most changes can be made by editing the HTML content and CSS colors. No advanced technical knowledge required!

### Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 📄 License

This template is free to use for commercial and personal projects. Attribution appreciated but not required.

---

**Ready to launch your construction business online? Start customizing today!**

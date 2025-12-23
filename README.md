# Melur Athletic Academy Website

A professional, modern, and motivational website for Melur Athletic Academy located at Govt Arts and Science College, Melur, Madurai, Tamil Nadu, India.

## Features

- **Modern Design**: Sports-focused design with bold typography and energetic color scheme
- **Fully Responsive**: Mobile-friendly layout that works on all devices
- **Fast Loading**: Optimized for performance
- **Multiple Pages**: Complete website with all required sections
- **Interactive Elements**: Smooth scrolling, mobile menu, gallery filters, contact form

## Pages

1. **Home** (`index.html`) - Hero section with motivational slogan "Train Hard. Serve Strong. Achieve Excellence."
2. **About Us** (`about.html`) - Mission, vision, and coaching philosophy
3. **Training Programs** (`programs.html`) - Detailed information about all training programs
4. **Why Choose Us** (`why-choose-us.html`) - Key differentiators and core values
5. **Gallery** (`gallery.html`) - Training photos with filter functionality
6. **Achievements** (`achievements.html`) - Success stories and testimonials
7. **Contact** (`contact.html`) - Contact information and enquiry form

## Design

- **Color Scheme**: Red (#DC143C), Black (#1a1a1a), Dark Blue (#1e3a8a), White (#ffffff)
- **Typography**: Oswald (headings) and Roboto (body text)
- **Style**: Strong, disciplined, energetic, and inspirational

## Setup Instructions

1. **Basic Setup**: Simply open `index.html` in a web browser to view the website
2. **Local Server** (Recommended): Use a local server for better performance:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
3. **Deployment**: Upload all files to your web hosting service

## Customization

### Update Contact Information

Edit the contact details in all HTML files:
- Phone number: Replace `+91 XXXXXXXXXX` with actual number
- WhatsApp: Update the WhatsApp link with actual number
- Location: Already set to "Govt Arts and Science College, Melur, Madurai, Tamil Nadu"

### Add Real Images

Replace the placeholder image divs with actual images:
- Update `.image-placeholder` divs in HTML files
- Add images to an `images/` folder
- Update image paths in HTML

### Form Integration

The contact form currently shows a success message. To make it functional:

1. **Formspree** (Easy):
   - Sign up at https://formspree.io
   - Replace form action with your Formspree endpoint
   - Uncomment the fetch code in `script.js`

2. **EmailJS**:
   - Sign up at https://www.emailjs.com
   - Configure email template
   - Add EmailJS script and update form handler

3. **Backend Integration**:
   - Create a backend endpoint to handle form submissions
   - Update the form submission handler in `script.js`

### Google Maps Integration

To add a real map to the contact page:

1. Get Google Maps API key
2. Add this to `contact.html`:
```html
<iframe 
    src="https://www.google.com/maps/embed?pb=YOUR_EMBED_CODE"
    width="100%" 
    height="450" 
    style="border:0;" 
    allowfullscreen="" 
    loading="lazy">
</iframe>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## File Structure

```
melur-athletic-academy/
│
├── index.html              # Home page
├── about.html              # About Us page
├── programs.html           # Training Programs page
├── why-choose-us.html      # Why Choose Us page
├── gallery.html            # Gallery page
├── achievements.html       # Achievements page
├── contact.html            # Contact page
├── styles.css              # Main stylesheet
├── script.js               # JavaScript functionality
└── README.md               # This file
```

## Future Enhancements

- Add Tamil language support
- Integrate with social media
- Add blog/news section
- Implement online enrollment system
- Add payment integration
- Create admin panel for content management

## Notes

- All phone numbers and WhatsApp links use placeholder values (`XXXXXXXXXX`) - update these with actual contact information
- Image placeholders are used throughout - replace with actual training photos
- The form submission is simulated - integrate with a backend service for production use

## License

© 2024 Melur Athletic Academy. All rights reserved.


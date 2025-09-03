# Chem with Dr Em - Static Website Setup

This is a static HTML/CSS/JavaScript version of the Chem with Dr Em website, converted from WordPress and optimized for hosting on Hostinger.

## Files Included

- `index.html` - Main HTML file
- `styles.css` - Complete CSS styling
- `images/` - Directory for image assets (see below)
- `README.md` - This setup guide

## Required Images

You'll need to download and add the following images to the `images/` directory:

### From Original Website:
1. **logo.png** - Main logo (150px max width recommended)
   - Download from: https://www.chemwithdrem.co.uk/wp-content/uploads/2024/09/1.png
   - Save as: `images/logo.png`

2. **hero-banner.png** - Hero section image
   - Download from: https://www.chemwithdrem.co.uk/wp-content/uploads/2024/09/DRM-Banner-Edit3-1.png
   - Save as: `images/hero-banner.png`

3. **signature.png** - Dr. Emma's signature
   - Download from: https://www.chemwithdrem.co.uk/wp-content/uploads/2024/11/Signature_Emma-only_V4-300x131.png
   - Save as: `images/signature.png`

4. **teaching.png** - Teaching service icon
   - Download from: https://www.chemwithdrem.co.uk/wp-content/uploads/2024/09/Teaching.png
   - Save as: `images/teaching.png`

5. **education.png** - Education service icon
   - Download from: https://www.chemwithdrem.co.uk/wp-content/uploads/2024/09/Education.png
   - Save as: `images/education.png`

6. **prizes.png** - Prizes service icon
   - Download from: https://www.chemwithdrem.co.uk/wp-content/uploads/2024/09/prizes.png
   - Save as: `images/prizes.png`

7. **logo-footer.png** - Footer logo
   - Download from: https://www.chemwithdrem.co.uk/wp-content/uploads/2024/09/DREM-LOGO-DBS-New-300x148.png
   - Save as: `images/logo-footer.png`

### Additional Assets:
8. **favicon.png** - Browser favicon (32x32 or 64x64 recommended)
   - Download from: https://www.chemwithdrem.co.uk/wp-content/uploads/2024/09/DREM-FAVICON.png
   - Save as: `images/favicon.png`

## Features

✅ Clean, modern design
✅ Fully responsive (mobile-friendly)
✅ No calendar/availability section (excluded as requested)
✅ Fast loading (static HTML/CSS)
✅ SEO optimized meta tags
✅ Social media integration
✅ Contact form (static - you'll need form processing)

## Setup Instructions for Hostinger

### Step 1: Upload Files
1. Log in to your Hostinger hosting account
2. Access the File Manager
3. Navigate to the `public_html` directory (or your website's root directory)
4. Upload all files:
   - `index.html`
   - `styles.css`
   - `README.md`
   - Entire `images/` directory with all images

### Step 2: Ensure File Structure
Your file structure should look like this:
```
public_html/
├── index.html
├── styles.css
├── README.md
└── images/
    ├── logo.png
    ├── hero-banner.png
    ├── signature.png
    ├── teaching.png
    ├── education.png
    ├── prizes.png
    ├── logo-footer.png
    └── favicon.png
```

### Step 3: Set Permissions (Optional)
Make sure files have the correct permissions:
- Files: 644
- Directories: 755

### Step 4: Set Up Domain
1. In Hostinger, go to "Domains"
2. Point your domain (chemwithdrem.co.uk) to your hosting account
3. Ensure the domain is set as the primary domain

### Step 5: Test Your Website
1. Visit your domain in a web browser
2. Test on different devices (mobile, tablet, desktop)
3. Test all links and modal popups

## Contact Form Processing

The contact form is currently static HTML. To make it functional, you'll need to:

### Option 1: Use Hostinger's Form Builder
1. Go to your Hostinger control panel
2. Use their built-in form processing service
3. Update form action to point to their endpoint

### Option 2: Set up PHP processing
1. Create a `mailto` form action
2. Or set up a simple PHP processor

### Option 3: Use a third-party service
- Formspree
- Netlify Forms (if using Netlify instead of Hostinger)
- Contact Form 7 (WordPress integration)

## Customization

### Colors
Main brand colors are defined in CSS variables:
- Primary: #00afee (blue)
- Secondary: #2a66bc (darker blue)
- Accent: #7f8ad9 (purple-blue)

### Content
To modify content, edit `index.html`:
- Hero section text
- About section content
- Service descriptions
- Contact information
- Social media links

### Styling
Modify `styles.css` for:
- Color scheme changes
- Spacing adjustments
- Font changes
- Layout modifications

## Technical Notes

### Browser Compatibility
✅ Chrome 70+
✅ Firefox 65+
✅ Safari 12+
✅ Edge 79+
✅ Mobile browsers

### Performance
- No external dependencies (except Google Fonts)
- Minimal JavaScript (only for modals and testimonials)
- Optimized images recommended (WebP format if supported)

### SEO
- Meta tags included
- Semantic HTML structure
- Clean URLs possible with Hostinger

## Support

If you encounter any issues:
1. Check that all image files are uploaded correctly
2. Verify file paths in the code
3. Test with different browsers
4. Check Hostinger's file permissions

## Notes

- The original WordPress calendar/availability section has been completely removed
- All social media links point to the original profiles
- The site uses modern CSS Grid and Flexbox for responsive design
- No database required - completely static

---

**Ready to host?** Upload these files to your Hostinger account and your website will be live!

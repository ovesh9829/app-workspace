# Onside Line Boring & Welding Services - Website

A professional, mobile-friendly business website for an industrial service company based in Chittorgarh, Rajasthan, India.

## Features

- ✅ Fully responsive mobile-first design
- ✅ Industrial theme with black, yellow, and dark grey color scheme
- ✅ SEO optimized with meta tags and keywords
- ✅ WhatsApp integration for instant inquiries
- ✅ Sticky call button for mobile users
- ✅ Smooth scrolling navigation
- ✅ Professional gallery section
- ✅ Google Maps integration
- ✅ Fast loading performance

## Customization Guide

### Contact Information (currently set)

- **Primary:** +91 73571 00108, +91 98299 48788, +91 79761 26013  
- **Emergency:** +91 98299 48788  
- **WhatsApp:** +91 73571 00108  
- **Email:** onsidelineboring@gmail.com  
- **Address:** Chittorgarh – 312001, Rajasthan, India  

To change numbers or email, search in `index.html` for the current values and replace.

### Google Maps Location

Update the Google Maps embed with your actual business location:

1. Go to [Google Maps](https://www.google.com/maps)
2. Search for your business location
3. Click "Share" → "Embed a map"
4. Copy the iframe code
5. Replace the iframe in the Contact section of `index.html` (around line 300)

### Gallery

- **25 images:** Currently using professional industrial stock images from Unsplash. To use your own work photos, replace each `src="https://images.unsplash.com/..."` with your image path (e.g. `src="images/photo1.jpg"`).
- **3 videos:** Placeholder divs are shown. To add real videos, replace each `.gallery-video .video-placeholder` block with an `<iframe>` (YouTube/Vimeo embed) or `<video>` tag.

### Business Information

Update any business-specific information in:
- Hero section text
- About Us section
- Service descriptions
- Footer information

## File Structure

```
├── index.html      # Main HTML file
├── styles.css      # All styling and responsive design
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized CSS with minimal dependencies
- Lazy loading support for images
- Debounced scroll events
- Efficient animations
- Fast loading times

## SEO Keywords Included

- Onsite Line Boring in Rajasthan
- Excavator Repair in Chittorgarh
- Heavy Earthmover Welding Service
- Line Boring Chittorgarh
- Excavator Pin Repair
- Hydraulic Repair Rajasthan
- Onsite Machine Maintenance
- Earthmover Repair Service

## Color Scheme

- **Primary Black**: `#1a1a1a`
- **Dark Grey**: `#2d2d2d`
- **Yellow**: `#ffd700`
- **Yellow Dark**: `#ffb800`

## Deployment

1. Upload all files to your web hosting server
2. Ensure `index.html` is in the root directory
3. Test all phone links and WhatsApp links
4. Verify Google Maps is displaying correctly
5. Test on mobile devices

## Notes

- The website uses Google Fonts (Roboto & Oswald) - ensure internet connection for fonts to load
- Replace placeholder content with actual business information
- Add real images to the gallery section for better visual appeal
- Consider adding Google Analytics for tracking visitor behavior
- Test all contact links before going live

## Support

For any customization needs or questions, refer to the code comments in each file.

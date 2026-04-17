# OSS Rent Car - Premium Landing Page

A modern, responsive, and conversion-focused landing page for OSS Rent Car, a car rental business in Salé, Morocco. Built with vanilla HTML, CSS, and JavaScript for maximum performance and minimal dependencies.

## Features

✨ **Modern Premium Design**
- Elegant dark theme with gold accents
- Smooth animations and transitions
- Glass morphism cards and effects
- Professional typography hierarchy
- Mobile-first responsive design

🌐 **Multilingual Support**
- French and English language toggle
- localStorage persistence
- Dynamic content switching
- SEO-ready structure

📱 **Conversion-Focused**
- Direct contact CTAs (WhatsApp, Phone, Instagram, Maps)
- Floating action buttons for quick contact
- Multiple CTA sections strategically placed
- Clear value proposition on hero

🎯 **Key Sections**
- Hero with car showcase
- About & trust indicators
- "Why Choose Us" with 6 advantages
- "How It Works" step-by-step guidance
- Vehicle gallery (categories with descriptions)
- Business hours
- FAQ accordion
- Contact section with embedded map
- Final conversion banner

⚡ **Performance**
- Pure HTML/CSS/JavaScript (no frameworks)
- Lazy loading for images
- Optimized animations
- Fast load times
- Deploy-ready for Vercel/GitHub Pages

♿ **Accessibility**
- Semantic HTML structure
- Proper ARIA labels
- Keyboard navigation support
- Color contrast compliance
- Focus states on all interactive elements

## Project Structure

```
├── index.html                    # Main HTML file with all content
├── assets/
│   ├── images/
│   │   ├── oss-logo.jpeg        # Company logo
│   │   ├── hero-car-display.png # Car showcase image
│   │   └── favicon.ico          # Favicon
│   ├── styles/
│   │   └── styles.css           # All styles (responsive)
│   └── scripts/
│       ├── translations.js      # Multilingual system
│       └── script.js            # Core functionality
├── vercel.json                   # Vercel deployment config
└── README.md                     # This file
```

## Quick Start

### Local Development

1. **Direct in Browser**
   Simply open `index.html` in your browser.

2. **Local Server (Recommended)**
   ```bash
   # Using Python
   python -m http.server 8080

   # Using Node.js http-server
   npx http-server

   # Using PHP
   php -S localhost:8080
   ```
   Then open `http://localhost:8080`

## Deployment

### Deploy to Vercel (Recommended)

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: OSS Rent Car landing page"
   git remote add origin https://github.com/YOUR_USERNAME/oss-rent-car.git
   git push -u origin main
   ```

2. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Sign in with GitHub
   - Click "New Project"
   - Select the repository
   - Leave default settings (they're pre-configured in `vercel.json`)
   - Click "Deploy"

3. **Done!** Your site is live at `https://your-project.vercel.app`

### Deploy to GitHub Pages

1. **Create GitHub repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/oss-rent-car.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to "Pages"
   - Set source to "main" branch
   - Save
   - Site will be live at `https://YOUR_USERNAME.github.io/oss-rent-car`

## Customization

### Update Contact Information

Edit these values in `index.html`:
- Phone/WhatsApp: `+212661184154` → your number
- Instagram: `oss_rent_car` → your handle
- Address: Update in contact section and map
- Logo: Replace `assets/images/oss-logo.jpeg`
- Car image: Replace `assets/images/hero-car-display.png`

### Update Text Content

- **French**: Edit `<p data-tr="...">`  tags directly in HTML or in `translations.js`
- **English**: Update English translations in `assets/scripts/translations.js`

### Update Styles

All styles are in `assets/styles/styles.css`. Key customization points:
- **Colors**: CSS variables at top of file (`:root`)
- **Typography**: Font families and sizes
- **Spacing**: Padding and margins
- **Animations**: Transitions and keyframes

### Language Toggle

The language toggle uses localStorage to remember user preference. Languages available:
- Français (FR) - Default
- English (EN)

Add new language:
1. Add translations to `translations.js`
2. Add language option to `lang-toggle` class in HTML
3. Update JS language detection

## SEO

### Metadata
- Title: "OSS Rent Car | Location Premium à Salé, Maroc"
- Description: Optimized with keywords
- Open Graph tags for social sharing
- Canonical tag for SEO
- JSON-LD structured data (local business)

### SEO Improvements Included
- Semantic HTML structure
- Proper heading hierarchy
- Image alt texts
- Meta descriptions
- Mobile-first design
- Fast loading times
- Accessibility compliance

### To Improve SEO Further
1. Add your Google Business Profile
2. Submit sitemap to Google Search Console
3. Monitor search performance
4. Build backlinks
5. Create content marketing strategy

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari 14+, Chrome Mobile)

## Accessibility

- ✓ WCAG 2.1 AA compliant
- ✓ Keyboard navigation (Tab, Enter, Esc)
- ✓ Screen reader friendly (ARIA labels)
- ✓ Color contrast ratios met
- ✓ Focus indicators visible
- ✓ Semantic HTML

## Performance

- Load time: ~1-2s (depending on connection)
- Lighthouse score: 90+
- Mobile-friendly
- No frameworks/jQuery
- Minimal external dependencies (only Font Awesome for icons)

## Business Contact Details

**OSS Rent Car**
- 📞 Phone/WhatsApp: +212 661 184 154
- 📧 Instagram: @oss_rent_car
- 📍 Address: N1764 Lot. Sidi Abdellah Sct. El Fath, Laayayda, Salé 11000
- 🌍 Location: Salé, Morocco

## Technical Stack

- **HTML5**: Semantic markup
- **CSS3**: Responsive design, animations, glass morphism
- **JavaScript (Vanilla)**: No frameworks
- **Font Awesome 6.4**: Icon library
- **Google Fonts**: Typography
- **Google Maps**: Embedded map
- **Smooth Scroll**: Native browser API

## License

This project is proprietary. All rights reserved for OSS Rent Car.

## Support & Maintenance

### Regular Maintenance Checklist
- [ ] Update contact info quarterly
- [ ] Check for broken links monthly
- [ ] Monitor page speed with Lighthouse
- [ ] Update social media links if changed
- [ ] Test on new browser versions
- [ ] Backup website monthly

### Common Issues & Solutions

**Map not loading?**
- Check internet connection
- Verify address in embed code
- Wait for Maps API to load

**Language not switching?**
- Clear browser cache
- Check localStorage is enabled
- Verify translations.js is loaded

**Images not showing?**
- Verify file paths are correct
- Check image files exist in assets/images/
- Ensure filenames match exactly (case-sensitive)

## Future Enhancements

- [ ] Add testimonials slider
- [ ] Integrate booking calendar
- [ ] Add live chat widget
- [ ] Email newsletter signup
- [ ] Photo gallery modal
- [ ] Dark/Light theme toggle
- [ ] Performance analytics tracking
- [ ] A/B testing for CTAs

---

**Last Updated**: April 2024  
**Version**: 2.0 (Multilingual + "How It Works")  
**Maintained by**: OSS Rent Car Team

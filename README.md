# EIN Fuel Extraction

Emergency wrong fuel recovery service across New Zealand.

## About

EIN Fuel Extraction provides certified, insured fuel decontamination and system recovery services. We extract contaminated fuel, inspect damage, and neutralize risk for petrol in diesel or diesel in petrol incidents.

**Website:** https://www.ein.nz

## Project Structure

Single-page static website with no build process required. All assets are in the root directory.

### Features

- Single-page HTML/CSS/JavaScript application
- Mobile-first responsive design
- Real-time phone availability status
- Google Analytics and Reddit Pixel tracking
- SEO optimized with structured data
- Security headers configured

## Website

The site provides:
- Emergency service contact information
- Service process information (Extract, Inspect, Neutralize)
- Trust indicators and certifications
- 24/7 nationwide coverage information
- Dynamic phone number display based on availability

## Deployment

This is a static site that can be deployed to any static hosting service:

- **Netlify** (recommended - uses `_headers` file)
- **GitHub Pages** (uses `CNAME` file)
- **AWS S3 + CloudFront**
- **Azure Static Web Apps**
- **Vercel**
- **Cloudflare Pages**

### Deployment Notes

- The `_headers` file is for Netlify configuration
- The `CNAME` file is for GitHub Pages custom domain
- No build process required - deploy files as-is

## Files

- `index.html` - Main website page (single-page application)
- `favicon.ico` - Site favicon
- `EIN Brand Image.png` - Logo image used in header and structured data
- `sitemap.xml` - XML sitemap for search engines
- `robots.txt` - Robots exclusion protocol
- `_headers` - Security headers for Netlify deployment
- `CNAME` - Custom domain configuration (www.ein.nz) for GitHub Pages
- `.gitignore` - Git ignore rules

## Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, flexbox, grid
- **Vanilla JavaScript** - No frameworks, ES6+
- **Google Analytics** - AW-17084465163, G-DQNKF1YLWR
- **Reddit Pixel** - Conversion tracking
- **Google Fonts** - Inter font family

## API Integration

The site integrates with:
- Power Platform API for phone availability status
- Google Analytics for tracking
- Reddit Pixel for conversion tracking

## Contact

**Emergency Service:** 04 887 3331

**Parent Company:** Forman Pacific (https://www.formanpacific.com)

## License

© 2025 Forman Pacific. EIN Fuel Extraction is a division of Forman Pacific. All rights reserved.

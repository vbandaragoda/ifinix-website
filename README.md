# IFINITY Website - HTML/CSS Structure

This is an organized copy of the IFINITY website saved from WordPress. It serves as a reference for the ReactJS development team to understand the content structure, styling, and animations.

## Project Structure

```
ifinix-website/
├── index.html                 # Entry point (redirects to home page)
├── README.md                  # This file
├── pages/                     # All HTML pages
│   ├── home.html             # Home page
│   ├── about.html            # About page
│   ├── capabilities.html     # Capabilities page
│   ├── careers.html          # Careers page
│   └── news.html             # News page
└── assets/                    # All website assets
    ├── css/                   # CSS stylesheets
    │   ├── admin-bar.min.css
    │   ├── dashicons.min.css
    │   ├── dflip.min.css
    │   ├── intlTelInput.min.css
    │   ├── countrySelect.min.css
    │   ├── style.min.css
    │   ├── styles__ltr.css
    │   ├── styles.css
    │   ├── jquery.fancybox.min.css
    │   ├── home.min.css
    │   └── ... (other CSS files)
    ├── js/                    # JavaScript files
    │   ├── (all library scripts)
    │   └── (page-specific scripts)
    └── (images, videos, and other media files)
```

## Pages Overview

### 1. **Home** (`pages/home.html`)
- Hero banner with video background
- "What We Do" section
- "Two in One" section with capabilities slider
- Call-to-action buttons
- Animations and transitions

### 2. **About** (`pages/about.html`)
- Company information and core banking solutions
- Company history and background
- Team and organizational details

### 3. **Capabilities** (`pages/capabilities.html`)
- Banking Applications
- Integration and Automation
- Data and AI
- Security, Risk, and Compliance
- Cloud Services
- IFINITY Products
- Support Services
- Managed Services

### 4. **Careers** (`pages/careers.html`)
- Job opportunities
- Company culture
- Career growth information

### 5. **News** (`pages/news.html`)
- Latest news and updates
- Blog posts or announcements

## How to View

1. **Open in Browser**: Simply open `index.html` in a web browser, which will redirect to the home page
2. **Or navigate directly**: Open any page from the `pages/` folder directly:
   - `pages/home.html`
   - `pages/about.html`
   - `pages/capabilities.html`
   - `pages/careers.html`
   - `pages/news.html`

## Key Features Preserved

- ✅ **Navigation Bar**: Sticky navigation with site logo and menu links
- ✅ **Footer**: Consistent footer with copyright and company information
- ✅ **Animations**: Scroll animations, transitions, and interactive elements
- ✅ **Styling**: All original CSS and styling preserved
- ✅ **Media**: All images, videos, and multimedia elements
- ✅ **Google Fonts**: Font imports and web typography
- ✅ **Third-party Libraries**: Owl Carousel, FancyBox, and other dependencies

## Asset References

All asset paths have been updated to point to the centralized `assets/` folder:
- CSS files are in `assets/css/`
- JavaScript files are in `assets/js/`
- Images and media are in `assets/` (organized by subdirectories)

## Important Notes for ReactJS Development

1. **External URLs**: Some assets still reference external CDN URLs (Google Fonts, Google Tag Manager, etc.)
2. **Videos**: Some video sources link to external Vimeo URLs with specific signature parameters
3. **Animations**: Custom animations are defined in CSS files - review `home.min.css`, `style.min.css` for animation patterns
4. **Component Structure**: The HTML maintains semantic structure with sections like:
   - Headers and navigation
   - Hero sections
   - Content sections (capabilities, features)
   - Call-to-action buttons
   - Carousels/sliders
   - Forms
   - Footer

## Development Guidelines

When converting to ReactJS:
- Decompose each section into reusable React components
- Migrate CSS to CSS modules, styled-components, or Tailwind CSS
- Extract animation patterns and convert to appropriate React animation libraries
- Maintain the navigation structure and page hierarchy
- Preserve all content and styling details
- Test responsive design across all breakpoints

## File Sizes & Optimization

- CSS is minified (`.min.css`)
- JavaScript is minified and optimized
- Images are optimized but not compressed for the web

---

**Created for**: ReactJS development team reference
**Last Updated**: 2026-06-22

# IFINITY Website - HTML/CSS Structure

This is an organized copy of the IFINITY website saved from WordPress. It serves as a reference for the ReactJS development team to understand the content structure, styling, and animations.

---

## 📁 Project Structure

```text
ifinix-website/
├── index.html                 # Entry point (redirects to home page)
├── README.md                  # This file
├── pages/
│   ├── home.html              # Home page
│   ├── about.html             # About page
│   ├── capabilities.html      # Capabilities page
│   ├── careers.html           # Careers page
│   └── news.html              # News page
└── assets/
    ├── css/
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
    ├── js/
    │   ├── (all library scripts)
    │   └── (page-specific scripts)
    └── (images, videos, and other media files)
```

---

## 📄 Pages Overview

### 🏠 Home (`pages/home.html`)

- Hero banner with video background
- "What We Do" section
- "Two in One" section with capabilities slider
- Call-to-action buttons
- Animations and transitions

### 👥 About (`pages/about.html`)

- Company information and core banking solutions
- Company history and background
- Team and organizational details

### ⚙️ Capabilities (`pages/capabilities.html`)

- Banking Applications
- Integration and Automation
- Data and AI
- Security, Risk, and Compliance
- Cloud Services
- IFINITY Products
- Support Services
- Managed Services

### 💼 Careers (`pages/careers.html`)

- Job opportunities
- Company culture
- Career growth information

### 📰 News (`pages/news.html`)

- Latest news and updates
- Blog posts or announcements

---

## 🚀 How to View

### Option 1

Open `index.html` in any web browser.

### Option 2

Open any page directly:

- `pages/home.html`
- `pages/about.html`
- `pages/capabilities.html`
- `pages/careers.html`
- `pages/news.html`

---

## ✨ Key Features Preserved

- ✅ Sticky navigation bar
- ✅ Responsive footer
- ✅ Scroll animations and transitions
- ✅ Original CSS styling
- ✅ Images and video assets
- ✅ Google Fonts
- ✅ Third-party libraries (Owl Carousel, FancyBox, etc.)

---

## 📂 Asset References

All assets have been centralized under the `assets/` directory.

| Asset | Location |
|-------|----------|
| CSS | `assets/css/` |
| JavaScript | `assets/js/` |
| Images | `assets/` |
| Videos | `assets/` |

---

## 📝 Important Notes for ReactJS Development

### External URLs

Some assets still reference external services such as:

- Google Fonts
- Google Tag Manager
- External CDNs

### Videos

Some videos are loaded from Vimeo using signed URLs.

### Animations

Review these files for animation logic:

- `assets/css/home.min.css`
- `assets/css/style.min.css`

### Component Structure

The HTML is already organized into reusable sections:

- Header
- Navigation
- Hero Banner
- Content Sections
- Feature Cards
- Call-to-Action
- Forms
- Footer

---

## 🛠 Development Guidelines

When converting to ReactJS:

- Break each section into reusable components.
- Convert CSS into CSS Modules, Styled Components, or Tailwind CSS.
- Replace jQuery-based interactions with React equivalents.
- Preserve animations and responsive layouts.
- Maintain page hierarchy and navigation.
- Test across desktop, tablet, and mobile devices.

---

## ⚡ Optimization

- CSS is minified.
- JavaScript is minified.
- Images are web optimized.
- Media assets are preserved.

---

## 📌 Purpose

This repository is intended **only as a reference** for rebuilding the IFINITY website in ReactJS.

It preserves:

- Content
- Layout
- Styling
- Animations
- Media assets

while serving as the source for component-based development.

---

**Created for:** ReactJS Development Team

**Last Updated:** 2026-06-22
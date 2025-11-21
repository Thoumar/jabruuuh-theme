# Jabruuuh Theme - One-Product Shopify Theme

A premium, Apple-inspired Shopify theme designed specifically for the Jabruuuh One product. Features a polished, high-tech aesthetic with smooth animations and a modern design language.

## ✨ Features

- **Apple-Inspired Design**: Clean typography, generous whitespace, smooth animations
- **One-Product Focused**: Optimized landing page experience for a single product
- **Fully Responsive**: Mobile-first design that looks great on all devices
- **Theme Editor Support**: Easily customize colors, text, and content through Shopify admin
- **Product Variants**: Full support for product variants with beautiful UI
- **Custom Cart Page**: Apple-aesthetic cart with quantity controls and summary
- **Reviews Ready**: Placeholder integration for Judge.me or similar review apps
- **Scroll Animations**: Smooth fade-in effects on scroll for engaging UX
- **Glassmorphism Header**: Fixed header with backdrop blur effect
- **Dark CTA Section**: High-contrast pricing section for strong conversion

## 📦 What's Included

### Sections
- **Hero Product** - Full-screen hero with product showcase
- **Product Specs** - Grid layout for technical specifications
- **Bento Marketing** - Apple-style bento grid for feature highlights
- **Comparison Table** - Professional comparison with competitors
- **Pricing CTA** - Dark-themed pricing section with trust badges
- **Product Page** - Enhanced product page with gallery and variants
- **Cart** - Beautiful cart page with order summary
- **Header** - Fixed glassmorphism header
- **Footer** - Clean footer with branding

### Templates
- **Homepage** (`index.json`) - Fully configured landing page
- **Product** (`product.json`) - Product detail page
- **Cart** (`cart.json`) - Shopping cart page

### Assets
- `critical.css` - Critical styles with CSS variables
- `theme.css` - Component styles and utilities

### Customization
- Full theme editor support in Shopify admin
- Customizable colors, fonts, spacing through settings
- All text content editable
- Image uploads for product imagery

## 🚀 Getting Started

### Prerequisites
- Shopify store
- Product with handle "jabruuuh-one" (or update references in code)
- Shopify CLI (optional, for local development)

### Installation

1. **Upload to Shopify**
   - Zip the theme folder
   - Upload to Shopify Admin > Themes > Add theme

2. **Or use Shopify CLI**
   ```bash
   cd jabruuuh-theme
   shopify theme push
   ```

3. **Activate Theme**
   - Go to Online Store > Themes
   - Find "Jabruuuh Theme"
   - Click "Publish"

### Initial Setup

1. **Configure Product**
   - Ensure you have a product with handle `jabruuuh-one`
   - Add product images
   - Set up variants if needed
   - Add description

2. **Customize Theme Settings**
   - Go to Theme Editor
   - Customize colors (defaults are Apple-inspired)
   - Update text content in each section
   - Upload product images

3. **Optional: Install Review App**
   - Install Judge.me from Shopify App Store
   - Follow their setup instructions
   - Reviews will automatically appear on product pages

## 🎨 Design System

### Colors
- **Primary Background**: `#FFFFFF`
- **Secondary Background**: `#F5F5F7`
- **Primary Text**: `#1D1D1F`
- **Secondary Text**: `#86868B`
- **Accent**: `#0071E3`
- **Badge**: `#BF4800`

### Typography
- **Font**: Inter (via Google Fonts)
- **Fallback**: System fonts (-apple-system, BlinkMacSystemFont)

### Spacing
- **Section Spacing**: 100px (default)
- **Page Margin**: 24px
- **Border Radius**: 24px

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Mobile**: ≤ 768px

## 🔧 Customization Guide

### Changing Colors
1. Go to Theme Editor
2. Click "Theme settings"
3. Navigate to "Colors" section
4. Adjust colors to match your brand

### Editing Content
1. Go to Theme Editor
2. Click on any section
3. Edit text, images, and settings
4. Save changes

### Adding New Sections
1. In Shopify admin, go to Theme Editor
2. Click "Add section"
3. Choose from available sections
4. Configure settings

## 🔌 Integrations

### Judge.me Reviews
1. Install Judge.me app
2. Reviews will automatically appear on product pages
3. Star ratings show in product section
4. Full reviews display below product details

### Other Apps
Theme is compatible with standard Shopify apps that work with Online Store 2.0.

## 📝 File Structure

```
jabruuuh-theme/
├── assets/
│   ├── critical.css          # Critical styles with design tokens
│   └── theme.css             # Component styles
├── config/
│   ├── settings_schema.json  # Theme customization options
│   └── settings_data.json    # Theme settings values
├── layout/
│   └── theme.liquid          # Main HTML wrapper
├── sections/
│   ├── header.liquid         # Fixed header
│   ├── footer.liquid         # Footer
│   ├── hero-product.liquid   # Hero section
│   ├── product-specs.liquid  # Specs grid
│   ├── bento-marketing.liquid # Bento grid
│   ├── comparison-table.liquid # Comparison
│   ├── pricing-cta.liquid    # Pricing section
│   ├── product.liquid        # Product page
│   └── cart.liquid           # Cart page
├── snippets/
│   ├── scroll-animations.liquid
│   └── judgeme-reviews.liquid
└── templates/
    ├── index.json            # Homepage
    ├── product.json          # Product template
    └── cart.json             # Cart template
```

## 🐛 Troubleshooting

### Product not showing
- Check product handle is "jabruuuh-one"
- Ensure product is published
- Verify product has images

### Styles not loading
- Clear browser cache
- Refresh theme files in Shopify admin
- Check for any liquid errors

### Reviews not showing
- Install Judge.me app
- Configure Judge.me in their settings
- Widget will replace placeholder text

## 📱 Testing Checklist

- [ ] Homepage loads correctly
- [ ] Product page displays properly
- [ ] Add to cart works
- [ ] Cart page functions
- [ ] Checkout process works
- [ ] Mobile responsive
- [ ] Animations work smoothly
- [ ] All links functional
- [ ] Forms submit correctly
- [ ] Cross-browser compatible

## 📄 Best Practices

### Images
- Use high-quality product images (at least 2000px wide)
- Optimize images before uploading
- Use WebP format when possible

### Performance
- Minimize installed apps
- Use Shopify's image CDN
- Enable browser caching

### SEO
- Add product descriptions
- Use descriptive image alt text
- Configure meta tags in theme settings

---

**Built with ❤️ for Jabruuuh**

*Based on Shopify Skeleton Theme*

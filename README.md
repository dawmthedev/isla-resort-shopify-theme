# Isla Resort Shopify Theme

A minimalist, modern Shopify theme designed specifically for Isla Resort's women's fashion boutique. This theme emphasizes simplicity, functionality, and aesthetics to create an engaging shopping experience.

## Features

### Modern Shopify Capabilities
- Full Online Store 2.0 compatibility
- Sections Everywhere technology for maximum customization
- Enhanced storefront filtering system
- Dynamic metafield support for rich product information
- Performance-optimized for fast loading times

### Design Elements
- Clean, minimalist aesthetic with white background
- Custom typography using Neulis Sans and Neulis Sans Bold
- Responsive design principles for all device sizes
- WCAG 2.1 compliant accessibility features

### Key Components
- Dynamic homepage sections
  - Full-width hero banner with text overlay
  - Featured collections grid
  - "Shop the Look" product showcase
  - Newsletter signup integration
- Streamlined product pages
  - High-resolution image gallery with zoom capability
  - Video and 3D model support
  - Clear product information hierarchy
  - Prominent add-to-cart functionality
- Enhanced Navigation
  - Clean header with dropdown collections
  - Organized footer with policy links and social media
  - Intuitive mobile navigation

## Development Setup

1. Install Shopify CLI 3.72.2:
```bash
npm install -g @shopify/cli @shopify/theme
```

2. Clone the repository:
```bash
git clone https://github.com/[username]/isla-resort-shopify-theme.git
cd isla-resort-shopify-theme
```

3. Authenticate with Shopify:
```bash
shopify auth login --store=your-store.myshopify.com
```

4. Start development server:
```bash
shopify theme dev
```

## Project Structure

```
isla-resort-shopify-theme/
├── assets/
│   ├── fonts/
│   ├── scripts/
│   └── styles/
├── config/
├── layout/
├── locales/
├── sections/
├── snippets/
└── templates/
    └── customers/
```

## Accessibility

This theme is built with accessibility as a core principle, following WCAG 2.1 guidelines:
- Semantic HTML structure
- ARIA labels where necessary
- Keyboard navigation support
- High contrast ratios
- Screen reader compatibility

## Performance

The theme is optimized for performance with:
- Lazy loading for images
- Minified CSS and JavaScript
- Responsive image sizing
- Efficient asset loading
- Core Web Vitals optimization

## Contributing

1. Create a feature branch:
```bash
git checkout -b feature/your-feature-name
```

2. Make your changes and commit:
```bash
git commit -m "Description of changes"
```

3. Push to GitHub:
```bash
git push origin feature/your-feature-name
```

4. Open a Pull Request with a detailed description of changes

## License

[License details to be added]
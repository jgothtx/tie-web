# The Intelligent Enterprise

A static marketing website for "The Intelligent Enterprise: An Executive's Guide to AI and Data" by Jason Goth and Vincent Yates.

## 📖 About

This website serves as the marketing hub for The Intelligent Enterprise book, providing visitors with information about the book, authors, and downloadable resources including sample chapters and checklists.

## 🚀 Features

- **Responsive Design**: Mobile-first approach using Bootstrap 5
- **Book Information**: Detailed description and purchase links
- **Author Profiles**: Information about Jason Goth and Vincent Yates
- **Free Resources**: Downloadable PDF sample chapter and checklist
- **Social Media Integration**: Open Graph tags for sharing
- **SEO Optimized**: Meta tags and semantic HTML structure

## 🛠️ Technology Stack

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with modern features
- **Bootstrap 5**: Responsive framework and components
- **Bootstrap Icons**: Icon library
- **Static Hosting**: No server-side dependencies

## 📁 Project Structure

```
tie-web/
├── index.html              # Main landing page
├── styles.css              # Custom CSS styles
├── CLAUDE.md               # Development guidelines
├── README.md               # Project documentation
├── images/                 # Image assets
│   ├── book-cover.jpg      # Book cover image
│   ├── Jason_Goth_square.jpg
│   └── Vincent_Yates_square.jpg
└── downloads/              # Downloadable resources
    ├── intelligent-enterprise-sample-chapter.pdf
    └── intelligent-enterprise-checklist.pdf
```

## 🏃‍♂️ Getting Started

### Prerequisites

- A modern web browser
- Basic text editor (VS Code recommended)

### Local Development

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd tie-web
   ```

2. **Open in browser**
   ```bash
   # Simply open the index.html file in your browser
   open index.html
   # Or on Windows
   start index.html
   # Or on Linux
   xdg-open index.html
   ```

3. **Alternative: Use a local server**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (if you have http-server installed)
   npx http-server
   
   # Then visit http://localhost:8000
   ```

## 🎨 Customization

### Styling

The website uses a combination of Bootstrap 5 and custom CSS:

- **Bootstrap**: Provides responsive grid, components, and utilities
- **Custom CSS**: Located in `styles.css` for brand-specific styling
- **Color Scheme**: Primary blue (#0070ad) for call-to-action elements

### Content Updates

- **Book Information**: Edit the hero and about sections in `index.html`
- **Author Bios**: Update the authors section
- **Resources**: Add new PDFs to the `downloads/` folder and update links
- **Images**: Replace images in the `images/` folder (maintain aspect ratios)

## 🚀 Deployment

### GitHub Pages

1. Push changes to the `main` branch
2. Enable GitHub Pages in repository settings
3. Select "Deploy from a branch" and choose `main`

### Other Static Hosts

The site is compatible with:
- Netlify
- Vercel
- AWS S3 + CloudFront
- Azure Static Web Apps

Simply upload the files or connect your repository.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Make your changes
4. Follow the code style guidelines in `CLAUDE.md`
5. Test on multiple devices/browsers
6. Commit your changes (`git commit -am 'Add new feature'`)
7. Push to the branch (`git push origin feature/new-feature`)
8. Create a Pull Request

## 📝 Code Style

Please refer to `CLAUDE.md` for detailed coding guidelines:

- Use semantic HTML5 elements
- Maintain 2-space indentation
- Follow kebab-case for CSS classes
- Keep the existing color scheme
- Ensure mobile responsiveness

## 📄 License

This project is proprietary and confidential. All rights reserved.

## 📞 Contact

For questions about the website or book:

- **Website**: [theintelligententerprise.ai](https://theintelligententerprise.ai)
- **Purchase**: [Amazon](https://amzn.to/4hEKbJP)


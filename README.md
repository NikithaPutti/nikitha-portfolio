# Nikitha's Portfolio Website

A modern, responsive portfolio website showcasing professional profile, research experience, and projects.

## Features

- 🎨 **Blue and White Color Scheme** - Clean and professional design
- 📱 **Mobile Responsive** - Optimized for all device sizes
- 🎯 **Horizontal Slide Navigation** - Smooth left-to-right page transitions
- 🖼️ **Enlarged Profile Picture** - Prominent display in header
- 🎴 **Card-based Project Display** - Beautiful project cards with hover effects
- ⚡ **Fast Loading** - Optimized with Tailwind CSS CDN
- 🚀 **Automated Deployment** - GitHub Actions + Vercel integration

## Technology Stack

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Vanilla)
- GitHub Pages
- Vercel

## Project Structure

```
ProjectInternship/
├── index.html              # Main portfolio page
├── flowchart.html          # Portfolio structure flowchart
├── PROJECT_ROADMAP.md      # Project roadmap and documentation
├── README.md               # This file
├── vercel.json            # Vercel configuration
└── .github/
    └── workflows/
        └── deploy.yml     # GitHub Actions workflow
```

## Sections

1. **About/Summary** - Professional summary and skills
2. **Research Experience** - Undergraduate research work at SRM University
3. **Projects** - Three featured projects with detailed descriptions
4. **Contact** - Social media links and contact information

## Deployment

### GitHub Pages
The site is automatically deployed to GitHub Pages via GitHub Actions when changes are pushed to the `main` branch.

### Vercel
1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect the configuration and deploy
3. Future pushes will trigger automatic deployments

## Local Development

1. Clone the repository
2. Open `index.html` in a web browser
3. Or use a local server:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## Navigation

- **Desktop**: Use the navigation dots on the right side or arrow keys
- **Mobile**: Use the bottom navigation bar or swipe left/right
- **Keyboard**: Arrow keys (Left/Right) to navigate between slides

## Customization

To update the profile picture, replace the placeholder image URL in `index.html`:
```html
<img src="YOUR_IMAGE_URL" alt="Nikitha Profile Picture" class="profile-picture mb-4">
```

Update contact links in the header and contact section with your actual URLs.

## License

© 2024 Nikitha. All rights reserved.


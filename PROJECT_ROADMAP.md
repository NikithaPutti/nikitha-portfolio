# Portfolio Website Project Roadmap

## Project Overview
A modern, responsive portfolio website showcasing Nikitha's professional profile, research experience, and projects. The website will feature a blue and white color scheme with horizontal slide navigation.

## Technology Stack
- **Frontend Framework**: HTML5, CSS3, JavaScript
- **CSS Framework**: Tailwind CSS (via CDN)
- **Deployment**: GitHub Pages + Vercel
- **CI/CD**: GitHub Actions for automated deployment

## Project Structure

```
ProjectInternship/
├── index.html              # Main portfolio page
├── flowchart.html          # Portfolio structure flowchart
├── assets/
│   ├── css/
│   │   └── style.css      # Custom styles
│   ├── js/
│   │   └── main.js        # JavaScript for navigation and interactions
│   └── images/
│       └── profile.jpg    # Profile picture
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions workflow
├── vercel.json            # Vercel configuration
└── README.md              # Project documentation
```

## Features & Sections

### 1. Header Section
- Large profile picture (enlarged)
- Name: Nikitha Putti
- Navigation menu for sections (Sticky top nav)
- Social links (GitHub, LinkedIn, Email) + Phone number

### 2. About/Summary Section
- Professional summary
- Skills overview (Languages, Core Areas, Web Tech, Tools, Soft Skills)

### 3. Education Section
- SRM-AP University
- Bhashyam Junior College
- Allen Group of Schools

### 4. Research Experience Section
- Undergraduate Research Assistant role
- SRM University, Amaravati
- StudyMate project description

### 5. Projects Section
- **Insight Stream** - Web Application
- **Driver Drowsiness Detection** - Machine Learning
- **Online Grocery System** - DBMS, SQL
- **Smart Voice Assistant** - Python
- **Smart Parking System** - C++
- Each project displayed as a card with purple/teal theme

### 6. Contact Section
- Contact info and social links
- Open to roles statement

## Design Specifications

## Design Specifications

### Color Scheme
- **Primary Background**: Deep Purple Gradient (#2e1065 to #4c1d95)
- **Accent**: White & Light Purple (#d8b4fe)
- **Cards**: Glassmorphism (White with transparency and blur)
- **Text**: White (Primary), Light Purple (Secondary)

### Layout Features
- **Single Page Application** with section visibility toggling
- **Live Background**: Animated floating shapes/circles
- **Hero Section**: Centered profile, name, title, and action buttons
- **Navigation**: Sticky top bar with transparent background
- **Profile Picture**: Circular with glowing border
- **Typography**: Google Fonts (Poppins)

## Implementation Phases

### Phase 1: Project Setup ✅
- [x] Create project structure
- [x] Set up Tailwind CSS
- [x] Create roadmap document
- [x] Create flowchart HTML

### Phase 2: Core Structure
- [ ] Create HTML skeleton
- [ ] Implement header with profile picture
- [ ] Create navigation system
- [ ] Set up horizontal slide sections

### Phase 3: Content Sections
- [ ] About/Summary section
- [ ] Research Experience section
- [ ] Projects section with cards
- [ ] Contact section

### Phase 4: Styling & Responsiveness
- [ ] Apply blue and white color scheme
- [ ] Style cards with proper shades
- [ ] Implement mobile responsive design
- [ ] Enlarge and style profile picture

### Phase 5: Interactivity
- [ ] Implement horizontal slide navigation
- [ ] Add smooth transitions
- [ ] Create interactive elements
- [ ] Add scroll animations

### Phase 6: Deployment Setup
- [ ] Configure GitHub Actions
- [ ] Set up Vercel configuration
- [ ] Create deployment scripts
- [ ] Test deployment process

### Phase 7: Testing & Finalization
- [ ] Test on multiple devices
- [ ] Cross-browser testing
- [ ] Performance optimization
- [ ] Final review and fixes

## Deployment Configuration

### GitHub Actions
- Automated build and deploy on push to main branch
- Deploy to GitHub Pages

### Vercel
- Connect GitHub repository
- Automatic deployments on push
- Custom domain support (if needed)

## Timeline
- **Setup & Planning**: Day 1
- **Development**: Day 2-3
- **Styling & Responsiveness**: Day 3-4
- **Deployment & Testing**: Day 4-5

## Notes
- Profile picture should be prominently displayed and enlarged
- Cards should use blue/white gradient or solid blue backgrounds
- Horizontal navigation should be smooth and intuitive
- Mobile-first responsive design approach

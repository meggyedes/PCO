# HZ University ICT Portfolio

A comprehensive portfolio website showcasing my academic journey, progress, and professional development in the HBO-ICT program at HZ University of Applied Sciences. This website serves as both a study progress tracker and a demonstration of web development skills acquired throughout the program.

## 📋 Project Overview

This portfolio website is designed to track and showcase my academic progress in the HBO-ICT program while demonstrating practical web development skills. It features a complete study monitoring system, personal blog, and comprehensive information about my educational journey at HZ University.

## 🌟 Key Features

### 🏠 **Home Page**
- Professional introduction and motivation
- Hero section with engaging visuals
- Quick navigation to key sections
- Overview of academic goals and aspirations

### 👤 **Profile Page**
- Personal and professional information
- Skills and characteristics overview
- Hobbies and interests
- Social media and contact links
- Professional development timeline

### 📊 **Study Monitor Dashboard**
- **Comprehensive Course Tracking**: All 10 core HBO-ICT courses with detailed assessment breakdowns
- **EC Progress Tracking**: Visual progress bars showing current EC (2.5/60) and NBSA boundary progress (2.5/45)
- **IT Personality Program**: Collapsible information section explaining the 7 available courses (students choose 4)
- **Quarter Organization**: Courses grouped by academic quarters (Q1, Q2, Q3, Q4, Q1-Q2, Q1-Q4)
- **Assessment Details**: Individual test components with weighting percentages and status tracking
- **Color-coded Status**: Visual indicators for completion status (not completed/sufficient/insufficient)

### 📝 **Blog Section**
- **Multiple Blog Posts**: 5 comprehensive blog posts covering various aspects of my ICT journey
- **Topics Include**: Study choice motivation, SWOT analysis, programming journey, full-stack engineering, and feedback reflection
- **Responsive Design**: Clean, readable layout with proper typography
- **Navigation**: Easy browsing between blog posts with breadcrumb navigation

### ❓ **FAQ Page**
- **Comprehensive Information**: 8 detailed FAQ entries about HZ University facilities and procedures
- **Accordion Layout**: Collapsible sections for easy navigation
- **Topics Include**: Study locations, transportation, accident reporting, passport photo upload, and more
- **Search-friendly Structure**: Well-organized content for easy information retrieval

### 🎨 **Advanced UI Features**
- **Collapsible Sections**: Bootstrap collapse components for better UX (IT Personality info, FAQ sections)
- **Interactive Elements**: Smooth animations and hover effects
- **Progress Visualization**: Bootstrap progress bars for EC tracking
- **Responsive Tables**: Mobile-friendly study monitor with proper column alignment

## 🗂️ File Structure

```
PCO/
├── index.html                           # Home page - main landing page
├── README.md                            # Project documentation
├── package.json                         # Node.js dependencies (Express server)
├── package-lock.json                    # Dependency lock file
├── pages/                               # Main website pages
│   ├── profile.html                     # Personal profile and information
│   ├── dashboard.html                   # Study monitor with course tracking
│   ├── blog.html                        # Blog feed with post previews
│   ├── faq.html                         # FAQ about HZ University
│   └── blogPosts/                       # Individual blog post pages
│       ├── blog-post-study-choice.html  # Study choice motivation
│       ├── blog-post-swot-analysis.html # Personal SWOT analysis
│       ├── blog-post-programming-journey.html # Programming background
│       ├── blog-post-fullstack-engineer.html # Full-stack development
│       ├── blog-post-feedback.html      # Feedback and reflection
│       └── misc/                        # Utility pages
│           ├── blog-skeleton.html       # Template for new blog posts
│           └── page-not-found.html      # 404 error page
├── assets/                              # Static assets
│   ├── css/
│   │   └── style.css                    # Custom CSS styles and overrides
│   ├── images/                          # Image assets
│   │   ├── danisoos.jpg                 # Personal profile photo
│   │   ├── hero-coding-laptop.jpg       # Hero section background
│   │   ├── engineering.jpg              # Engineering/technology image
│   │   ├── hz-logo.png                  # HZ University logo
│   │   └── hz-logo-favicon.png          # Website favicon
│   └── js/                              # JavaScript files (if any)
├── docs/                                # Documentation and course materials
│   ├── PCO course reader.pdf            # Course documentation
│   ├── OSIRIS_EXPORT.pdf               # Academic records
│   └── feedback.txt                     # Project feedback notes
├── screenshots/                         # Website screenshots for documentation
│   ├── index.png                        # Home page screenshot
│   ├── profile.png                      # Profile page screenshot
│   ├── dashboard.png                    # Dashboard screenshot
│   ├── blog.png                         # Blog page screenshot
│   └── faq.png                          # FAQ page screenshot
└── node_modules/                        # Node.js dependencies (auto-generated)
```

### 📁 Recent File Structure Changes

**Blog Post Reorganization**: All individual blog post HTML files have been moved from the root `blog/` directory to `pages/blogPosts/` for better organization and maintainability. This change required updating all relative file paths for:
- CSS and JavaScript references
- Navigation links between pages
- Image and asset references
- Favicon links

## 🔧 Technologies Used

### Frontend Technologies
- **HTML5**: Semantic markup with proper document structure
- **CSS3**: Custom styling, animations, and responsive design
- **JavaScript**: Interactive elements and dynamic functionality
- **Bootstrap 5.3.2**: Responsive framework and UI components
- **Bootstrap Icons**: Comprehensive icon library for UI elements

### Backend/Development
- **Node.js**: Development environment
- **Express.js**: Local development server (for testing)
- **Git**: Version control and project management

### Key Libraries & Frameworks
- **Bootstrap Components Used**:
  - Responsive grid system
  - Navigation components (navbar, breadcrumbs)
  - Card components for content layout
  - Accordion components for FAQ
  - Collapse components for expandable sections
  - Progress bars for EC tracking
  - Alert components for notifications
  - Table components with responsive design

## 🎨 Design System & UI/UX

### Color Palette
- **Primary**: #0066cc (HZ Blue) - Main brand color
- **Secondary**: #004499 (Dark Blue) - Accent and hover states
- **Success**: #28a745 (Green) - Completed status indicators
- **Warning**: #ffc107 (Yellow) - In-progress status indicators
- **Info**: #17a2b8 (Light Blue) - Information alerts and badges
- **Light**: #f8f9fa (Light Gray) - Background and subtle elements

### Typography & Layout
- **Font Stack**: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- **Responsive Design**: Mobile-first approach with Bootstrap breakpoints
- **Heading Hierarchy**: Semantic H1-H6 structure for accessibility and SEO
- **Line Height**: 1.6 for optimal readability across devices

### Interactive Elements
- **Collapsible Sections**: Bootstrap collapse for IT Personality info and FAQ
- **Progress Visualization**: Animated progress bars for EC tracking
- **Hover Effects**: Subtle animations on cards and buttons
- **Active States**: Clear indication of current page in navigation
- **Responsive Tables**: Horizontal scrolling on mobile devices

## 📱 Responsive Design & Compatibility

### Device Support
The website is fully responsive and optimized for:
- **Desktop**: 1200px+ (Full layout with sidebar navigation)
- **Tablet**: 768px - 1199px (Adapted layout with collapsible navigation)
- **Mobile**: 320px - 767px (Mobile-first design with hamburger menu)

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile, Samsung Internet)
- Progressive enhancement for older browsers

## ♿ Accessibility & SEO

### Accessibility Features
- **Semantic HTML5**: Proper document structure with semantic elements
- **ARIA Labels**: Screen reader support for interactive elements
- **Keyboard Navigation**: Full keyboard accessibility for all interactive elements
- **Color Contrast**: WCAG compliant color combinations
- **Alt Text**: Descriptive alternative text for all images
- **Focus Indicators**: Clear visual focus states for navigation

### SEO Optimization
- **Unique Meta Tags**: Custom title and description for each page
- **Heading Hierarchy**: Proper H1-H6 structure throughout the site
- **Semantic Markup**: Structured data with appropriate HTML5 elements
- **Clean URLs**: Descriptive file names and logical site structure
- **Image Optimization**: Compressed images with descriptive alt text
- **Mobile-First**: Google's mobile-first indexing compatibility

## 🚀 Setup & Usage

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/meggyedes/PCO.git
   cd PCO
   ```

2. **Install dependencies** (optional, for development server):
   ```bash
   npm install
   ```

3. **View the website**:
   - **Option 1**: Open `index.html` directly in your web browser
   - **Option 2**: Use a local development server:
     ```bash
     # Using Node.js Express (if installed)
     node server.js

     # Or using Python (if available)
     python -m http.server 8000

     # Or using any other local server
     ```

4. **Navigate the site**:
   - Start at `index.html` (Home page)
   - Use the navigation menu to explore all sections
   - Check the dashboard for study progress tracking
   - Browse blog posts for insights into the ICT journey

### File Organization
- All main pages are in the `pages/` directory
- Blog posts are organized in `pages/blogPosts/`
- Assets (CSS, images, JS) are in the `assets/` directory
- Documentation and course materials are in `docs/`

## 🎓 Learning Outcomes & Skills Demonstrated

### Technical Skills
- **Frontend Development**: HTML5, CSS3, JavaScript, Bootstrap framework
- **Responsive Design**: Mobile-first approach, flexible layouts, media queries
- **UI/UX Design**: User-centered design, accessibility, visual hierarchy
- **Version Control**: Git workflow, project organization, documentation
- **Web Standards**: Semantic markup, SEO optimization, performance considerations

### Academic & Professional Skills
- **Self-Reflection**: Personal SWOT analysis, study choice motivation
- **Progress Tracking**: Academic monitoring, goal setting, milestone tracking
- **Communication**: Technical writing, blog content creation, documentation
- **Project Management**: File organization, structured development approach
- **Problem Solving**: Debugging, responsive design challenges, cross-browser compatibility

## 🔄 Future Development Plans

### Short-term Enhancements
- **Interactive Features**: Add JavaScript for enhanced user interactions
- **Content Updates**: Regular blog posts documenting learning progress
- **Performance**: Image optimization, CSS minification, loading improvements
- **Testing**: Cross-browser testing, accessibility audits, mobile testing

### Long-term Goals
- **Portfolio Integration**: Showcase completed projects and assignments
- **Dynamic Content**: Implement a content management system
- **Advanced Features**: Search functionality, contact forms, comment systems
- **Professional Development**: Integration with LinkedIn, GitHub portfolio

## 📝 Academic Context

**Course**: Program & Career Orientation (PCO)
**Institution**: HZ University of Applied Sciences
**Program**: HBO-ICT (Bachelor of ICT)
**Academic Year**: 2025-2026
**Study Phase**: Year 1, Semester 1

### Course Objectives Met
- ✅ Personal reflection and career orientation
- ✅ Academic progress monitoring and planning
- ✅ Technical skill development in web technologies
- ✅ Professional communication and documentation
- ✅ Understanding of ICT industry and career paths

## 📊 Project Statistics

- **Total Pages**: 10+ (including blog posts)
- **Lines of Code**: 2000+ (HTML, CSS, JavaScript combined)
- **Images**: 5 optimized images
- **Blog Posts**: 5 comprehensive articles
- **FAQ Entries**: 7 detailed university information sections
- **Responsive Breakpoints**: 3 (mobile, tablet, desktop)

---

**© 2025 - HZ University ICT Portfolio by Daniel Soos**


_This website represents my academic journey and commitment to excellence in the ICT field. Created as part of the PCO course requirements at HZ University of Applied Sciences._

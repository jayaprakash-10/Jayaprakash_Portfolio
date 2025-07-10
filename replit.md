# Personal Portfolio Website

## Overview

This is a minimal, modern, and responsive personal portfolio website built with vanilla HTML, CSS, and JavaScript. The site features a clean, central container layout with Space Grotesk typography and supports both light and dark modes. It's designed to showcase skills, projects, and experience with a focus on simplicity and elegance.

## User Preferences

Preferred communication style: Simple, everyday language.
Design preference: Minimal, modern aesthetic with clean layouts and smooth transitions.
User: Jaya Prakash - Data & ML Engineer, Business Analyst & Software Engineer
Specialization: AI/ML, Data Analytics, Business Intelligence

## System Architecture

This is a frontend-only static website with a multi-page architecture:

- **HTML Structure**: Multi-page application with separate HTML files for each section
- **CSS Styling**: Shared CSS file with modern layouts, smooth transitions, and responsive design
- **JavaScript Interactivity**: Shared JavaScript for navigation, mobile menu, and animations

The architecture follows a traditional separation of concerns pattern with:
- index.html (Home page)
- about.html (Skills and Education)
- projects.html (Portfolio projects)
- contact.html (Contact information)
- style.css (Shared styling)
- multi-page-script.js (Shared JavaScript functionality)

## Key Components

### Frontend Architecture
- **Multi-Page Application**: Separate HTML files for Home, About, Projects, and Contact sections
- **Responsive Design**: Mobile-first approach with breakpoints for different screen sizes
- **Modern CSS**: Uses CSS3 features including backdrop-filter, transitions, and flexbox
- **Progressive Enhancement**: Core functionality works without JavaScript, enhanced with JS features

### Navigation System
- **Fixed Header**: Sticky navigation bar that stays visible while scrolling
- **Mobile Toggle**: Hamburger menu for mobile devices
- **Scroll Effects**: Dynamic navbar styling and active section highlighting
- **Smooth Scrolling**: CSS-based smooth scrolling between sections
- **Pages**: Home (landing page), About (skills and education), Projects (real projects), Contact (links only)

### Design System
- **Typography**: Space Grotesk from Google Fonts for modern, minimal typography
- **Icons**: Font Awesome for consistent iconography
- **Color Scheme**: Light theme with automatic dark mode support based on system preferences
- **Layout**: Central container (800px max-width) with clean, minimal design
- **Animations**: Subtle fade-in effects and smooth transitions

## Data Flow

Since this is a static frontend application, there's no traditional data flow. Instead, the interaction flow follows this pattern:

1. **User Interaction**: Click navigation links or scroll page
2. **Event Handling**: JavaScript captures events (clicks, scrolls)
3. **DOM Manipulation**: Update classes and styles based on user actions
4. **Visual Feedback**: CSS transitions provide smooth visual responses

The JavaScript handles:
- Mobile menu toggle states
- Scroll position tracking
- Active navigation highlighting
- Navbar appearance changes based on scroll position

## External Dependencies

### Third-Party Services
- **Google Fonts**: Inter font family hosted by Google
- **Font Awesome**: Icon library (version 6.4.0) via CDN
- **No Backend Services**: Completely client-side application

### Development Dependencies
- **Modern Browser**: Requires browsers supporting CSS3 and ES6+ JavaScript
- **No Build Process**: Direct file serving without compilation or bundling

## Deployment Strategy

### Static Hosting
This portfolio is designed for static hosting platforms:
- **GitHub Pages**: Ideal for free hosting with automatic deployments
- **Netlify/Vercel**: Modern static hosting with form handling capabilities
- **Traditional Web Hosting**: Any standard web hosting service
- **CDN Deployment**: Can be served entirely from content delivery networks

### Performance Considerations
- **Minimal Dependencies**: Only essential external resources loaded
- **Optimized Loading**: Fonts loaded with display=swap for better performance
- **No Build Step Required**: Files can be deployed directly without compilation

### Scalability Notes
- **Contact Forms**: Currently no contact form implementation (would require backend service or third-party integration)
- **Content Management**: Content updates require direct file editing
- **Analytics**: Can be easily extended with Google Analytics or similar services

## Development Notes

### Code Organization
- **Modular CSS**: Styles organized by component/section
- **Event-Driven JavaScript**: Clean event handling with proper cleanup
- **Semantic HTML**: Proper heading hierarchy and accessibility considerations

### Browser Compatibility
- **Modern Browser Support**: Uses CSS Grid, Flexbox, and modern JavaScript
- **Progressive Enhancement**: Graceful degradation for older browsers
- **Mobile Responsive**: Tested across different device sizes

### Future Enhancements
- **Content Sections**: HTML structure prepared for About, Projects, Skills, and Contact sections
- **Form Integration**: Ready for contact form implementation
- **CMS Integration**: Structure supports future headless CMS integration
- **Build Process**: Can be enhanced with build tools for optimization
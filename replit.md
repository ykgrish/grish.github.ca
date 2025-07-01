# Grish Acharya Portfolio Website

## Overview

This is a personal portfolio website for Grish Acharya, a versatile professional with experience in copywriting, content editing, video editing, AI voice model training, and program development. The site is a static single-page website built with vanilla HTML and CSS, showcasing professional accomplishments and experience in tech and marketing roles.

## System Architecture

### Frontend Architecture
- **Technology**: Pure HTML5 and CSS3 (no JavaScript framework)
- **Design Philosophy**: Minimalist, responsive design with clean typography
- **Layout**: Single-page application with centered content layout
- **Responsive Design**: Uses CSS clamp() and viewport-based units for mobile responsiveness

### Content Structure
- Static HTML content with embedded CSS styles
- Markdown content file for project descriptions and updates
- Clean, semantic HTML structure following modern web standards

## Key Components

### 1. HTML Structure (`index.html`)
- Semantic HTML5 document structure
- Embedded CSS for styling (no external stylesheets)
- Responsive typography using system fonts
- Clean, minimal design aesthetic

### 2. Content Management
- Portfolio content now includes:
  - Professional status (available for opportunities)
  - Personal introduction highlighting versatility
  - Six key project areas showcasing diverse skills
  - Contact information with LinkedIn and portfolio drive links

### 3. Styling Approach
- CSS Reset for cross-browser consistency
- Modern CSS features (clamp, flexbox implied)
- System font stack for optimal performance
- Mobile-first responsive design principles

## Data Flow

1. **Static Content Delivery**: HTML file served directly to browser
2. **Content Updates**: Manual editing of HTML and markdown files
3. **Asset Loading**: Currently references external CDN images (Webflow CDN)
4. **Navigation**: Single-page experience with potential for anchor linking

## External Dependencies

### Current Dependencies
- **Webflow CDN**: Project images hosted on `cdn.prod.website-files.com`
- **System Fonts**: Relies on device system fonts (no web font loading)

### Potential Issues
- Broken image links in markdown content
- External CDN dependency for visual assets
- No content management system for easy updates

## Deployment Strategy

### Current State
- Static website suitable for any web server or CDN
- No build process required
- Can be deployed to GitHub Pages, Netlify, Vercel, or any static hosting service

### Recommendations for Enhancement
- Implement proper asset management
- Add build process for content compilation
- Consider static site generator for easier content management
- Implement proper image optimization and hosting

## User Preferences

Preferred communication style: Simple, everyday language.

## Changelog

Changelog:
- June 30, 2025: Initial setup with Arlen McCluskey template
- June 30, 2025: Personalized portfolio for Grish Acharya with:
  - Updated professional background and experience
  - Added colorful gradient background to match reference design
  - Created 6 project sections highlighting key accomplishments
  - Added contact section with LinkedIn and portfolio drive links
  - Responsive design with semi-transparent content overlay
- July 1, 2025: Migration to Replit environment completed with:
  - Installed Python 3.11 for HTTP server functionality
  - Successfully configured Portfolio Server workflow on port 5000
  - Fixed interactive stick pattern positioning (absolute instead of fixed)
  - Reduced stick pattern size from 400x500px to 320x400px
  - Adjusted stick grid from 12x9 to 10x8 with 35px spacing
  - Moved stick pattern to top 5% for first-screen visibility
  - Added scroll-triggered logo animation with glow effects
  - Enhanced background with realistic grainy paper texture
  - Added multiple texture layers for authentic paper/wall appearance
  - Implemented radial gradient staining effects on background

## Notes for Development

### Immediate Improvements Needed
1. **Content Integration**: The markdown content needs to be properly integrated into the HTML structure
2. **Asset Management**: Replace external CDN links with local assets or reliable hosting
3. **Content Structure**: Complete the project showcase section with proper descriptions and working links
4. **Status Updates**: Implement the sabbatical status notice prominently on the page

### Technical Considerations
- The site follows modern web standards but could benefit from a build process
- Consider implementing a static site generator (like Eleventy, Gatsby, or Next.js) for better content management
- The responsive design foundation is solid but incomplete in the current HTML file
- No JavaScript is currently used, maintaining fast load times and simplicity

### Content Strategy
- The designer values clarity, empathy, and integrity - this should be reflected in the site's clean, accessible design
- Seven main projects are outlined, each needing proper presentation with images and case study links
- Professional experience spans major tech companies, suggesting a high-quality portfolio presentation is essential
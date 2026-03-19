# Muhammad Abdullah - Single-Page Developer Portfolio

A responsive single-page portfolio website showcasing my development projects, skills, and contact information. Built with vanilla HTML, CSS, and JavaScript as a solution to the [Frontend Mentor Single-page Developer Portfolio Challenge](https://www.frontendmentor.io/challenges/singlepage-developer-portfolio-bBVj2ZPi-x).

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Built With](#built-with)
- [Project Highlights](#project-highlights)
- [Key Learnings](#key-learnings)
- [Live Site & Repository](#live-site--repository)
- [Author](#author)

## Overview

This portfolio website presents my front-end development work, skills, and professional information in a clean, interactive interface. The site features responsive design across mobile, tablet, and desktop devices, with smooth animations and interactive hover effects. Featured projects include Personal Finance Tracker, Registration Form UI, Growth SaaS Landing Page, and LoopStudios.

## Features

- **Responsive Design**: Mobile-first approach with optimized layouts for mobile (≤768px), tablet (769px-1024px), and desktop (1025px+)
- **Interactive Project Overlays**: Hover effects reveal GitHub and live demo links for each project
- **Typing Animation**: Animated hero description text that types out on page load
- **Contact Form**: Fully styled contact form to connect with visitors
- **Accessible Navigation**: Keyboard-friendly navigation with social media links (GitHub, Frontend Mentor, LinkedIn, Upwork)
- **Smooth Animations**: CSS transitions and animations for interactive elements
- **Pattern Design Elements**: Decorative SVG pattern rings positioned throughout the page

## Built With

- **Semantic HTML5** - Structured, accessible markup
- **CSS3** - Advanced styling with:
  - CSS Custom Properties (variables) for theming
  - Flexbox for layouts
  - CSS Grid for skill sections
  - Media queries for responsive design
  - Transitions and animations
- **Vanilla JavaScript** - Pure JS for:
  - Project overlay interactions (mouseenter/mouseleave events)
  - Character-by-character typing animation
  - DOM manipulation

## Project Highlights

### 1. Personal Finance Tracker
- HTML, CSS, JavaScript
- Interactive financial tracking application
- [GitHub](https://github.com/theprogrammer141/PERSONAL-FINANCE-TRACKER) | [Live Demo](https://pft-app.netlify.app/)

### 2. Registration Form UI
- HTML, CSS, JavaScript form validation
- Clean, modern form design
- [GitHub](https://github.com/theprogrammer141/JS-FORM-VALIDATION) | [Live Demo](https://js-reg-form1.netlify.app/)

### 3. Growth SaaS Landing Page
- HTML, CSS, JavaScript
- Professional SaaS landing page
- [GitHub](https://github.com/theprogrammer141/GROWTH-SAAS-WEBSITE) | [Live Demo](https://growth-saas-website.netlify.app/)

### 4. LoopStudios Landing Page
- HTML, CSS, JavaScript
- Interactive portfolio showcase
- [GitHub](https://github.com/theprogrammer141/LoopStudios) | [Live Demo](https://loopstudios-app1.netlify.app/)

## Key Learnings

### CSS Positioning & Stacking Context
- Mastered absolute positioning within relative containers
- Understood z-index layering and positioning context
- Fixed pattern ring visibility issues through proper stacking order

### Responsive Design Architecture
- Implemented mobile-first workflow with media queries
- Created flexible layouts using Flexbox and CSS Grid
- Optimized typography and spacing for different viewport sizes

### JavaScript Interactivity
- Implemented event-driven interactions with addEventListener
- Built typing animation algorithm with character-by-character delays
- Practiced DOM manipulation with classList methods

### Accessibility & Semantics
- Used semantic HTML for structure (header, footer, section, nav)
- Implemented keyboard-accessible interactions
- Designed focus states for interactive elements

## Technical Implementation

### Responsive Breakpoints
- **Mobile**: ≤768px
- **Tablet**: 769px - 1024px
- **Desktop**: 1025px+

### Project Card Overlay Effect
```javascript
const projects = document.querySelectorAll(".project");
projects.forEach((project) => {
  project.addEventListener("mouseenter", () => {
    project.querySelector(".overlay").classList.add("visible");
  });
  project.addEventListener("mouseleave", () => {
    project.querySelector(".overlay").classList.remove("visible");
  });
});
```

### Typing Animation
- Character-by-character animation with 50ms delays
- Executes automatically on page load
- Creates engaging hero section intro

## Live Site & Repository

- **Live Site**: [View Portfolio](https://muhammad-abdullahdev.netlify.app/)
- **Frontend Mentor Profile**: [@theprogrammer141](https://www.frontendmentor.io/profile/theprogrammer141)
- **GitHub**: [theprogrammer141](https://github.com/theprogrammer141)
- **LinkedIn**: [Muhammad Abdullah](https://www.linkedin.com/in/muhammad-abdullah-872b74278/)
- **Upwork**: [View Profile](https://www.upwork.com/freelancers/~019ccc7cd97e63b821)

## Author

**Muhammad Abdullah**
- Portfolio: m.abdullah
- Front-end developer passionate about building accessible web apps
- Currently learning React and expanding JavaScript expertise

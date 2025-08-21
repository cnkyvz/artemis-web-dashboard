# Artemis Web Dashboard

[![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)

Multi-portal web dashboard system for enterprise field operations management. Features separate interfaces for employees and companies with a unified main landing page.

## Features

### Multi-Portal Architecture
- **Main Landing Page** - Central entry point with navigation
- **Employee Portal** - Dedicated interface for field workers
- **Company Portal** - Management dashboard for businesses
- **Unified Build System** - Integrated deployment workflow

### Core Functionality
- Responsive web design for all devices
- Real-time data visualization
- User authentication and role management
- Interactive dashboard components
- Modern ES6+ JavaScript modules

### Business Value
- Centralized access to multiple interfaces
- Role-based portal separation
- Streamlined user experience
- Efficient resource management

## 🌐 Live Production System

**[Access Production Dashboard](https://simetra.artemisaritim.com)**

This is the live production system currently in use:
- Multi-portal enterprise dashboard
- Employee field operations interface
- Company management system
- Real-time data processing and analytics

*Production system - active business operations*

## Tech Stack

- **HTML5** - Modern semantic markup
- **CSS3** - Advanced styling with flexbox/grid
- **JavaScript ES6+** - Modern JavaScript features
- **Vite** - Fast build tool and dev server
- **Modular Architecture** - Component-based structure

## Project Structure
artemis-web-dashboard/
├── index.html              # Main landing page
├── calisan/                # Employee portal
│   ├── index.html         # Employee interface
│   └── assets/            # Employee portal assets
├── firma/                 # Company portal
│   ├── index.html         # Company interface
│   └── assets/            # Company portal assets
├── dist/                  # Built files for production
├── package.json           # Dependencies and build scripts
└── vite.config.js         # Vite configuration

## Portal Overview

### Main Landing Page
- Welcome interface with portal selection
- Company branding and navigation
- Quick access to employee and company portals
- Responsive design for mobile and desktop

### Employee Portal (calisan/)
- Field worker dashboard
- Service request management
- Real-time task updates
- Mobile-optimized interface

### Company Portal (firma/)
- Business management dashboard
- Employee oversight
- Analytics and reporting
- Administrative tools

## Installation & Setup

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Modern web browser

### Development Setup

```bash
# Clone the repository
git clone https://github.com/cnkyvz/artemis-web-dashboard.git

# Navigate to project directory
cd artemis-web-dashboard

# Install dependencies
npm install

# Start development server
npm run dev

# Open browser to http://localhost:3000
Build for Production
bash# Build all portals
npm run build

# Preview production build
npm run preview
Development Workflow
Portal Development
Each portal can be developed independently:
bash# Work on main landing page
edit index.html

# Work on employee portal
cd calisan/
edit index.html

# Work on company portal
cd firma/
edit index.html
Build System
The build process creates optimized versions of all portals:
bashnpm run build
# Generates:
# - dist/index.html (main page)
# - dist/calisan/ (employee portal)
# - dist/firma/ (company portal)
Features by Portal
Main Page Features

Portal selection interface
Company information display
Navigation menu
Contact information

Employee Portal Features

Task management
Service form submissions
Real-time notifications
Mobile-responsive design

Company Portal Features

Employee management
Service oversight
Analytics dashboard
Administrative controls

Browser Support

Chrome 80+
Firefox 75+
Safari 13+
Edge 80+

Performance Optimizations

Vite-powered fast builds
ES6 module optimization
CSS and JavaScript minification
Asset compression
Lazy loading for portal assets

Security Considerations

Content Security Policy headers
XSS prevention
Secure authentication flow
Input validation

Deployment
Static Hosting
The built files can be deployed to any static hosting service:
bashnpm run build
# Upload dist/ folder to your hosting provider
Recommended Hosting

Netlify
Vercel
GitHub Pages
AWS S3 + CloudFront

Contributing
This is a portfolio project demonstrating enterprise web dashboard development capabilities.
License
This project is for portfolio demonstration purposes.
Contact
Cenk Yavuz - Full Stack Developer

Email: cnkyvzz@gmail.com
LinkedIn: linkedin.com/in/yavuzcenk
GitHub: @cnkyvz

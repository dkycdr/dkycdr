# Portfolio Website

> A modern, interactive portfolio website showcasing professional work with stunning 3D visual effects and smooth animations.

[![React Version](https://img.shields.io/badge/React-19.2.0-61dafb?logo=react)](https://reactjs.org/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-0.1.0-green.svg)](package.json)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/dkycdr/portfolio)

## 🌟 About

This portfolio website is a cutting-edge React application designed to showcase professional work, skills, and achievements in an engaging and visually stunning way. Built with modern web technologies, it features advanced 3D graphics, smooth animations, and an intuitive user experience that leaves a lasting impression on visitors.

**Target Audience:** Developers, designers, recruiters, clients, and anyone interested in exploring a professional portfolio with a modern, interactive interface.

## 🚀 Demo

<!-- TODO: Add your live demo link -->
<!-- 🔗 **Live Site:** [https://your-portfolio-url.com](https://your-portfolio-url.com) -->

## 📸 Screenshots

<!-- TODO: Add screenshots of your portfolio -->
<!-- Replace the placeholder path with your actual screenshot -->

![Portfolio Hero Section](./docs/screenshots/hero-screenshot.png)

*Main hero section with 3D visual effects and smooth animations*

<!-- Additional screenshots can be added here -->
<!-- ![Projects Section](./docs/screenshots/projects-section.png) -->
<!-- ![Mobile View](./docs/screenshots/mobile-view.png) -->

## ✨ Features

- **Responsive Design** - Mobile-first approach ensuring perfect display on all devices
- **Advanced 3D Visual Effects** - Powered by Three.js for immersive graphics
- **Smooth Scroll Navigation** - Intersection observer-based navigation with smooth scrolling
- **Interactive AI Chatbot** - Engage visitors with an intelligent chatbot assistant
- **Animated Hero Section** - Eye-catching WebGL shader effects
- **Project Showcase** - Display your work with tilted card effects and hover animations
- **Team Member Profiles** - Showcase your team with professional profile cards
- **Contact Form Integration** - Easy-to-use contact form for visitor inquiries
- **Dynamic Background Effects** - Plasma and Liquid Ether visual effects
- **Performance Optimized** - Lazy loading and code splitting for fast load times
- **Modern UI/UX** - Clean, professional design with Framer Motion animations

## 🛠️ Technology Stack

| Category | Technologies |
|----------|-------------|
| **Frontend Framework** | React 19.2.0, React DOM 19.2.0 |
| **Animation Library** | Framer Motion 12.23.26 |
| **3D Graphics** | Three.js 0.181.2, OGL 1.0.11, Postprocessing 6.38.0 |
| **Icons** | React Icons 5.5.0 |
| **Testing** | Jest, React Testing Library, fast-check 4.4.0 |
| **Build Tools** | React Scripts 5.0.1 |
| **Deployment** | gh-pages 6.3.0 |
| **Performance** | Web Vitals 2.1.4 |

## 🚀 Quick Start

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Node.js** (version 16.x or higher) - [Download here](https://nodejs.org/)
- **npm** (comes with Node.js) or **yarn** package manager

To check your current versions, run:
```bash
node --version
npm --version
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/dkycdr/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   
   Using npm:
   ```bash
   npm install
   ```
   
   Or using yarn:
   ```bash
   yarn install
   ```

3. **Start the development server**
   
   Using npm:
   ```bash
   npm start
   ```
   
   Or using yarn:
   ```bash
   yarn start
   ```

4. **Open your browser**
   
   The application will automatically open at [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

In the project directory, you can run the following commands:

### `npm start`
Runs the app in development mode.  
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.  
The page will reload when you make changes, and you may see lint errors in the console.

### `npm test`
Launches the test runner in interactive watch mode.  
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Builds the app for production to the `build` folder.  
It correctly bundles React in production mode and optimizes the build for the best performance.  
The build is minified and the filenames include hashes.

### `npm run deploy`
Deploys the built application to GitHub Pages.  
Runs `npm run build` automatically before deploying.

### `npm run eject`
**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project and copy all the configuration files and transitive dependencies (webpack, Babel, ESLint, etc.) right into your project so you have full control over them.

## 📁 Project Structure

```
portfolio/
├── public/                      # Static assets and HTML template
│   ├── images/                  # Public images (profile, team members)
│   ├── index.html              # HTML template
│   ├── favicon.ico             # Site favicon
│   └── manifest.json           # PWA manifest
│
├── src/                        # Source code
│   ├── components/             # React components
│   │   ├── NavBar.js          # Navigation bar with smooth scroll
│   │   ├── Hero.js            # Hero section with 3D effects
│   │   ├── About.js           # About section
│   │   ├── Projects.js        # Projects showcase
│   │   ├── Team.js            # Team members section
│   │   ├── Contact.js         # Contact form
│   │   ├── ChatBot.js         # AI chatbot (lazy loaded)
│   │   ├── GlobalBackground.js # Dynamic background effects
│   │   ├── ProfileCard.js     # Reusable profile card component
│   │   ├── ProjectCard.js     # Project display card
│   │   ├── TiltedCard.js      # 3D tilted card effect
│   │   ├── Stats.js           # Statistics display
│   │   ├── Testimonials.js    # Testimonials section
│   │   ├── Plasma.js          # Plasma visual effect
│   │   ├── LiquidEther.js     # Liquid ether visual effect
│   │   ├── ProfilePhoto.js    # Profile photo component
│   │   └── *.css              # Component-specific styles
│   │
│   ├── utils/                  # Utility functions
│   │   └── smoothScroll.js    # Smooth scroll utilities
│   │
│   ├── images/                 # Source images
│   │   └── *.jpg, *.png       # Image assets
│   │
│   ├── App.js                  # Main application component
│   ├── App.css                 # Global app styles
│   ├── index.js                # Application entry point
│   ├── index.css               # Global CSS styles
│   └── setupTests.js           # Test configuration
│
├── docs/                       # Documentation
│   └── screenshots/            # Screenshot images for README
│
├── .kiro/                      # Kiro AI assistant configuration
│   └── specs/                  # Feature specifications
│
├── package.json                # Project dependencies and scripts
├── README.md                   # This file
└── .gitignore                  # Git ignore rules
```

## 🏗️ Architecture Overview

### Component Organization

The application follows a **component-based architecture** with clear separation of concerns:

#### **Core Layout Components**
- **NavBar** - Sticky navigation bar with smooth scroll links to sections
- **Hero** - Landing section featuring WebGL shader effects and animated text
- **GlobalBackground** - Manages dynamic background visual effects (Plasma/Liquid Ether)

#### **Content Sections**
- **About** - Personal/professional information with stats and profile
- **Projects** - Portfolio project showcase with interactive cards
- **Team** - Team member profiles with hover effects
- **Contact** - Contact form for visitor inquiries

#### **Reusable UI Components**
- **ProfileCard** - Displays team member information with consistent styling
- **ProjectCard** - Shows project details with images and descriptions
- **TiltedCard** - Provides 3D tilt effect on hover for interactive elements
- **Stats** - Displays numerical statistics with animations
- **Testimonials** - Shows client/user testimonials

#### **Visual Effects Components**
- **Plasma** - WebGL-based plasma effect for dynamic backgrounds
- **LiquidEther** - Fluid simulation effect using Three.js
- **ProfilePhoto** - Enhanced profile image with visual effects

#### **Interactive Features**
- **ChatBot** - AI-powered chatbot (lazy loaded for performance)

### Routing and Navigation

This is a **single-page application (SPA)** without traditional routing. Navigation is handled through:

- **Smooth Scroll Navigation** - Clicking nav links smoothly scrolls to corresponding sections
- **Intersection Observer API** - Detects when sections enter viewport for animations
- **Section-based Layout** - Each major component represents a full-screen or content section
- **Hash-based Navigation** - Uses anchor links (#about, #projects, etc.) for direct section access

The navigation flow:
```
NavBar (sticky) → Smooth scroll to section → Intersection Observer triggers animations
```

### Styling Organization

The project uses a **modular CSS approach** with component-specific stylesheets:

#### **Global Styles**
- `index.css` - Base styles, CSS variables, typography, and global resets
- `App.css` - Application-level styles, layout, and footer

#### **Component Styles**
Each component has its own CSS file (e.g., `Hero.js` → `hero.css`):
- `navbar.css` - Navigation bar styles
- `hero.css` - Hero section with 3D transforms
- `about.css` - About section layout
- `projects.css` - Project grid and card styles
- `team.css` - Team section layout
- `contact.css` - Contact form styling
- `chatbot.css` - Chatbot interface styles
- `globalBackground.css` - Background effect styles
- And more component-specific stylesheets...

#### **CSS Architecture Principles**
- **CSS Variables** - Used for theming (colors, spacing, timing)
- **BEM-like Naming** - Descriptive class names for clarity
- **Scoped Styles** - Each component's styles are isolated
- **Responsive Design** - Mobile-first media queries
- **Performance** - Hardware-accelerated transforms and animations

### State Management

The application uses **React's built-in state management**:
- **useState** - Local component state for UI interactions
- **useEffect** - Side effects (scroll listeners, intersection observers)
- **Lazy Loading** - Code splitting with React.lazy() for ChatBot
- **No external state library** - Keeps the bundle size small and architecture simple

### Performance Optimizations

- **Lazy Loading** - ChatBot component loads only when needed
- **Intersection Observer** - Efficient scroll-based animations
- **Throttled Event Handlers** - Mouse move events throttled to ~30fps
- **CSS Transforms** - Hardware-accelerated animations
- **Code Splitting** - Automatic chunking via React Scripts
- **Image Optimization** - Proper image formats and sizes


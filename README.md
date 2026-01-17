#  Safaqes - Design Consultancy Portfolio

<div align="center">

<img src="https://safaqes.com/Slogo.png" alt="Safaqes Logo" width="120" height="120" />

**Clarity by Design | Transforming Complexity into Intuitive Solutions**

[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-18.2.0-3178C6?logo=typescript)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-6.0.4-646CFF?logo=vite)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4.16-38BDF8?logo=tailwind-css)](https://tailwindcss.com/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-12.26.2-FF6B6B?logo=framer)](https://www.framer.com/motion/)
[![Radix UI](https://img.shields.io/badge/Radix_UI-Latest-161618?logo=radix-ui)](https://www.radix-ui.com/)

[Live Site](https://safaqes.com) | [ Fully Responsive](https://safaqes.com) | [ SEO Optimized](https://safaqes.com)

</div>

---

##  Project Overview

**Safaqes** is a professional design consultancy portfolio website showcasing comprehensive design services including Product & Service Design, Business Design, Brand Strategy, Coaching & Capacity Building, and Report Design. Built with modern web technologies, it delivers an exceptional user experience while highlighting the company's expertise in transforming complexity into clarity.

###  Design Philosophy

- **Clarity First**: Clean, intuitive interfaces that prioritize user understanding
- **Evidence-Backed**: Design decisions rooted in research and validation
- **Scalable Solutions**: Systems engineered to work efficiently at any scale
- **User-Centric**: Approaches that put the end-user at the center of every decision

###  Core Mission

Safaqes turns complexity into clarity, designing intuitive products, services, and systems engineered to work efficiently. The company helps organizations understand what needs to be improved through research, analysis, prototyping, and testing.

---

##  Features

###  Core Features

- **Interactive Service Showcase**: Detailed presentation of 5 core service offerings
- **Animated Hero Section**: Cinematic background with compelling messaging
- **Client Portfolio**: Showcase of trusted clients and successful projects
- **Value Proposition**: Clear communication of delivered value
- **Responsive Design**: Optimized for all devices and screen sizes
- **Smooth Animations**: Framer Motion-powered transitions and interactions

###  Visual Experience

- **Dynamic Background**: Animated pattern elements for visual depth
- **Hover Effects**: Interactive micro-animations throughout
- **Scroll Animations**: Smooth scroll-triggered reveals
- **Typography**: Professional Gilroy font family for brand consistency
- **Color System**: Carefully curated palette with brand colors

###  User Experience

- **Mobile-First Design**: Optimized for smartphones and tablets
- **Fast Loading**: Optimized images and code splitting
- **Accessibility**: WCAG compliant with keyboard navigation
- **SEO Optimized**: Comprehensive meta tags and structured data
- **Progressive Enhancement**: Works seamlessly across all browsers

---

##  Technology Stack

###  Frontend Framework

- **React 18.2.0**: Modern React with hooks and concurrent features
- **TypeScript 18.2.0**: Type-safe development environment
- **React Router DOM 6.8.1**: Client-side routing with dynamic pages

###  Styling & Animation

- **Tailwind CSS 3.4.16**: Utility-first CSS framework
- **Framer Motion 12.26.2**: Production-ready motion library
- **Tailwind Merge 2.5.4**: Utility class merging
- **Tailwind Animate 1.0.7**: Extended animation utilities

###  UI Components

- **Radix UI Accordion 1.2.1**: Accessible accordion components
- **Radix UI Separator 1.1.0**: Visual separators
- **Radix UI Slot 1.1.0**: Composition utilities
- **Lucide React 0.453.0**: Beautiful icon library
- **Class Variance Authority 0.7.0**: Type-safe component variants

###  Build Tools

- **Vite 6.0.4**: Lightning-fast build tool with HMR
- **ESBuild 0.24.0**: Extremely fast JavaScript bundler
- **PostCSS**: CSS processing and optimization

---

##  Project Structure

```
Safaqus v1/
├── 📁 public/                        # Static assets
│   ├── 🖼️ Slogo.png                  # Brand logo
│   ├── 🖼️ icons.svg                  # Icon sprite
│   ├── 🖼️ element-05.svg             # Decorative elements
│   ├── 📁 Service Images/            # Service detail images
│   │   ├── ProductServiceDesign.jpeg
│   │   ├── BusinessDesign.jpeg
│   │   ├── BrandStrategy.jpeg
│   │   ├── Coaching.jpeg
│   │   └── ReportDesign.jpeg
│   ├── 📁 Client Logos/              # Trusted client logos
│   │   ├── clients (1-10).png
│   │   └── ...
│   ├── 📁 Value Images/              # Value proposition images
│   │   ├── Clarity.jpeg
│   │   ├── Alignment.jpeg
│   │   ├── Confidence.jpeg
│   │   └── Impact.jpeg
│   ├── 📄 robots.txt                 # SEO robots file
│   └── 📄 sitemap.xml                # Site structure
├── 📁 src/
│   ├── 📁 components/
│   │   ├── 📁 ui/                    # Reusable UI components
│   │   │   ├── accordion.tsx
│   │   │   ├── button.tsx
│   │   │   └── separator.tsx
│   │   └── Layout.tsx                # Main layout wrapper
│   ├── 📁 screens/
│   │   ├── 📁 Homepage/
│   │   │   ├── Homepage.tsx
│   │   │   └── 📁 sections/
│   │   │       ├── HeroSection/
│   │   │       ├── WhatWeDoSection/
│   │   │       ├── OurServicesSection/
│   │   │       ├── ValueDeliveredSection/
│   │   │       ├── HowWeWorkSection/
│   │   │       ├── WhoWeWorkWithSection/
│   │   │       ├── CoreValuesSection/
│   │   │       ├── ClientTestimonialsSection/
│   │   │       ├── FAQSection/
│   │   │       └── ContactCTASection/
│   │   └── 📁 ServiceDetail/
│   │       ├── ProductServiceDesign.tsx
│   │       ├── BusinessDesign.tsx
│   │       ├── BrandStrategy.tsx
│   │       ├── Coaching.tsx
│   │       ├── ReportDesign.tsx
│   │       └── ServiceDetailLayout.tsx
│   ├── 📁 lib/
│   │   └── utils.ts                  # Utility functions
│   ├── index.tsx                     # Application entry
│   └── index.html                    # HTML template
├── 📄 package.json                   # Dependencies & scripts
├── 📄 tailwind.config.js            # Tailwind configuration
├── 📄 vite.config.ts                # Vite build configuration
└── 📄 README.md                     # Project documentation
```

---

##  Design System

###  Color Palette

```css
:root {
  /* Primary Colors */
  --safaqes-orange: #f1592d;
  --safaqes-orange-50: #fff5f2;
  --safaqes-orange-600: #d94d2a;

  /* Neutral Colors */
  --off-white: #f7f7f7;
  --black: #171717;
  --black-500: #000000;

  /* Semantic Colors */
  --border: hsl(214.3 31.8% 91.4%);
  --input: hsl(214.3 31.8% 91.4%);
  --ring: hsl(222.2 84% 4.9%);
}
```

###  Typography

- **Primary Font**: Gilroy (Bold, Semibold, Regular)
- **Display Font**: Neue Haas Grotesk Text Pro (Bold)
- **Weights**: 400 (Regular), 600 (Semibold), 700 (Bold)
- **Font Loading**: Custom font files with fallback to Helvetica

###  Animation System

- **Duration**: 300ms (fast), 600ms (medium), 800ms (slow)
- **Easing**: ease-out for smooth, natural motion
- **Stagger**: 0.1s delay between sequential elements
- **Scroll Animations**: Framer Motion with viewport triggers

###  Responsive Breakpoints

- **Mobile**: < 640px (sm)
- **Tablet**: 640px - 1024px (md/lg)
- **Desktop**: > 1024px (xl)
- **Large**: > 1440px (2xl)

---

## Services Offered

### 1.  Product & Service Design

**Transforming insights into validated, evidence-backed solutions**

- User-centric design approaches
- Research, analysis, prototyping, and testing
- Evidence-backed product development
- Customer-focused service design

### 2.  Business Design

**Combining business strategy with design thinking**

- Current state analysis and future vision
- New business model creation
- Revenue stream development
- Go-to-market concept development

### 3.  Brand Strategy, Design & Communication

**Shaping brands that are distinctive, meaningful, and built to grow**

- Brand foundation definition
- Visual identity creation
- Communication strategy
- Consistent brand messaging

### 4.  Coaching & Capacity Building

**Tailor-made courses combining theory and practice**

- Innovation training
- Design thinking workshops
- Custom practical sessions
- Team capacity building

### 5.  Report Design

**Transforming complex information into accessible insights**

- Research report design
- Evaluation report structuring
- Impact report visualization
- Policy report presentation

---

##  Performance & SEO

###  SEO Features

- **Comprehensive Meta Tags**: Title, description, keywords
- **Open Graph**: Rich social media previews
- **Structured Data**: Schema.org markup for services
- **XML Sitemap**: Complete site structure for search engines
- **Robots.txt**: Search engine crawling directives
- **Semantic HTML**: Proper HTML5 semantic elements

###  Performance Optimizations

- **Code Splitting**: Route-based and component-based splitting
- **Image Optimization**: Optimized JPEG images with proper sizing
- **Font Loading**: Custom font loading with display swap
- **Bundle Optimization**: Tree shaking and minification
- **Lazy Loading**: Components loaded on demand

###  Core Web Vitals

Target performance metrics:

- **LCP (Largest Contentful Paint)**: < 2.5s
- **FID (First Input Delay)**: < 100ms
- **CLS (Cumulative Layout Shift)**: < 0.1
- **TTFB (Time to First Byte)**: < 800ms


---

##  Deployment

###  Production Deployment

The site is deployed on a dedicated KVM server with:

- **Server**: Ubuntu 22.04 LTS
- **Web Server**: Nginx 1.18.0
- **SSL**: Let's Encrypt (Auto-renewal enabled)
- **Domain**: safaqes.com + www.safaqes.com
- **CI/CD**: GitHub Webhook for automated deployments

###  Security Features

- **HTTPS Enforcement**: Full SSL/TLS encryption
- **Security Headers**: XSS protection, content type options
- **Automated SSL Renewal**: Certbot with twice-daily checks
- **Webhook Authentication**: HMAC SHA-256 signature verification

---

##  License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

##  Acknowledgments

- **React Team**: For the powerful framework
- **Vite Team**: For the lightning-fast build tool
- **Tailwind CSS**: For the utility-first CSS framework
- **Framer Motion**: For smooth animations
- **Radix UI**: For accessible component primitives

---

## Technical Support

For technical questions or contributions:
- **Developer**: [BnRamadan](https://bnramadan.com/)
- **Email**: [contact@bnramadan.com](mailto:contact@bnramadan.com)

---

<div align="center">

###  Built with passion for design excellence

**Safaqes** - _Clarity by Design_

_"Turning complexity into clarity, designing intuitive products, services, and systems engineered to work efficiently."_

</div>

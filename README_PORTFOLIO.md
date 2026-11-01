# Vishal Band — Personal Portfolio

A modern, animated portfolio website built with **React**, **Tailwind CSS**, and **Lucide Icons**.

## Quick Start Guide

### 1. Run Development Server
```bash
npm run dev
```
Open your browser at `http://localhost:3000` to preview your portfolio live with instant hot-reload.

### 2. Build for Production / Deployment
```bash
npm run build
```
The compiled, production-ready static files will be generated in the `dist/` directory, ready to deploy to **Vercel**, **Netlify**, or **GitHub Pages**.

---

## How to Customize Your Content

All portfolio content is centralized in a single configuration file:
👉 **`src/data/portfolioData.js`**

### What you can customize:
1. **Personal Info (`personalInfo`)**:
   - `name`: Your full name
   - `roles`: Badges displayed on hero (e.g., MBA Student, Marketing, Product, Consulting)
   - `bio`: Short professional narrative
   - `email`: Your direct email address
   - `linkedin`: Your LinkedIn URL
   - `resumeUrl`: Link to your resume PDF or external file
   - `portrait`: Add your photo to `public/avatar.jpg` and set `src: "/avatar.jpg"`

2. **About Me (`aboutData`)**:
   - Academic Focus, Location, Interests, Background
   - Structured achievement placeholders (no fake numbers)

3. **Experience Timeline (`experienceData`)**:
   - Roles, companies, dates, locations, bullet points, and expandable key strategic highlights

4. **Case Studies & Projects (`projectsData`)**:
   - Category filtering (`Marketing`, `Product`, `Research`, `Technology`)
   - 6-part full case study breakdown:
     1. Problem
     2. Research & Discovery
     3. Strategic Approach
     4. Solution & Deliverables
     5. Outcomes & Key Metrics (Placeholders)
     6. Key Learnings

5. **Skills (`skillsData`)**:
   - Grouped into Marketing & Strategy, Product & Research, Analytics & Tools, and Operations
   - Clean chips without arbitrary percentages

6. **Education & Certifications (`educationData` & `certificationsData`)**:
   - MBA, Bachelor's degree, and certifications with verification links

7. **Contact Info (`contactData`)**:
   - Headline, subheadline, email copy button, and validated message form

---

## Design Features
- **Near-Black Palette**: Ultra-sleek dark theme (`#080B11`) with off-white typography and vibrant electric indigo accent.
- **Theme Toggle**: Switch between Dark and Light modes seamlessly with automatic persistence.
- **Scroll Spy Navigation**: Active section automatically highlights as you scroll down the page.
- **Interactive Case Studies**: Deep dive modal with 6 distinct strategic sections.
- **Fully Responsive**: Optimized for mobile, tablet, laptop, and 4K displays.
- **Accessibility & Motion**: Respects `prefers-reduced-motion` settings and supports full keyboard navigation.

# Compute — Distributed AI Agent Platform (Landing Page)

A premium, highly-interactive, dark-themed developer landing page for **Compute**, a state-of-the-art platform designed to build, run, and orchestrate autonomous AI agents on a global distributed infrastructure.

This website is built with **Next.js (App Router)**, **TypeScript**, and **Tailwind CSS**, featuring rich animations, interactive Canvas elements, and an immersive cyberpunk aesthetic.

---

## 🚀 Key Website Features & Interactive Sections

The landing page features a modular structure designed to wow users with advanced visuals and premium micro-interactions:

1. **Navigation Bar (`components/landing/navigation.tsx`)**: A sleek, sticky, glassmorphism-based header offering smooth transitions to various sections.
2. **Hero Section (`components/landing/hero-section.tsx`)**: Includes an atmospheric background video, subtle architectural gridlines, and a dynamic typing word animation ("automate", "delegate", "execute", "scale") featuring a staggered letters blur/lerp effect.
3. **Features Bento Grid (`components/landing/features-section.tsx`)**: Displays core capabilities using a Bento Grid layout with a custom-built interactive particle flow canvas visualization reacting to mouse movement.
4. **How It Works (`components/landing/how-it-works-section.tsx`)**: Guides the developer through the compile-to-deploy process of building distributed AI agents.
5. **Global Infrastructure Map (`components/landing/infrastructure-section.tsx`)**: Features a 3D-like wireframe network sphere image and a custom SVG-based animated connection map that simulates live data transfer across 29 global nodes.
6. **Live Metrics Dashboard (`components/landing/metrics-section.tsx`)**: Displays charts, logs, and statistics representing uptime, latency, cost savings, and execution trends.
7. **Integrations Grid (`components/landing/integrations-section.tsx`)**: Highlights the platform's compatibility with databases, LLM providers, and external tools.
8. **Security & Sandboxing (`components/landing/security-section.tsx`)**: Focuses on the isolated environment, audit logs, and TLS-encrypted communication layers.
9. **Developer SDK & CLI (`components/landing/developers-section.tsx`)**: Focuses on the TypeScript SDK with syntax highlighting and interactive features.
10. **Testimonials Carousel (`components/landing/testimonials-section.tsx`)**: A responsive review carousel showing real-world case studies against an absolute client-rendered ASCII dot background grid (optimized for SSR hydration).
11. **Interactive Pricing Grid (`components/landing/pricing-section.tsx`)**: Displays tiers (*Explorer*, *Builder*, and *Scale*) with a toggle for monthly/annual pricing, complete with custom styled elements.
12. **CTA (Call to Action) & Footer**: Premium final conversion prompts and quick links.

---

## 🛠️ Technology Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router, Turbopack)
- **Language**: TypeScript
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) & Vanilla CSS (`styled-jsx` for section-specific animations)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Visuals**: HTML5 Canvas (custom physics & particle flows)

---

## 📂 Project Structure

```bash
├── app/
│   ├── layout.tsx         # Global layout with fonts and metadata
│   └── page.tsx           # Home entry combining all landing sections
├── components/
│   ├── landing/           # Highly modular sections of the website
│   │   ├── ascii-scene.tsx
│   │   ├── cta-section.tsx
│   │   ├── developers-section.tsx
│   │   ├── features-section.tsx
│   │   ├── footer-section.tsx
│   │   ├── hero-section.tsx
│   │   ├── how-it-works-section.tsx
│   │   ├── infrastructure-section.tsx
│   │   ├── integrations-section.tsx
│   │   ├── metrics-section.tsx
│   │   ├── navigation.tsx
│   │   ├── pricing-section.tsx
│   │   ├── security-section.tsx
│   │   └── testimonials-section.tsx
│   └── ui/                # Shared base design components
├── public/                # Static assets (images, videos, and icons)
├── package.json           # Scripts and dependencies configuration
└── tsconfig.json          # TypeScript compiler rules
```

---

## 💻 Getting Started

Follow these steps to run the landing page locally:

### Prerequisites

Make sure you have Node.js (v18.x or newer) installed.

### 1. Install Dependencies

Using `npm`:
```bash
npm install
```

### 2. Run the Development Server

Start the Next.js dev server with Turbopack enabled:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the page.

### 3. Build for Production

Compile and optimize the project for production deployment:
```bash
npm run build
```

To run the built production bundle locally:
```bash
npm run start
```

### 4. Linting

Run ESLint to check for code quality and syntax issues:
```bash
npm run lint
```

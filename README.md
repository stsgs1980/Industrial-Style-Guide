# Industrial Style Guide

A visual reference guide to 31 technical illustration styles -- from engineering blueprints to modern UI design -- helping designers and engineers choose the right style for their projects.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Next.js](https://img.shields.io/badge/Next.js-16-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B2AC)

## Features

- 31 illustration styles with visual examples across 6 categories: Technical, Pencil, Minimalist, Architectural, Vintage, Digital
- Dark and light theme support with toggle
- Modal image viewer for full-size previews
- Top-5 UI style ranking with scoring: Flat Design Technical (100%), Line Art (90%), Monoline (85%), Geometric Minimalism (80%), Isometric (75%)
- Key concepts comparison: Engineering Drawing vs Minimalism
- FAQ section with common questions

## Tech Stack

- **Framework** - Next.js 16 (App Router)
- **Language** - TypeScript 5
- **Styling** - Tailwind CSS 4
- **UI Components** - shadcn/ui
- **Icons** - Lucide React
- **Theme** - next-themes

## Getting Started

### Prerequisites

- Node.js 20+ or Bun

### Installation

```bash
git clone https://github.com/Sts8987/Industrial-Style-Guide.git
cd Industrial-Style-Guide
bun install
```

### Run

```bash
bun run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

- `src/app/page.tsx` - Main page with all components
- `src/app/layout.tsx` - Root layout with ThemeProvider
- `src/app/globals.css` - Global styles
- `src/components/ui/` - shadcn/ui components
- `src/components/theme-provider.tsx` - Theme context provider
- `src/components/theme-toggle.tsx` - Theme toggle button
- `src/lib/` - Utility functions
- `public/styles/` - Style illustration images (37 files)

## Screenshots

### Light theme

![Light Theme](public/styles/industrial_minimalism_01.png)

### Dark theme

![Dark Theme](public/styles/industrial_minimalism_02.png)

## Scripts

```bash
bun run dev      # Development server (port 3000)
bun run build    # Production build
bun run start    # Production server
bun run lint     # ESLint check
bun run setup    # Project initialization
```

## License

[MIT](LICENSE)

---
Built with: Next.js + React + TypeScript + Tailwind CSS
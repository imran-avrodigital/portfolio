# Portfolio Website - Replit.md

## Overview

This is a modern React-based portfolio website for Imran Nazir, an SEO Strategist and Digital Marketing Expert. The application is built using a full-stack architecture with React frontend, Express.js backend, and PostgreSQL database integration via Drizzle ORM. The site showcases professional services, projects, and contact information with a dark theme and smooth animations.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript
- **Routing**: Wouter for client-side routing
- **State Management**: TanStack Query (React Query) for server state management
- **UI Framework**: Tailwind CSS with shadcn/ui component library
- **Animations**: Framer Motion for smooth animations and transitions
- **Build Tool**: Vite for fast development and optimized builds

### Backend Architecture
- **Framework**: Express.js with TypeScript
- **Runtime**: Node.js with ES modules
- **Database ORM**: Drizzle ORM for type-safe database operations
- **Database**: PostgreSQL (configured for Neon Database)
- **Session Management**: Connect-pg-simple for PostgreSQL session storage

### Component Structure
- **Radix UI**: Headless UI components for accessibility
- **Custom Components**: Modular section components (Hero, About, Projects, Services, Contact)
- **UI Components**: Reusable shadcn/ui components with consistent theming

## Key Components

### Frontend Components
1. **Navigation**: Sticky navigation with smooth scrolling and active section highlighting
2. **Hero Section**: Animated introduction with typewriter effect
3. **About Section**: Personal information with animated statistics
4. **Projects Section**: Portfolio showcase with detailed project cards
5. **Services Section**: Service offerings with skill progress bars
6. **Contact Section**: Contact form with project type selection
7. **Footer**: Social media links and copyright information

### Backend Infrastructure
1. **Express Server**: RESTful API endpoints with error handling middleware
2. **Database Layer**: Drizzle ORM with PostgreSQL connection
3. **Session Management**: Secure session handling with PostgreSQL storage
4. **Development Tools**: Hot reload with Vite integration in development

### Database Schema
- **Users Table**: Basic user authentication structure with username and password fields
- **Schema Location**: `shared/schema.ts` for type sharing between frontend and backend

## Data Flow

1. **Static Content**: Portfolio information is currently hardcoded in React components
2. **API Integration**: TanStack Query setup for future API integration
3. **Form Handling**: Contact form with validation and submission handling
4. **Database Operations**: Drizzle ORM provides type-safe database queries
5. **Session Management**: PostgreSQL-based session storage for user authentication

## External Dependencies

### Core Dependencies
- **@neondatabase/serverless**: Serverless PostgreSQL connection for Neon Database
- **drizzle-orm**: Type-safe ORM for database operations
- **@tanstack/react-query**: Server state management
- **framer-motion**: Animation library for smooth transitions
- **wouter**: Lightweight routing library

### UI Dependencies
- **@radix-ui/***: Headless UI components for accessibility
- **tailwindcss**: Utility-first CSS framework
- **class-variance-authority**: Type-safe variant API for components
- **react-hook-form**: Form handling with validation

### Development Dependencies
- **vite**: Fast build tool and development server
- **typescript**: Type safety across the application
- **tsx**: TypeScript execution for Node.js

## Deployment Strategy

### Build Process
1. **Frontend Build**: Vite builds React application to `dist/public`
2. **Backend Build**: esbuild bundles Express server to `dist/index.js`
3. **Database Migration**: Drizzle Kit handles schema migrations

### Environment Configuration
- **Database**: Requires `DATABASE_URL` environment variable for PostgreSQL connection
- **Production**: Serves static files from `dist/public` in production mode
- **Development**: Uses Vite dev server with hot module replacement

### Hosting Requirements
- **Node.js**: Runtime environment for Express server
- **PostgreSQL**: Database server (configured for Neon Database)
- **Static File Serving**: Express serves built React application in production

## Changelog

```
Changelog:
- June 29, 2025. Initial setup with futuristic portfolio design
- June 29, 2025. Added 3 new projects (Avrodigital.co, Bestwheeled.com, DigitalDivingBoard.com)
- June 29, 2025. Created testimonials section with client reviews
- June 29, 2025. Enhanced services with off-page SEO and link building
- June 29, 2025. Added video editing skills (Adobe Premiere Pro, CapCut)
- June 29, 2025. Added AI content creation skills (Kling AI, Runway ML, Google VEO)
- June 29, 2025. Added social media marketing skills (Facebook/Instagram organic)
- June 30, 2025. Made website fully mobile responsive with cross-device animations
- June 30, 2025. Added professional profile image to About Me section with hover effects
- June 30, 2025. Implemented responsive mobile navigation with hamburger menu
- June 30, 2025. Made hero text mobile responsive with two-line layout
```

## User Preferences

```
Preferred communication style: Simple, everyday language.
```
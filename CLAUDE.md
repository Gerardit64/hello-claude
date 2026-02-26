# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Development Commands

```bash
# Start development server (runs on port 3001)
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run linter
npm run lint
```

## Project Architecture

This is a simple Next.js application using the App Router (Next.js 16) with TypeScript.

- **App Router**: Uses the `app/` directory for routing (not `pages/`)
- **Server Components**: Pages are Server Components by default
- **Port**: Development server runs on port 3001 instead of default 3000
- **Path Alias**: `@/*` maps to the root directory for imports

## Structure

- `app/layout.tsx` - Root layout with HTML structure and metadata
- `app/page.tsx` - Home page component
- `app/globals.css` - Global CSS styles
- `next.config.js` - Next.js configuration (includes port 3001)
- `tsconfig.json` - TypeScript configuration with strict mode enabled
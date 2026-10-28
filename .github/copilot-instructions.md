# Copilot Instructions

## Project overview
- This repository contains an Astro 6 project named **Mona Mayhem**.
- The app source is in `/src` with pages in `/src/pages`.
- Current runtime target is **server output** using `@astrojs/node` (`astro.config.mjs`).
- Treat `/workshop` as out of scope for implementation tasks unless explicitly requested.

## Build and development commands
- Install dependencies: `npm ci`
- Start local dev server: `npm run dev`
- Build production output: `npm run build`
- Preview build output: `npm run preview`
- Run Astro CLI directly: `npm run astro -- <command>`

## Astro best practices
- Keep pages and API routes under `src/pages` (`.astro` pages and `src/pages/api/**` endpoints).
- Prefer Astro components/pages for rendering; use islands only when client interactivity is required.
- Keep server/client boundaries explicit; avoid unnecessary client-side JavaScript.
- Follow existing project conventions and make minimal, focused changes.
- Validate changes with `npm run build` after updates.

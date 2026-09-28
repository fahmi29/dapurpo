# Food PO

A React + TypeScript + Vite frontend for a food pre-order website. The initial structure is ready to grow into customer and admin experiences, with Tailwind CSS and a Laravel API planned for later.

## Requirements

- Node.js 20.19+ or 22.12+
- pnpm 10+

## Start the frontend

```sh
pnpm install
pnpm dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Build for production

```sh
pnpm build
pnpm preview
```

## Structure

- `src/components` — shared UI components
- `src/pages` — customer and admin pages
- `src/lib` — API client and shared utilities
- `src/types` — shared TypeScript types
- `src/styles` — global styles and design tokens

The backend is not included yet. When it is added, the frontend can call the Laravel REST API and Laravel can use PostgreSQL.

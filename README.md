# SKIRO

SKIRO is a personal portfolio and project archive for a visual artist and
software maker. It brings the studio introduction, selected external links, and
public GitHub repositories together on one page.

## What’s on the site

- An archive of projects ordered newest first
- Search by project name, language, or description
- Filters for common programming languages
- Links to each project’s GitHub repository and, when available, its live demo
- Studio and contact sections

## Run locally

Requirements: Node.js and npm.

```sh
npm install
npm run dev
```

Open the local URL printed by the development server.

## Scripts

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run typecheck` | Check TypeScript types |
| `npm run lint` | Run ESLint |
| `npm test` | Run the project’s tests |
| `npm run build` | Build the production app |

## Built with

- React
- TanStack Start and TanStack Router
- Tailwind CSS
- TypeScript

## Project content

The repository archive is maintained in [`src/data/projects.ts`](src/data/projects.ts).
Each entry can include a name, description, language, update date, GitHub URL,
and an optional live-demo URL. Only add a live-demo URL when the demo is
available; otherwise the site shows the repository link without a “Live” link.

# SKIRO

SKIRO is a focused page of repositories pinned on the SKIRO GitHub profile.

## What’s on the site

- A compact grid of the six pinned repositories
- Repository descriptions, languages, and star counts where available
- Direct links to the repositories on GitHub
- A download button for a ZIP archive of each repository

## Run locally

Requirements: Node.js and npm.

```sh
npm install
npm run dev
```

Open the local URL printed by the development server.

## Scripts

| Command             | Purpose                      |
| ------------------- | ---------------------------- |
| `npm run dev`       | Start the development server |
| `npm run typecheck` | Check TypeScript types       |
| `npm run lint`      | Run ESLint                   |
| `npm test`          | Run the project’s tests      |
| `npm run build`     | Build the production app     |

## Built with

- React
- TanStack Start and TanStack Router
- Tailwind CSS
- TypeScript

## Pinned projects

The pinned repository list is maintained in [`src/data/projects.ts`](src/data/projects.ts).

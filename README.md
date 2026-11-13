# SupaMax Live

SupaMax Live is a responsive IPTV browser built with React, TypeScript, and Vite.

## Development

- `npm install` installs dependencies.
- `npm run dev` starts the local development server.
- `npm run build` creates a production build.
- `npm test` runs the test suite.

## Deploying to Vercel

Import this repository into Vercel and use the Vite preset. The project uses
`npm run build` as its build command and `dist` as its output directory.
`vercel.json` routes client-side paths back to the app entry point so direct
visits and refreshes on routes such as `/search` and `/category/sports` work.

# AGENTS.md

## Project Context

This repository contains the EKSEL Medical Clinic frontend application. Treat it as user-owned application code; keep changes focused on the user's request and preserve existing project conventions.

Start with `README.md` for local setup, environment variables, and publish workflow.

## Key Files

- `src/`: frontend application source.
- `src/lib/clinicClient.js`: local clinic client and auth helpers.
- `vite.config.js`: Vite config.
- `.env.local`: local-only environment values; never commit secrets.

## Working Notes

- Use `npm run dev` to start the Vite development server for frontend work.
- When docs mention the frontend being started automatically, that usually means a project-specific serve command (`npm run dev`).
- Reuse the existing client patterns before adding new integration paths.
- Run the relevant checks from `package.json` before finishing code changes.

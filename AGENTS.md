# AGENTS.md

## Cursor Cloud specific instructions

This is a simple React + Vite single-page application (named `todo-project`). There is no backend, no database, and no external service dependencies.

### Quick reference

- **Package manager:** npm (lockfile: `package-lock.json`)
- **Dev server:** `npm run dev` (Vite, default port 5173)
- **Lint:** `npm run lint` (ESLint 9)
- **Build:** `npm run build`
- **Preview prod build:** `npm run preview`

### Notes

- The React Compiler is enabled via `babel-plugin-react-compiler` and `@rolldown/plugin-babel`. This may slightly slow Vite dev/build performance but requires no special configuration.
- Vite binds to `localhost` by default. To expose the dev server on all interfaces (useful in cloud VMs), run `npm run dev -- --host 0.0.0.0`.

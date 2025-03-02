# CLAUDE.md - Singularity App Development Guide

## Commands
- Development: `npm run dev --turbopack` (or yarn/pnpm/bun)
- Build: `npm run build`
- Start: `npm run start`
- Lint: `npm run lint`

## Code Style Guidelines
- **TypeScript**: Strict typing enabled. Use proper type annotations for all functions, components and variables.
- **Components**: Use React 19 with functional components and hooks.
- **Imports**: Group imports by external libraries, then internal components/utilities (`@/` prefix).
- **CSS**: Use Tailwind with class-variance-authority for components. Follow mobile-first approach.
- **Naming**: PascalCase for components, camelCase for functions/variables, kebab-case for files.
- **Error Handling**: Use try/catch blocks with specific error types. Avoid generic error messages.
- **JSX**: Use fragments where possible. Self-close tags without children.
- **Component Structure**: "use client" directive at top when needed, imports, then component definition.
- **State Management**: Prefer React hooks (useState, useContext) for state management.
- **Accessibility**: Ensure all components meet WCAG guidelines.
# AGENTS.md

You are a senior front-end architect. Please help me implement a React component library that can be published to npm.
Goal: Implement an AI streaming message component (StreamMessage) that supports high-performance rendering of large text.

## Command

1. pnpm dev — Start development server
2. pnpm build — Build production bundle
3. pnpm preview — Preview production build locally
4. pnpm add <pkg> — Install dependency
5. pnpm fmt:write — Format code
6. pnpm lint:write — Lint code

## Tech Stack

1. TypeScript
2. React 19
3. Oxc (oxlint、oxfmt)

## Princple

1. Does not depend on large UI libraries
2. Use `type` instead of interface
3. Support tree-shaking

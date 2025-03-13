# Development Guidelines

## Build & Development Commands
- `npm run dev` - Start development server with Turbopack
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run lint -- --fix` - Run ESLint with auto-fixing

## Code Style
- **TypeScript**: Use strict typing with explicit return types
- **Imports**: Absolute imports with `@/` prefix (e.g., `import { Component } from "@/components/Component"`)
- **Components**: React functional components with explicit type definitions
- **Naming**: PascalCase for components, camelCase for variables/functions
- **Error Handling**: Use try/catch with appropriate error logging
- **Clerk Auth**: Always use proper authentication patterns and middleware

## Project Structure
- Place components in appropriate directories
- Leverage Next.js App Router conventions
- Keep business logic separate from UI components
- Use TypeScript interfaces/types for shared data structures
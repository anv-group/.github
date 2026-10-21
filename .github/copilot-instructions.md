# Organization & Team Context: anv-group

## Team Composition & Individual Developer Roles
Our team consists of 3 developers:
- **Backend Developer**:
  - @aldenasf: Responsible for database architecture, schema migrations, Eloquent models and relationships, query scopes, controllers, API/web routes, authentication (Laravel Breeze), and core business logic.
- **Frontend & UI/UX Developers**:
  - @SaaMasy: Frontend & UI/UX development, creating reusable Blade components, page views, and styling directly in \.blade.php\ files using TailwindCSS.
  - @vypashaa: Frontend & UI/UX development, creating reusable Blade components, page views, and styling directly in \.blade.php\ files using TailwindCSS.

## Tech Stack
- **Backend**: Laravel, PostgreSQL
- **Frontend**: Blade templates, TailwindCSS
- **Authentication**: Laravel Breeze (Blade stack)

## AI Instructions & Development Guidelines
1. **Decoupled Development (Blade Component Mocking)**:
   - When generating or suggesting frontend components for @SaaMasy or @vypashaa, structure Blade components with modular, mockable \@props\ and default states.
   - This allows the frontend developers to design and test interactive UI/UX independently without being blocked by pending backend migrations or controller endpoints from @aldenasf.
2. **Task Delegation & Assignment**:
   - Backend tasks (database migrations, models, controllers, query filters, authorization policies) are assigned to @aldenasf.
   - Frontend tasks (layout shell, Blade components, Tailwind styling, interactive modals, responsive states) are assigned to @SaaMasy and @vypashaa.
3. **Flexibility & Iteration**:
   - High-fidelity UI/UX designs evolve frequently during development. Keep components flexible and avoid hardcoding rigid structures.

# Organization & Team Context: anv-group

## About ANV Group
ANV Group is a team of software engineering students from SMKN 1 Jenangan, Indonesia, driven by curiosity and constructive chaos. The team builds web applications, services, and digital products primarily focused on modern Laravel, PostgreSQL, and TailwindCSS ecosystems.

## Team Composition & Individual Developer Roles

Our team consists of 4 developers:
- **Backend Developers**:
  - @aldenasf: Lead Backend Developer & System Architect. Responsible for database architecture, schema migrations, Eloquent models and relationships, query scopes, controllers, API/web routes, authentication (Laravel Breeze), and core business logic.
  - @alfianRapa: Backend Developer. Responsible for API endpoints, controller logic, database seeders, query filtering, and automated testing (Pest/PHPUnit).

- **Frontend & UI/UX Developers**:
  - @SaaMasy: Frontend & UI/UX developer. Responsible for designing and creating reusable Blade components, page views, and styling directly in \.blade.php\ files using TailwindCSS.
  - @vypashaa: Frontend & UI/UX developer. Responsible for designing and creating reusable Blade components, page views, and styling directly in \.blade.php\ files using TailwindCSS.

## Tech Stack & Standards
- **Backend**: Laravel, PostgreSQL, Pest (testing)
- **Frontend**: Blade templates, TailwindCSS
- **Authentication**: Laravel Breeze (Blade stack)
- **Tooling & Conventions**: Git-flow, Conventional Commits, Component Mocking

## AI Instructions & Development Guidelines
1. **Decoupled Development (Blade Component Mocking)**:
   - When generating or suggesting frontend components for @SaaMasy or @vypashaa, structure Blade components with modular, mockable \@props\ and default fallback states.
   - This allows frontend developers to design and test interactive UI/UX independently without being blocked by pending backend migrations or controller endpoints from @aldenasf or @alfianRapa.
2. **Task Delegation & Assignment**:
   - Backend tasks (database migrations, models, controllers, query filters, authorization policies, test suites) are assigned to @aldenasf and @alfianRapa.
   - Frontend tasks (layout shell, Blade components, Tailwind styling, interactive modals, responsive states) are assigned to @SaaMasy and @vypashaa.
3. **Flexibility & Iteration**:
   - High-fidelity UI/UX designs evolve frequently during development. Keep components flexible and avoid hardcoding rigid structures.
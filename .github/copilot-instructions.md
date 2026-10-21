# Organization & Team Context: anv-group

## Team Composition & Roles
Our team consists of 3 developers:
- **1 Backend Developer**: Responsible for database design, migrations, Eloquent models, controllers, API/web endpoints, authentication (Laravel Breeze), and business logic.
- **2 Frontend & UI/UX Developers**: Responsible for user interfaces and experience, writing directly in \.blade.php\ files using TailwindCSS. They create components, views, layouts, and interactive styling.

## Tech Stack
- **Backend**: Laravel, PostgreSQL
- **Frontend**: Blade templates, TailwindCSS
- **Authentication**: Laravel Breeze (Blade stack)

## AI Instructions & Guidelines
1. **Decoupled Development (Blade Component Mocking)**:
   - When building or proposing frontend work, write Blade components with modular, mockable \@props\ and default states.
   - This allows frontend developers to design and test views independently without waiting for database migrations or controller endpoints.
2. **Task Delegation & Scope**:
   - Backend tasks (migrations, routes, controllers, query scopes, policies) must be separated cleanly from UI tasks.
   - Frontend tasks should focus strictly on \.blade.php\ templates, Blade components, Tailwind styling, and responsive layout.
3. **Flexibility & Iteration**:
   - UI/UX designs evolve frequently during development. Keep components flexible and avoid hardcoding rigid structures.

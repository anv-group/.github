# AGENTS.md: anv-group Organization Context & Coding Instructions

> Shared organizational context, team developer roles, and AI coding agent guidelines for **ANV Group**.

---

## 1. Organization Background
- **Organization**: ANV Group (nv-group)
- **Origin**: Software engineering students from SMKN 1 Jenangan, Indonesia.
- **Motto / Spirit**: Driven by curiosity and constructive chaos.
- **Primary Domain / Website**: [anvgroup.my.id](https://anvgroup.my.id)
- **Primary Tech Ecosystem**: Modern Laravel, PostgreSQL, Blade Templates, TailwindCSS, Pest.

---

## 2. Team Composition & Developer Roles

Our team consists of 4 developers divided into specialized backend and frontend domains:

### Backend Developers
- **@aldenasf**: **Lead Backend Developer & System Architect**
  - Database schema design, migrations, and index optimization.
  - Eloquent models, relationships, query scopes, and repositories/services.
  - Web & API routing, controller endpoints, and core business logic.
  - Authentication & security implementation (Laravel Breeze).
- **@alfianRapa**: **Backend Developer**
  - Web & API controllers and request validation rules.
  - Database seeders, factory definitions, and query filters.
  - Automated unit and feature testing with Pest / PHPUnit.

### Frontend & UI/UX Developers
- **@SaaMasy**: **Frontend & UI/UX Developer**
  - High-fidelity UI/UX design and interaction flows.
  - Reusable, modular Blade components (\esources/views/components/\).
  - Page layouts, dashboard shells, and TailwindCSS responsive styling.
- **@vypashaa**: **Frontend & UI/UX Developer**
  - High-fidelity UI/UX design, modals, and status widgets.
  - Reusable, modular Blade components (\esources/views/components/\).
  - Form states, interactive elements, and TailwindCSS responsive styling.

---

## 3. Tech Stack & Standards
- **Framework**: Laravel 11+
- **Database**: PostgreSQL (strict typing, foreign keys, indexed foreign relationships)
- **Frontend Engine**: Laravel Blade with TailwindCSS (no heavy SPA runtime unless explicitly specified)
- **Authentication**: Laravel Breeze (Blade stack)
- **Testing**: Pest PHP for feature and unit tests
- **Commits**: Conventional Commits (\eat:\, \ix:\, \docs:\, \efactor:\, \	est:\, \chore:\)

---

## 4. Universal Agent Instructions & Development Rules

### Rule 1: Decoupled Development (Blade Component Mocking)
When generating, reviewing, or suggesting frontend code for **@SaaMasy** or **@vypashaa**:
- Design Blade components using explicit, mockable \@props\ with reasonable fallback defaults.
- Frontend work must **never be blocked** by pending backend APIs or database migrations.
- Example:
  \\\lade
  @props([
      'title' => 'Sample Task',
      'status' => 'pending',
      'priority' => 'medium',
      'dueDate' => null,
  ])
  <div {{ \->merge(['class' => 'p-4 rounded-xl border ...']) }}>
      <!-- Mockable component body -->
  </div>
  \\\

### Rule 2: Strict Task Delegation & Issue Assignment
When creating issues, assigning PRs, or attributing tasks:
- **Backend tasks** (migrations, models, services, controllers, authorization policies, test suites) $\rightarrow$ assign to **@aldenasf** and **@alfianRapa**.
- **Frontend tasks** (Blade views, reusable components, Tailwind styling, responsive layouts, modals) $\rightarrow$ assign to **@SaaMasy** and **@vypashaa**.

### Rule 3: Robust Backend Practices
- Use Form Request validation classes for incoming request payloads.
- Keep controllers lean; delegate business logic to Eloquent models, query scopes, or dedicated actions.
- Write Pest feature tests covering both happy and error paths for every endpoint.

### Rule 4: Design Flexibility
UI/UX designs evolve iteratively. Keep component markup clean, accessible, semantic, and decoupled from rigid database constraints.
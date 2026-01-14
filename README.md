# Road map:

1. Understand Web & TypeScript Basics (1–2 days)

- TypeScript Basics
- ES6 Features (import/export, classes, promises)
- Interfaces & Types
- Async/await

This step is required — Angular uses TypeScript everywhere.

2. Understand the Basics (2-4 days)

- What is Angular?
- Components
- Modules
- Templates
- Data Binding (Interpolation, Property, Event, Two-Way)
- Directives (@if, @for, ngClass, ngStyle)
- Pipes (date, currency, custom pipes)
- Services & Dependency Injection

3. Setup Angular Environment (1 day)

- Install Node.js
- Install Angular CLI (npm install -g @angular/cli)
- Create your first project
- Run app locally
- CLI commands: generate, serve, build

4. Learn Core Angular Concepts (7–12 days)

Components (deep dive):

- Input / Output
- Component communication
- Lifecycle hooks (ngOnInit, etc.)

Routing:

- Creating pages
- Nested routes
- Route parameters
- Route Guards (AuthGuard, RoleGuard)
- Lazy loading modules (important for SaaS)

Services:

- Shared logic
- Singleton vs multi providers
- API services

HttpClient:

- Get, post, put, delete
- Interceptors (JWT token)
- Error handling

Forms:

- Template-driven
- Reactive Forms (recommended for SaaS dashboards)
- Form validation
- Custom validators

State Management:

- Local component state
- Using services as a store
- BehaviorSubject
- NgRx (optional for large SaaS)

5. Learn Angular Best Practices (4–6 days)

- Smart & dumb components
- Folder structure
- DRY shared components
- Reusable services
- Lazy loading for performance
- Environment variables
- Models & interfaces

6. Start Structuring Your SaaS (10–20 days)

- Find out a good folder Structure
- Common SaaS Modules
- Auth Module – login, register, forgot-password
- Dashboard Module – analytics, charts, table
- User Module – CRUD
- Billing Module – payments (Stripe, Razorpay, SSLCommerz)
- Settings Module

7. Pick a UI Framework (Highly Recommended)

- Angular Material (best for dashboard)
- PrimeNG (most powerful UI suite)
- NG-Zorro (very clean UI)

8. Connect Your SaaS to Backend API (Real World)

- Create base API service
- API error handling
- Interceptors for tokens
- Auto-refresh token flow

9. Authentication Setup

- JWT login
- Role-based routes
- Auth Guard
- Refresh token
- Protect API calls with interceptor for Authorization header

10. Build Your First SaaS MVP (7–14 days)

MVP Pages:

- Login
- Register
- Dashboard
- User CRUD
- Settings page

Dashboard Components:

- Cards: total users, revenue, active subscriptions, analytics cards
- Table with pagination + sorting
- Chart (ApexCharts or Chart.js or ng2-charts)

Bonus (Advanced SaaS):

- Dark mode
- Multi-language
- Multi-tenancy
- RBAC (Role-based access control)


## Git Submodule

- Create new repository + push code
- Clone repository with submodules
> git clone --recurse-submodules https://github.com/bjayanta/ng-event-practice.git event
- Add submodule to main repository
> git submodule add https://github.com/bjayanta/ng-event-practice.git event
# MISE POS — Technical Overview

## Application Structure

The main MISE POS application is organized as a Node.js monorepo with separate frontend and backend workspaces.

```text
MISE-POS/
├── apps/
│   ├── web/    # Next.js frontend
│   └── api/    # NestJS API
└── package.json
```

This keeps the user interface and API separated while allowing them to share one repository and development workflow.

## Frontend

The frontend uses:

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS
- TanStack React Query
- Zustand
- Axios
- Socket.IO Client

The interface is designed around role-based restaurant workflows rather than a single generic dashboard.

## Backend

The backend uses:

- NestJS 11
- TypeScript
- Prisma ORM
- PostgreSQL
- JWT / Passport authentication
- Socket.IO / WebSockets
- QR code generation
- Jest testing setup

## Main Backend Areas

The application contains modules covering areas such as:

- Authentication
- Menu management
- Tables
- Orders
- Staff
- Inventory
- Reports
- Real-time events
- Printers
- QR workflows
- Settings
- Reservations
- Customers
- Shifts
- Campaigns
- Sections
- Combo meals
- Happy hours
- Marketplace integration foundations

## Data Model Direction

The product data model supports restaurant concepts including:

- Tenants and branches
- Users and operational roles
- Restaurant tables
- Categories, products and modifiers
- Orders and order items
- Payments
- Staff shifts and cash movements
- Ingredients, recipes and stock movements
- Suppliers and purchase orders
- Reservations and waitlists
- Customers, loyalty, gift cards and campaigns

## Role-Based Product Thinking

The system considers different operational users, including restaurant owners, area managers, branch managers, cashiers, waiters, kitchen staff, accountants and inventory managers.

The goal is to give each role the information and actions relevant to its responsibilities while keeping the underlying restaurant data connected.

## Real-Time Operations

Socket.IO is used in the technical direction for real-time application behaviour. This supports the type of fast operational feedback required for restaurant workflows such as order and kitchen-status changes.

## Development Approach

The project is developed iteratively using product requirements, interface design, testing and AI-assisted development workflows.

The public showcase documents the architecture and product thinking. The private repository contains the main application source code.

## Status

MISE POS is under active development. The presence of a module or data structure does not mean every related workflow is production-complete. The project continues to be tested, refined and expanded.

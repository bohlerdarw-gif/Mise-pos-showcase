# MISE POS

**Restaurant Operations & Management Platform — Public Project Showcase**

MISE POS is an independent digital product project focused on bringing everyday restaurant operations into one clear, role-based system.

This public repository presents the product thinking, workflow design, UI/UX direction and technical structure behind the project. The main application source code is kept private.

## The Problem

Restaurants often manage tables, orders, staff, stock, reservations and reporting across separate tools or manual processes. During busy service, that can create unnecessary complexity and disconnected workflows.

MISE POS explores how these operational areas can work together inside one structured platform.

## What I Worked On

My contribution includes:

- Product concept and requirements definition
- User flows and role-based workflow design
- UI/UX direction and information structure
- Restaurant operations modelling
- Testing, iteration and product refinement
- AI-assisted development and technical implementation workflows

## Core Product Areas

The project includes product and technical foundations for:

- Multi-tenant and multi-branch restaurant management
- Menu, categories, products and modifiers
- Table and order management
- Staff roles and shifts
- Payments and cash-movement workflows
- Kitchen and printer workflows
- Inventory, recipes, suppliers and stock movements
- Reservations and waitlists
- Customers, loyalty, gift cards and campaigns
- QR workflows
- Reports and operational visibility
- Real-time updates
- Restaurant settings and role-based access

## User Roles

The system is designed around different restaurant responsibilities, including:

`Owner` · `Area Manager` · `Branch Manager` · `Cashier` · `Waiter` · `Kitchen` · `Accountant` · `Inventory Manager`

The product approach is not to show every user the same dashboard. Each role should see workflows that match the work they actually need to perform.

## Technology

### Frontend

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS
- TanStack React Query
- Zustand
- Axios
- Socket.IO Client

### Backend

- NestJS 11
- TypeScript
- Prisma ORM
- PostgreSQL
- JWT / Passport authentication
- Socket.IO / WebSockets
- QR code generation
- Jest testing setup

## Architecture

The private application is structured as a Node.js monorepo with separate frontend and backend workspaces:

```text
MISE-POS/
├── apps/
│   ├── web/    # Next.js frontend
│   └── api/    # NestJS API
└── package.json
```

## Product Principles

The project is built around a few practical principles:

- Clear role-based workflows
- Fast interaction during service
- Simple information hierarchy
- Responsive and mobile-friendly interfaces
- Real-time operational feedback
- Multi-branch scalability
- Practical restaurant use cases rather than isolated screens

## Project Status

**Active development.**

Some areas are more developed than others and the product is still being refined. This showcase intentionally separates implemented structure from future product direction and does not present unfinished work as production-complete.

## About Me

**Johnpaul Ogonna Onyeje**  
Electrical & Electronics Engineering graduate focused on UI/UX, digital product development and technical problem solving.

I use projects like MISE POS to develop practical experience by turning real business problems into structured digital products and working prototypes.

## More Detail

- [Project Case Study](docs/PROJECT_CASE_STUDY.md)
- [Technical Overview](docs/TECHNICAL_OVERVIEW.md)

---

**Note:** This repository is a public portfolio showcase. The main MISE POS development repository and application source code remain private.
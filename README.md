# Awesome TanStack Start [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome TanStack Start tutorials, guides, libraries, tools, and resources.

[TanStack Start](https://tanstack.com/start/latest) is a full-stack React framework powered by TanStack Router and Vite, featuring full-document SSR, streaming, server functions, and end-to-end type safety.

## Contents

- [Official Resources](#official-resources)
- [Getting Started](#getting-started)
- [Tutorials & Articles](#tutorials--articles)
- [Videos](#videos)
- [Boilerplates & Starters](#boilerplates--starters)
- [Libraries & Integrations](#libraries--integrations)
- [Example Projects](#example-projects)
- [Community](#community)

---

## Official Resources

- [TanStack Start Homepage](https://tanstack.com/start/latest) – Official landing page and overview.
- [Documentation](https://tanstack.com/start/latest/docs/framework/react/overview) – Full reference docs including routing, server functions, and deployment guides.
- [Getting Started Guide](https://tanstack.com/start/latest/docs/framework/react/getting-started) – Step-by-step guide to setting up your first TanStack Start project.
- [Quick Start](https://tanstack.com/start/latest/docs/framework/react/quick-start) – Bootstrap a new project instantly with `npx @tanstack/cli@latest create`.
- [Official Examples](https://tanstack.com/start/latest/docs/framework/react/examples/start-basic) – Official code examples (basic, auth, React Query, Supabase, Material UI, and more).
- [GitHub Repository](https://github.com/TanStack/router) – Source code for TanStack Router/Start.
- [Official Blog](https://tanstack.com/blog) – Release notes, feature deep-dives, and ecosystem updates.
- [All TanStack Libraries](https://tanstack.com/libraries) – Overview of the full TanStack ecosystem (Query, Table, Form, Router, etc.).

## Getting Started

- [Quick Start Docs](https://tanstack.com/start/latest/docs/framework/react/quick-start) – Official quick start guide.
- [TanStack for Beginners: A Complete Guide](https://dev.to/codeparrot/tanstack-for-beginners-a-complete-guide-tutorial-2ch3) – Introduction to the TanStack suite covering data fetching, state management, routing, and performance optimizations.
- [An Introduction to the TanStack Start Framework](https://blog.logrocket.com/tanstack-start-overview/) – Overview article on LogRocket covering server functions, API routes, full-stack type safety, and a comparison with other frameworks.
- [Discover TanStack Start: Modern React Framework](https://softcolontechnologies.hashnode.dev/tanstack-start) – Explores what sets TanStack Start apart: type safety, server-side streaming, server functions, and when to choose it over Next.js.
- [How to Build Modern React Apps with the TanStack Suite in 2025](https://dev.to/andrewbaisden/how-to-build-modern-react-apps-with-the-tanstack-suite-in-2025-5fed) – Dev.to guide on combining TanStack Start, Router, and Query for global state management and blog features.

## Tutorials & Articles

### Full-Stack App Building

- [A Step-by-Step Guide to Building a Full-Stack App with TanStack Start](https://blog.logrocket.com/full-stack-app-with-tanstack-start/) – LogRocket tutorial: builds a recipe-sharing web app with PostgreSQL (Prisma), authentication, routing, and CRUD.
- [Building Your First Full-Stack App with TanStack Start: A Beginner's Guide](https://www.adeelhere.com/blog/2025-10-28-building-your-first-full-stack-app-with-tanstack-start) – Beginner-friendly guide building a full-stack to-do list app; covers file structure, TypeScript types, server functions, and CRUD UI.
- [How to Build a CRUD App with TanStack Start and TanStackDB](https://www.freecodecamp.org/news/how-to-build-a-crud-app-with-tanstack-start-and-tanstackdb-with-rxdb-integration/) – freeCodeCamp walkthrough integrating TanStack Start with TanStackDB (RxDB) for a reactive local database to-do app.

### Authentication & Database

- [A Minimal TanStack Start Template with Better Auth & Drizzle ORM](https://dev.to/jqueryscript/a-minimal-tanstack-start-template-with-better-auth-drizzle-orm-4mei) – Guide showcasing a minimal starter with React 19, Better Auth, Drizzle ORM, shadcn/ui, and PostgreSQL.
- [Use Supabase with TanStack Start](https://supabase.com/docs/guides/getting-started/quickstarts/tanstack) – Official Supabase quickstart guide for integrating Supabase (auth, querying) with TanStack Start.
- [Clerk + TanStack Start Quickstart](https://clerk.com/docs/tanstack-react-start/getting-started/quickstart) – Official Clerk docs for adding authentication with prebuilt components, route protection, and session management.

### SSR & Advanced Topics

- [Effective Rendering with Selective SSR in TanStack Start](https://blog.logrocket.com/tag/tanstack/) – LogRocket deep-dive into selective server-side rendering strategies.
- [Migrating TanStack Start from Vinxi to Vite](https://blog.logrocket.com/tag/tanstack/) – Migration guide for projects upgrading to the Vite-powered build pipeline.
- [TanStack Start vs. Next.js: Choosing the Right Full-Stack React Framework](https://blog.logrocket.com/tag/tanstack/) – Comparison article to help you decide between TanStack Start and Next.js.

### Learning by Example

- [TanStack Start By Example – AyoKoding](https://www.ayokoding.com/en/learn/software-engineering/platform-web/tools/fe-tanstack-start/by-example/overview/) – 80+ practical, annotated code examples ranging from beginner to advanced topics (routing, server functions, deployment).

## Videos

- [TanStack Start Tutorial Playlist – Leonardo Montini](https://www.youtube.com/playlist?list=PLOQjd5dsGSxIEKFg4dnSQ4zQkmTktfszp) – Beginner-friendly video series covering setup, server functions, Convex, Clerk, SSR, Supabase, Drizzle ORM, dark mode, and localization.
- [TanStack Tutorials Hub – leonardomontini.dev](https://leonardomontini.dev/tanstack/) – Hub page with all TanStack Start video tutorials and accompanying code repositories by Leonardo Montini.

## Boilerplates & Starters

- [tanstarter](https://github.com/mugnavo/tanstarter) – Minimal TanStack Start template with Better Auth, Drizzle ORM, shadcn/ui, PostgreSQL, and Tailwind CSS.
- [tanstack-start-dashboard](https://github.com/Kiranism/tanstack-start-dashboard) – Admin dashboard starter using TanStack Start and shadcn/ui.
- [tanstack-start-faster](https://github.com/Vijayabaskar56/tanstack-start-faster) – E-commerce starter with TanStack, Cloudflare, Elysia.js, Better Auth, and end-to-end type safety.
- [TanStack Router Examples](https://github.com/TanStack/router/tree/main/examples) – Official example projects maintained by the TanStack team (basic, auth, Convex, Supabase, Material UI, and more).

## Libraries & Integrations

### Authentication

- [Better Auth](https://www.better-auth.com/) – Framework-agnostic authentication library with first-class TanStack Start support.
- [Clerk](https://clerk.com/docs/tanstack-react-start/getting-started/quickstart) – Drop-in authentication-as-a-service with prebuilt React components and route protection.
- [Supabase Auth](https://supabase.com/docs/guides/auth) – Open-source authentication with social login, magic links, and row-level security.

### Databases & ORMs

- [Drizzle ORM](https://orm.drizzle.team/) – Type-safe TypeScript ORM supporting PostgreSQL, MySQL, and SQLite; popular choice in TanStack Start stacks.
- [Prisma](https://www.prisma.io/) – Next-generation ORM with a powerful schema language and type-safe query builder.
- [Supabase](https://supabase.com/) – Open-source Firebase alternative providing a PostgreSQL database, auth, storage, and real-time subscriptions.
- [Convex](https://www.convex.dev/) – Serverless backend platform for real-time and event-driven apps with native TanStack Start examples.

### UI Components

- [shadcn/ui](https://ui.shadcn.com/) – Accessible, copy-paste React components built on Radix UI and Tailwind CSS; widely used in TanStack Start starters.
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework natively supported in TanStack Start projects.

### TanStack Ecosystem

- [TanStack Query](https://tanstack.com/query/latest) – Powerful async state management and data-fetching library for React.
- [TanStack Router](https://tanstack.com/router/latest) – Type-safe routing with first-class search param handling; the foundation of TanStack Start.
- [TanStack Table](https://tanstack.com/table/latest) – Headless, framework-agnostic library for building powerful tables and data grids.
- [TanStack Form](https://tanstack.com/form/latest) – Type-safe, framework-agnostic form state management.
- [TanStack Store](https://tanstack.com/store/latest) – Framework-agnostic reactive data store.
- [TanStack Virtual](https://tanstack.com/virtual/latest) – Virtualizer for efficiently rendering large lists and grids.

## Example Projects

- [tanstack-start-supabase-auth](https://github.com/aaronksaunders/tanstack-start-supabase-auth) – TanStack Start with Supabase authentication, login/signup, session management, and protected routes.
- [tanstack-start-drizzle-app](https://github.com/aaronksaunders/tanstack-start-drizzle-app) – Full-stack template with Drizzle ORM (SQLite/PostgreSQL), server-side rendering, and Tailwind CSS.
- [start-convex-trellaux](https://github.com/TanStack/router/tree/main/examples/react/start-convex-trellaux) – Official Trello-like board example combining TanStack Start with Convex as the real-time backend.

## Community

- [TanStack Discord](https://tlinz.com/discord) – Official community Discord server for questions, announcements, and discussion.
- [TanStack GitHub Discussions](https://github.com/TanStack/router/discussions) – GitHub Discussions for TanStack Router/Start questions, RFCs, and community showcases.
- [#tanstack on Hashnode](https://hashnode.com/tag/tanstack) – Community articles and tutorials tagged with `#tanstack` on Hashnode.
- [tanstack-start GitHub Topic](https://github.com/topics/tanstack-start) – Browse all public repositories tagged with `tanstack-start` on GitHub.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request. Ensure any resource you add is high quality, freely accessible, and relevant to TanStack Start.

# Catamyst Stack

> 🐱 Short URL: https://a.catamyst.com/stack

The opiniated stack list to build modern apps with web technologies. This is the simpler version of [catamyst/stack-all](https://a.catamyst.com/stack-all) (the complete list).

THe main criteria in choosing these that it must already been used for building real world apps especially with real teams. The symbol ⭐ indicated the recommendation and 🔰 need to be prioritized. Just keep in mind it doesn't mean that everything is required.

You can [use this repo as a template](https://github.com/catamyst/stack/generate) to help with your app development stack.

Main categories:

- Stack List: For evaluation
- References: For learning more
- Checklist: For development

Table of Contents:

- [Catamyst Stack](#catamyst-stack)
- [Work Stack](#work-stack)
  - [Communication](#communication)
  - [Project or Product Management](#project-or-product-management)
  - [Data Management](#data-management)
  - [Repository](#repository)
  - [Documentation and Content](#documentation-and-content)
  - [Time Tracking](#time-tracking)
- [App Stack/Dependency](#app-stackdependency)
  - [App Language/Platform/Runtime/Format](#app-languageplatformruntimeformat)
  - [Package Manager](#package-manager)
  - [Full Stack Framework](#full-stack-framework)
  - [Frontend/Client-Side Framework/Library](#frontendclient-side-frameworklibrary)
  - [API Layer](#api-layer)
  - [Content Layer](#content-layer)
  - [Auth Layer](#auth-layer)
  - [Backend/Server-Side Framework/Library](#backendserver-side-frameworklibrary)
  - [Data Fething](#data-fething)
  - [Styling](#styling)
  - [Components](#components)
  - [Icons](#icons)
  - [Router/Routing](#routerrouting)
  - [Data Validation](#data-validation)
  - [Form](#form)
  - [Complex State Management](#complex-state-management)
  - [Database ORM](#database-orm)
  - [Database](#database)
  - [App Utility](#app-utility)
- [Development Stack/Dependency](#development-stackdependency)
  - [Language Transpiler](#language-transpiler)
  - [Tooling Language/Platform/Runtime](#tooling-languageplatformruntime)
  - [Project Bundler](#project-bundler)
  - [Repo Management](#repo-management)
  - [Code Formating](#code-formating)
  - [Code Linting](#code-linting)
  - [Testing](#testing)
  - [Dev Utility](#dev-utility)
- [Deployment Stack](#deployment-stack)
  - [Frontend/Client Focused](#frontendclient-focused)
  - [Backend/Server Focused](#backendserver-focused)
- [External Service Stack](#external-service-stack)
  - [Analytics](#analytics)
  - [Multimedia/Image/Video](#multimediaimagevideo)
  - [Map](#map)
  - [Mail](#mail)
  - [Log](#log)
  - [CI/CD](#cicd)
- [References](#references)
  - [Template](#template)
- [Checklist](#checklist)
  - [Ideas](#ideas)
  - [Todos](#todos)

---

> BEGIN: [Catamyst](https://a.catamyst.com/stack)

---

# Work Stack

## Communication

- Telegram ⭐🔰
- Twist
- Slack

## Note and Knowledge Base

- Notion ⭐
- Slab ⭐

## Project or Product Management

- Linear ⭐🔰
- Trello
- Todoist

## Data Management

- Airtable ⭐
- TypeForm

## Repository

- Git ⭐🔰
- GitHub ⭐🔰
- GitLab

## Documentation and Content

- Markdown ⭐🔰
  - MDX

## Time Tracking

- Clockify ⭐

---

# Design Stack

## Sketch

- [Excalidraw](https://excalidraw.com) ⭐

## Diagram

- [Whimsical](https://whimsical.com) ⭐
- [Mermaid](https://mermaid.js.org)

## UI and UX

- Figma ⭐🔰
- Sketch
  - Zeplin
- InVision
- UXPin
- Marvel

---

# App Stack/Dependency

## App Language/Platform/Runtime/Format

- HTML ⭐🔰
- CSS ⭐🔰
- JavaScript ⭐🔰
  - TypeScript ⭐🔰
  - JSON ⭐
- Node.js v19+ ⭐🔰
- Deno
- Bun

## Package Manager

- pnpm v7+ ⭐🔰
- npm v8+
- yarn
- @antfu/ni

## Full Stack Framework

- Remix v1.14+ ⭐🔰
  - 📦 React, TypeScript, Prisma, Tailwind CSS, Remix Auth
- Next.js v13+ ⭐
  - T3 Stack ⭐
    - 📦 Next.js, TypeScript, tRPC, Prisma, Tailwind CSS, NextAuth.js
- SolidStart
- SvelteKit

## Frontend/Client-Side Framework/Library

- React ⭐🔰
- Solid
- Svelte

## API Layer

- Full Stack Framework's Approach ⭐
- tRPC
- REST API
- GraphQL

## Content Layer

For transforming the data into the content.

- DIY
- Contentlayer
- Astro:Content + Zod

## Auth Layer

Functions/Services:

- Remix Auth ⭐🔰
  - `remix-auth`
  - `remix-auth-form`
- Auth.js ⭐
  - `next-auth`
- Clerk ⭐
  - `@clerk/remix`
  - `@clerk/nextjs`
- Auth0

Methods:

- Cookie-based Sessions ⭐🔰
- Email and Password ⭐
- Passwordless with OTP
- OAuth
  - GitHub
  - Google
  - Twitter

Security/Encryption/Encoding:

- bcrypt ⭐
- JWT (JSON Web Token)

## Backend/Server-Side Framework/Library

If using Full Stack Framework's Approach, these might not needed.

REST:

- NestJS ⭐
- Express
- Fastify

GraphQL:

- GraphQL Yoga ⭐
  - Envelop
- Pothos GraphQL Schema
- Apollo GraphQL Server

## Data Fething

General:

- Fetch API ⭐🔰
- Axios HTTP ⭐🔰

REST:

- TanStack Query ⭐
- SWR
- RTK Query

GraphQL:

- urql ⭐
- `graphql-request`
- Apollo Client

## Styling

- [Tailwind CSS](https://tailwindcss.com) ⭐🔰
  - [Tailwind UI](https://tailwindui.com)
  - `tailwindcss`
  - `@tailwindcss/typography`
  - `@tailwindcss/forms`
  - `@tailwindcss/line-clamp`
  - `@tailwindcss/nesting`
  - `tailwind-merge`
  - `tailwind-variants`
  - `tailwind-config-viewer`
  - `tailwindcss-radix`
  - `tailwindcss-animate`
  - `tailwindcss-debug-screens`
- clsx ⭐🔰
- `class-variance-authority` (`joe-bell/cva`)
- PostCSS
- Autoprefixer

## Components

- [Radix UI](https://radix-ui.com) ⭐🔰
  - [shadcn UI](https://ui.shadcn.com) (`shadcn/ui`)
    - [Chimera UI](https://chimera-ui.com)
- [Headless UI](https://headlessui.com)
- Ariakit
- Downshift
- React Wrap Balancer
- NProgress ⭐: For slim progress bar

## Icons

- [Lucide](https://lucide.dev) ⭐
  - `lucide-react`
- [Heroicons](https://heroicons.com)
  - `@heroicons/react`
- React Icons
  - `react-icons`

## Router/Routing

- React Router v6 ⭐
- Next Router
- TanStack Router

## Data Validation

- Zod ⭐🔰
  - `zod-form-data`

## Form

Framework Specific:

- Remix Validated Form ⭐🔰: For full stack form handling
- Remix Forms by Seasoned
  - `domain-funcions`

Framework Agnostic:

- HouseForm ⭐: For highly interactive client side form handling
- React Hook Form (RHF)
  - `react-hook-form`
  - `@hookform/resolvers`
- Formik

## Complex State Management

- Jotai ⭐
- Zustand
- XState
- Recoil
- Redux
  - Redux Toolkit (RTK)

## Database ORM

- Prisma ORM ⭐🔰: For modeling the data and connecting the database
  - `prisma`
  - `@prisma/client`
- TypeORM
- Sequelize
- Mongoose

## Database

- MySQL on PlanetScale ⭐🔰
- PostgreSQL on Neon
- MongoDB on MongoDB Atlas

## App Utility

Remix:

- `remix-utils` ⭐

General:

- `sleep-promise`: For a promise after a specified delay
- Invariant: For descriptive errors in development, but generic errors in production
  - `tiny-invariant`
- Falso: For all the fake data

Text/String:

- `@sindresorhus/slugify`
- Voca: For string manipulaton
- `prettyjson`: For formatting JSON data in a coloured YAML-style, perfect for CLI output
- `pluralize`
- `country-code-lookup`
- i18next
  - `remix-i18next`
  - `next-i18next`

Number/Currency:

- `numeral`: For formatting and manipulating numbers
- currency.js

Date:

- Day.js ⭐🔰
- date-fns
- Moment.js

File/Asset:

- `pdfjs-dist`: For parsing and rendering PDFs

Email:

- [React Email](https://react.email) ⭐
- Nodemailer

---

# Development Stack/Dependency

## Language Transpiler

- TypeScript ⭐🔰: For type safety
- swc ⭐
- Babel

## Tooling Language/Platform/Runtime

These are important just to know the language behind the tools.

- Golang → esbuild, Vite
- Rust → swc, Turbopack

## Project Bundler

- esbuild ⭐: For Remix default bundler
  - Vite: For client side only bundler
- Turbopack ⭐: For Next.js future bundler
- Webpack: For Next.js current bundler

## Repo Management

- pnpm Workspace
- Turborepo
- Nx

## Code Formating

- Pretier ⭐🔰: For opiniated formatting
  - `prettier-plugin-tailwindcss`
  - `IanVS/prettier-plugin-sort-imports`
- Rome
- EditorConfig

## Code Linting

- ESLint ⭐🔰: For enforcing JS/TS syntax rules
  - `eslint-config-next`
  - `eslint-config-prettier`
  - `eslint-config-turbo`
  - `eslint-plugin-react`
  - `eslint-plugin-tailwindcs`
- stylelint ⭐: For enforcing CSS syntax rules
- ls-lint
- commitlint
  - `@commitlint/cli`
  - `@commitlint/config-conventional`
- lint-staged

## Testing

- Vitest ⭐🔰: For unit test
- Jest
- testing-library ⭐: For unit test
- Playwright ⭐: For end-to-end test
- MSW ⭐: For mock service test

## Dev Utility

Workflow:

- Doppler ⭐🔰: For team environment variable management
- Kodiak: For pull request management
- `npm-run-all`/`run-p`: For parallel scripts
- `motdotla/dotenv`
- Husky

TypeScript:

- `@total-typescript/ts-reset`: For improving types for common JavaScript AP

General:

- Pino
- `bundle-wizard`
- `@milahu/patch-package`

---

# Deployment Stack

## Frontend/Client Focused

- Vercel ⭐🔰: For full stack app deployment with frontend focus
  - `vercel.json`
- Netlify ⭐: For full stack app deployment with frontend focus

## Backend/Server Focused

- Railway.app ⭐: For full stack app deployment with all focus
- Render
- Fly.io
- Deno Deploy

## Complex Infra Focused

- Amazon Web Services (AWS)
  - Amazon Elastic Compute Cloud (EC2)
- Google Cloud Platform (GCP)
  - Google Compute Engine (GCE)

---

# External Service Stack

## Analytics

- Posthog ⭐
- Axiom
- Fathom
- Plausible
- Google Analytics
- Cloudflare Analytics

## Multimedia/Image/Video

- ImageKit ⭐🔰: For easy image storage/hosting
  - `imagekitio-react`
- Mux Video: For modern video hosting
- bunny.net (Bunny CDN): For cheapesrt video storage/hosting/streaming

## Map

- Mapbox ⭐
  - `mapbox-gl`
  - `react-map-gl`
- Google Maps

## Mail

Transactional:

- Mailjet ⭐: For cheapest transactional email service
- Postmark
- Sendgrid
- Amazon SES

Marketing:

- ConvertKit

## CI/CD

- GitHub Actions ⭐: For easy CI/CD on GitHub
- GitLab CI: For easy CI/CD on GitLab
- Circle CI

---

# References

- [Catamyst Stack All](https://a.catamyst.com/stack-all)
- [Infra I'm Building On In 2023](https://t3.gg/blog/post/2023-infra)
  - [The Infra That Saved Me From AWS - My 2023 Stack](https://www.youtube.com/watch?v=v-9AZKp-Ljo)

## Template

- [Rewinds - Remix Tailwind CSS starter kit](https://rewinds.mhaidarhanif.com)
- [neorepo - Remix/Next.js production-ready starter kit](https://neorepo.com)
- [SaasRock - The One-Man SaaS Framework](https://saasrock.com)
- [MakerKit - SaaS Starter Kits based on React](https://makerkit.dev)

---

# Checklist

## Ideas

- [ ] Website
  - [ ] Personal Website
  - [ ] Company Profile
  - [ ] Organization Profile
  - [ ] School Portal
  - [ ] Government Portal
  - [ ] Community Portal
- [ ] Application
  - [ ] Content Management System (CMS)
  - [ ] Learning Management System (LMS)
  - [ ] Information and Encyclopedia
  - [ ] News and Magazine
  - [ ] Writing and Publication
  - [ ] Work and Productivity
  - [ ] Contacts and Address Book
  - [ ] Social Media and Event
  - [ ] Note-Taking and Research
  - [ ] Multimedia Streaming
  - [ ] Cooking and Culinary
  - [ ] Commerce and Shopping
  - [ ] Forum and Discussion
  - [ ] Jobs and Hiring
  - [ ] Health and Fitness Tracker
  - [ ] Personal Development
  - [ ] Places and Exploration
  - [ ] Travel and Accommodation
  - [ ] Property and Housing
  - [ ] Directory and List
  - [ ] Software as a Service (SaaS)

## Todos

- [ ] Stack:
  - [ ] Work Stack
  - [ ] App Stack/Dependency
  - [ ] Development Stack/Dependency
  - [ ] Deployment Stack
  - [ ] External Service Stack
- [ ] General:
  - [ ] Format and lint rules
  - [ ] Function vs arrow function
  - [ ] Type naming convention
- [ ] Frontend/Client/Website:
  - [ ] Landing page/route
    - [ ] Header and Navigation
    - [ ] Main
    - [ ] Footer
  - [ ] 404 Not Found page/route
  - [ ] Splat (`*`) routes
  - [ ] Analytics
  - [ ] SEO metadata
  - [ ] `sitemap.xml`
  - [ ] `robots.txt`
  - [ ] OG image for social media
  - [ ] Twitter metadata
  - [ ] JSON-LD Structured data
- [ ] Backend/Server/API/Database:
  - [ ] Model naming convention (singular vs plural)
  - [ ] Field/property case convention (camel vs snake)

---

> EOF: [Catamyst](https://a.catamyst.com/stack)

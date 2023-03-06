# Catamyst Stack

> 🐱 Short URL: https://a.catamyst.com/stack

The opiniated stack list to build modern apps with web technologies. This is the simpler version of [catamyst/stack-all](https://a.catamyst.com/stack-all) (the complete list).

THe main criteria in choosing these that it must already been used for building real world apps especially with real teams. Every ⭐ indicated the recommendation, but keep in mind it doesn't mean that everything is required.

You can [use this repo as a template](https://github.com/catamyst/stack/generate) to help with your app development stack.

- [Catamyst Stack](#catamyst-stack)
- [Work Stack](#work-stack)
  - [Communication](#communication)
  - [Project/Product Management](#projectproduct-management)
  - [Data Management](#data-management)
  - [Repository](#repository)
  - [Documentation](#documentation)
  - [Time Tracking](#time-tracking)
- [App Stack/Dependency](#app-stackdependency)
  - [App Language/Platform/Runtime](#app-languageplatformruntime)
  - [Tooling Language/Platform/Runtime](#tooling-languageplatformruntime)
  - [Package Manager](#package-manager)
  - [Full Stack Framework](#full-stack-framework)
  - [Frontend/Client-Side Framework/Library](#frontendclient-side-frameworklibrary)
  - [API Layer](#api-layer)
  - [Auth Layer](#auth-layer)
  - [Backend/Server-Side Framework/Library](#backendserver-side-frameworklibrary)
  - [Data Fething](#data-fething)
  - [Styling](#styling)
  - [Components](#components)
  - [Icons](#icons)
  - [Router/Routing](#routerrouting)
  - [Data Validation](#data-validation)
  - [Form](#form)
  - [Database ORM](#database-orm)
  - [Database](#database)
  - [App Utility](#app-utility)
- [Development Stack/Dependency](#development-stackdependency)
  - [Language Transpiler](#language-transpiler)
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
  - [Multimedia/Image/Video](#multimediaimagevideo)
  - [Map](#map)
  - [Mail](#mail)
  - [CI/CD](#cicd)

---

> BEGIN: [Catamyst](https://a.catamyst.com/stack)

---

# Work Stack

## Communication

- Telegram ⭐
- Twist
- Slack

## Project/Product Management

- Linear ⭐
- Trello
- Todoist

## Data Management

- Airtable

## Repository

- Git ⭐
- GitHub ⭐

## Documentation

- Markdown ⭐
  - README.md
  - Mermaid

## Time Tracking

- Clockify ⭐

---

# App Stack/Dependency

## App Language/Platform/Runtime

- HTML ⭐
- CSS ⭐
- JavaScript ⭐
  - TypeScript ⭐
- Node.js ⭐
- Deno
- Bun

## Tooling Language/Platform/Runtime

These are important just to know the language behind the tools.

- Golang -> esbuild, Vite
- Rust -> swc, Turbopack

## Package Manager

- pnpm ⭐
- npm
- yarn

## Full Stack Framework

- Remix ⭐
  - 📦 React, TypeScript, Prisma, Tailwind CSS, Remix Auth
- Next.js ⭐
  - T3 Stack ⭐
    - 📦 Next.js, TypeScript, tRPC, Prisma, Tailwind CSS, NextAuth.js
- SolidStart
- SvelteKit

## Frontend/Client-Side Framework/Library

- React ⭐
- Solid
- Svelte

## API Layer

- Full Stack Framework's Approach ⭐
- tRPC
- REST API
- GraphQL

## Auth Layer

- Remix Auth ⭐
  - `remix-auth`
  - `remix-auth-form`
- Auth.js ⭐
  - `next-auth`
- Clerk

Methods:

- Cookie-based sessions ⭐
- Email and Password ⭐
- Passwordless with OTP
- OAuth
  - GitHub
  - Google

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

- Fetch API ⭐
- Axios HTTP ⭐

REST:

- TanStack Query ⭐
- SWR
- RTK Query

GraphQL:

- urql ⭐
- `graphql-request`
- Apollo Client

## Styling

- clsx ⭐
- Tailwind CSS ⭐
  - `tailwindcss`
  - `@tailwindcss/typography`
  - `@tailwindcss/forms`
  - `@tailwindcss/line-clamp`
  - `tailwind-merge`
  - `tailwind-variants`
  - `tailwind-config-viewer`
  - `tailwindcss-radix`
  - `tailwindcss-animate`
  - `tailwindcss-debug-screens`
- `class-variance-authority` (`joe-bell/cva`)
- PostCSS
- Autoprefixer

## Components

- Radix UI ⭐
  - shadcn UI (`shadcn/ui`)
- Headless UI
- Ariakit
- Downshift
- React Wrap Balancer
- NProgress ⭐: For slim progress bar

## Icons

- Lucide
  - `lucide-react`

## Router/Routing

- React Router ⭐
- Next Router
- TanStack Router

## Data Validation

- Zod ⭐
  - `zod-form-data`

## Form

- Remix Validated Form ⭐: For full stack form handling
- Remix Forms by Seasoned
  - `domain-funcions`
- HouseForm ⭐: For highly interactive client side form handling
- React Hook Form (RHF)
  - `react-hook-form`
  - `@hookform/resolvers`
- Formik

## Database ORM

- Prisma ORM ⭐: For modeling the data and connecting the database
  - `prisma`
  - `@prisma/client`
- TypeORM
- Sequelize
- Mongoose

## Database

- MySQL on PlanetScale ⭐
- PostgreSQL on Neon
- MongoDB on MongoDB Atlas

## App Utility

Remix:

- `remix-utils` ⭐

General:

- `sleep-promise`: For a promise after a specified delay
- Falso: For all the fake data
- Invariant: For descriptive errors in development, but generic errors in production
  - `tiny-invariant`

Text/String:

- `prettyjson`: For formatting JSON data in a coloured YAML-style, perfect for CLI output
- `@sindresorhus/slugify`
- Voca: For string manipulaton
- `pluralize`
- `country-code-lookup`
- i18next
  - `remix-i18next`
  - `next-i18next`

Number/Currency:

- `numeral`: For formatting and manipulating numbers
- currency.js

Date:

- Day.js
- date-fns
- Moment.js

File/Asset:

- `pdfjs-dist`: For parsing and rendering PDFs

---

# Development Stack/Dependency

## Language Transpiler

- TypeScript ⭐: For type safety
- swc ⭐
- Babel

## Project Bundler

- esbuild ⭐: For Remix default bundler
  - Vite: For client side only bundler
- Turbopack: For Next.js future bundler
- Webpack: For Next.js current bundler

## Repo Management

- Turborepo
- pnpm Workspace
- Nx

## Code Formating

- Pretier ⭐: For opiniated formatting
- Rome
- EditorConfig

## Code Linting

- ESLint ⭐: For enforcing JS/TS syntax rules
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

- Vitest ⭐: For unit test
- Jest
- testing-library ⭐: For unit test
- Playwright ⭐: For end-to-end test
- MSW ⭐: For mock service test

## Dev Utility

TypeScript:

- `@total-typescript/ts-reset`: For improving types for common JavaScript AP

Workflow:

- Doppler ⭐: For team environment variable management
- Kodiak: For pull request management
- `npm-run-all`/`run-p`: For parallel scripts
- `motdotla/dotenv`
- Husky

General:

- `@milahu/patch-package`

---

# Deployment Stack

## Frontend/Client Focused

- Vercel ⭐: For full stack app deployment with frontend focus
  - `vercel.json`
- Netlify: For full stack app deployment with frontend focus

## Backend/Server Focused

- Railway.app ⭐: For full stack app deployment with all focus
- Render
- Fly.io
- Deno Deploy
- Amazon Web Services (AWS)
  - Amazon EC2
- Google Cloud Platform (GCP)
  - Google CE

---

# External Service Stack

## Multimedia/Image/Video

- ImageKit ⭐: For easy image storage/hosting
  - `imagekitio-react`
- Mux Video: For modern video hosting
- bunny.net (Bunny CDN): For cheapesrt video storage/hosting/streaming

## Map

- Mapbox
  - `mapbox-gl`
  - `react-map-gl`
- Google Maps

## Mail

Transactional:

- Mailjet ⭐: For cheapest transactional email service
- Postmark
- Amazon SES

Marketing:

- ConvertKit

## CI/CD

- GitHub Actions ⭐: For easy CI/CD on GitHub
- GitLab CI: For easy CI/CD on GitLab
- Circle CI

---

> EOF: [Catamyst](https://a.catamyst.com/stack)

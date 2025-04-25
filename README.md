# Skybase Monorepo

A modern monorepo setup powered by [Turborepo](https://turbo.build/repo), [PNPM Workspaces](https://pnpm.io/workspaces), and [TypeScript](https://www.typescriptlang.org/) to build, test, and manage scalable modular packages.

---

## 📦 Packages

This monorepo contains the following packages under `packages/`:

- `@skybase/auth` – Authentication module
- `@skybase/forms` – Forms and validations
- `@skybase/axios` – Axios wrapper for API calls  
- `@skybase/api` – API route definitions and shared logic
- `@skybase/core` – App state management (auth, theme, session)
- `@skybase/files` – File upload SDK (S3, Cloudinary, compression)
- `@skybase/i18n` – Internationalization (locale, RTL, auto detect)
- `@skybase/notify` – Notifications (toasts, alerts, retry)
- `@skybase/query` – Query SDK (TanStack Query wrapper)
- `@skybase/ui` – UI components (design system)
- `@skybase/ws` – WebSocket and real-time features

Apps for testing/demo purposes are housed under `apps/`.

---

## 🛠 Tech Stack

- **Turborepo** – Task runner with caching and pipeline support
- **PNPM** – Workspace package manager
- **tsup** – Build tool (CommonJS + ESM + DTS support)
- **Jest** – Testing framework
- **TypeScript** – Type-safe codebase
- **ESLint & Prettier** – Code quality and formatting

---

## 📂 Project Structure

```bash
skybase/
│
├── packages/
│   ├── auth/
│   ├── forms/
│   ├── axios/
│   ├── api/
│   ├── core/
│   ├── files/
│   ├── i18n/
│   ├── notify/
│   ├── query/
│   ├── ui/
│   └── ws/
│
├── apps/
│   └── demo/
│
├── .github/workflows/     # CI/CD workflows
├── node_modules/
├── package.json
├── tsconfig.json
└── turbo.json


hey viewer wer are still in development phase ,but feel free to take a look around into what we are doing.
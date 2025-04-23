# Skybase Monorepo

A modern monorepo setup powered by [Turborepo](https://turbo.build/repo), [PNPM Workspaces](https://pnpm.io/workspaces), and [TypeScript](https://www.typescriptlang.org/) to build, test, and manage scalable modular packages.

---

## 📦 Packages

This monorepo contains the following packages under `packages/`:

- `@skybase/auth` – Authentication module
- `@skybase/forms` – Forms and validations
- `@skybase/axios` – Axios wrapper for API calls  
- *(Add more as needed)*

Apps for testing/demo purposes can live under `apps/`.

---

## 🛠 Tech Stack

- **Turborepo**: Task running and caching
- **PNPM**: Monorepo package manager
- **tsup**: Bundling for both CommonJS & ESM
- **Jest**: Unit testing
- **TypeScript**: Static typing
- **ESLint & Prettier**: Linting and formatting

---

## 📂 Structure

```bash
skybase/
│
├── packages/
│   ├── auth/
│   ├── forms/
│   └── axios/
│
├── apps/
│   └── demo/
│
├── node_modules/
├── package.json
├── tsconfig.json
└── turbo.json

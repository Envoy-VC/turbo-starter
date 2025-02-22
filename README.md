# Turbo Starter

This is a starter kit for bootstrapping full-stack applications with Turborepo. This starter kit is designed to be used with [TurboRepo](https://turborepo.org) and other accompanying starter kits. These are:

- [Next Starter Kit](https://github.com/Envoy-VC/next-starter): https://github.com/Envoy-VC/next-starter
- [Vite Starter Kit](https://github.com/Envoy-VC/vite-starter): https://github.com/Envoy-VC/vite-starter
- [Package Starter Kit](https://github.com/Envoy-VC/package-starter): https://github.com/Envoy-VC/package-starter
- [@shadcn/ui monorepo](https://github.com/Envoy-VC/shadcn-ui-monorepo): https://github.com/Envoy-VC/shadcn-ui-monorepo

# Features

- 🏎️ Uses [turborepo](https://turborepo.org) for monorepo management.
- 📦 Packages are managed with [pnpm](https://pnpm.io) 
- 🌎 Uses `@biome/biomejs` for code formatting and linting.
- ✅ Uses a strict opinionated linting setup using [klarity](https://github.com/Envoy-VC/klarity).
- 🪝 Uses [lefthook](https://github.com/evilmartians/lefthook) for git hooks.
- 📝 Uses [commitlint](https://github.com/conventional-changelog/commitlint) for commit message formatting.

# Project Structure

After combining the Turbo starter kit with `next-starter`, `package-starter`, and `shadcn-ui-monorepo` you will have a full-stack application with the following structure:

```
├── packages
│   ├── ui
├── apps
│   ├── web
│   └── api
├── README.md
├── LICENSE
├── .gitignore
├── .npmrc
├── package.json
├── tsconfig.json
├── turbo.json
├── biome.jsonc
├── commitlint.config.ts
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
├── lefthook.yml
```

---
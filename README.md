# Vite Typescript + Tailwind Starter

Simple, opinionated, and production-ready TS + Tailwind project template for Vite.

## Features

- Vue 3
- TypeScript
- Tailwind CSS w/ plugins preinstalled
  - `@tailwindcss/aspect-ratio`
  - `@tailwindcss/typography`
  - `@tailwindcss/forms`
- PostCSS w/ `postcss-nesting` plugin
- Eslint
- Prettier
- Simple reactive store
- Alias to `<project_root>/src` with `@`
- Cypress.io e2e tests (configured similarly to `vue-cli`)
- GitHub workflows
  - Dependabot
  - Automated e2e tests
- GitLab CI
## Project setup and usage

Install dependencies:

```
yarn
```

Run development server:

```
yarn dev
```

Open Cypress test runner:

```
yarn test
```

Run Cypress tests in headless mode:

```
yarn test:ci
```

## Contributing

Contributions are welcome! Please follow the [code of conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/) when interacting with others.

---

[Follow @uninen](https://twitter.com/uninen) on Twitter

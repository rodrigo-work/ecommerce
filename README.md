# ecommerce

This Turborepo starter is maintained by the Turborepo core team.

This example also shows how to use [Workspace Configurations](https://turbo.build/repo/docs/core-concepts/monorepos/configuring-workspaces).

## Using this example

Run the following command:

```sh
npx create-turbo@latest -e https://github.com/rodrigo-work/aws-auth-platform
```

## What's inside?

This Turborepo includes the following packages and apps:

### Apps and Packages

- `api`: an [Express](https://expressjs.com/) server
- `web`: a [Next.js](https://nextjs.org/) app
- `@repo/eslint-config`: ESLint configurations used throughout the monorepo
- `@repo/jest-presets`: Jest configurations
- `@repo/logger`: isomorphic logger (a small wrapper around console.log)
- `@repo/typescript-config`: tsconfig.json's used throughout the monorepo
- `@repo/ui`: a dummy React UI library (which contains `<CounterButton>` and `<Link>` components)

Each package and app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Jest](https://jestjs.io) test runner for all things JavaScript
- [Prettier](https://prettier.io) for code formatting

```sh
### Descrição

Desenvolva um serviço de autenticação com AWS Cognito que ofereça recursos de autenticação multifator, gerenciamento de usuários e integração com provedores OAuth (Google, Facebook).

### Destaques

Implemente autenticação multifator (MFA) e recuperação de senha segura.
Configure permissões e grupos de usuários para controlar acessos em diferentes níveis.

### Tech Stack

Node.js, Express, AWS Amplify, Cognito, DynamoDB.

Impacto no Portfólio: Demonstra expertise em segurança e integração de autenticação complexa, muito procurada em ambientes corporativos.
```

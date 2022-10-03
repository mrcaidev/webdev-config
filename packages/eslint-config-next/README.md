# @mrcaidev/eslint-config-next

## ✨ Introduction

ESLint configuration for Next.js + TS projects.

Integrated plugins and configs:

- Next
- TypeScript
- Import
- JSX a11y
- React
- React hooks
- Prettier

> How is it different from [official eslint-config-next](https://github.com/vercel/next.js/blob/canary/packages/eslint-config-next/index.js)?
>
> This package is a stricter version of the official configuration. It extends the TypeScript ESLint plugin's recommended configuration and integrates Prettier by default.

## 🚀 Getting Started

```sh
npm i -D eslint @mrcaidev/eslint-config-next     # npm
yarn add -D eslint @mrcaidev/eslint-config-next  # yarn
pnpm add -D eslint @mrcaidev/eslint-config-next  # pnpm
```

`.eslintrc.json`

```json
{
  "extends": "@mrcaidev/next"
}
```

# @mrcaidev/tsconfig

## ✨ Introduction

TypeScript configuration.

- `base.json`: Strictest type checking, ESM support, and other best practices.
- `backend.json`: CommonJS module system, inline source maps, removing comments.
- `frontend.json`: No emit.
- `library.json`: declaration output, inline source maps.

## 🚀 Getting Started

```sh
npm i -D typescript @mrcaidev/tsconfig     # npm
yarn add -D typescript @mrcaidev/tsconfig  # yarn
pnpm add -D typescript @mrcaidev/tsconfig  # pnpm
```

`tsconfig.json`

```json
{
  "extends": "@mrcaidev/tsconfig/base.json"
}
```

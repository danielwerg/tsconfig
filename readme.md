# tsconfig

⚙️ Shared TypeScript config

[ESLint Config](https://github.com/danielwerg/eslint-config)
• [Prettier Config](https://github.com/danielwerg/prettier-config)

## 💾 Install

```sh
yarn add -D @danielwerg/tsconfig
```

```sh
yarn add -D typescript @types/node
```

## 👀 Usage

`tsconfig.json`

```json
{
  "extends": "@danielwerg/tsconfig",
  "compilerOptions": {
    "outDir": "./dist"
  }
}
```
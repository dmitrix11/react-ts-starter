# ViteRC ❤️‍🔥

A modern minimal Vite + React + TypeScript + TailwindCSS template with pre-configured ESLint (with Airbnb JS/React rules), Prettier, Testing with Jest and Git hooks with Husky out of the box 📦

![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![ESLint](https://img.shields.io/badge/eslint-3A33D1?style=for-the-badge&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E)
![Jest](https://img.shields.io/badge/jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Testing Library](https://img.shields.io/badge/testing%20library-E33332?style=for-the-badge&logo=testing-library&logoColor=white)
![Commitlint](https://img.shields.io/badge/commitlint-000000?style=for-the-badge&logo=commitlint&logoColor=white)

![Screenshot](https://i.imgur.com/4dpYsyG.png)

## Features

- ⚡️ [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling
- ⚛️ [React 18](https://reactjs.org/) - A JavaScript library for building user interfaces
- 💎 [TypeScript](https://www.typescriptlang.org/) - Why not?!
- 🔨 [EsLint](https://eslint.org/) - Pluggable JavaScript linter
- 🌀 [Prettier](https://prettier.io) - Opinionated Code Formatter
- 🐺 [Husky](https://github.com/typicode/husky) - Native Git hooks
- ⚙️ [Jest](https://jestjs.io/) - Testing libraries
- ⌨️ Absolute Imports
- 📑 [Commitlint](https://commitlint.js.org/) - Linting your commits based on commit convention

## Why

This template arose out of a need to unite all the above libraries, which were not found in the existing Vite templates. This template has an active contributors that will update everything on this template as needed

## Usage

```bash
npx degit dmitrix11/react-ts-starter my-app

cd my-app

# Required if you want a repository and work with Git hooks
git init

pnpm install

pnpm dev
```

## Available commands

<p>In this project, you can run the following scripts:</p>

| Script        | Description                                                                 |
| ------------- | --------------------------------------------------------------------------- |
| pnpm dev      | Runs the app in the development mode.                                       |
| pnpm build    | Builds the app for production to the `dist` folder.                         |
| pnpm preview  | Builds the app for production to the `dist` folder, and run locally server. |
| pnpm lint     | Runs the Eslint and show code problems                                      |
| pnpm lint:fix | Runs the Eslint and fix the code problems                                   |
| pnpm format   | Runs the Prettier and fix code style                                        |
| pnpm compile  | Runs the TS Compiling                                                       |
| pnpm test     | Run the app tests.                                                          |
| pnpm commit   | Open the CZ CLI to create a message to your commit.                         |

## About the absolute imports

To have correctly functioning (code and tests) of absolute imports, you should add some codes in some files, like:

- jest.config.js
- vite.config.ts
- tsconfig.json

## TODO

- [x] Eslint
- [x] Prettier
- [x] Husky
- [x] Testing Tools
- [x] Absolute imports
- [x] Commit linting

## License

[MIT](https://choosealicense.com/licenses/mit/)

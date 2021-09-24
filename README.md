# Node TDD :honeybee: WeBee®

## Installation dev

Requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies.
```sh
cd skeleton-TDD-node-typescript
# install dependencies
npm install
```

## Prepare Dev.
### husky.

```sh
npm run prepare
npx husky add .husky/pre-commit "npm run test"
```
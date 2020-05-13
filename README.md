[![npm version](https://badge.fury.io/js/base-es6-template.svg)](https://badge.fury.io/js/base-es6-template)
[![npm downloads](https://img.shields.io/npm/dt/base-es6-template.svg?style=flat)](https://www.npmjs.com/package/base-es6-template)

### Installation
```bash
Click On Green Button "Use this template".
```

### Features
- Eslint Config: AirBnB
- Eslint Plugins: Prettier

- Git Hooks: Husky
- Pre Commit: lint-staged

- Commit Lint: commitlint
- Change Log: standard version
```yaml
```

### Fix
```bash
git add .
npm run precommit
git commit -m 'fix: some fix file'
npm run release:patch
```

### Minor change
```bash
git add .
npm run precommit
git commit -m 'feat: some change'
npm run release:minor
```

### Major change
```bash
git add .
npm run precommit
git commit -m 'feat: large changes '
npm run release:major
```

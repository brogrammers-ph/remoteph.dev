# Main website for remoteph.dev

# Contributing

## Commiting
- Use commitizen commit message standards
- All branch names must be prefixed with:
  - `refactor/<name>` - General refactoring of the code
  - `feat/<name>` - New feature/files
  - `fix/<name>` - Bug fixes
  - `chore/<name>` - Anything outside `src` folder e.g. README
  - `hotfix/<name>` - Hotfixes
  - `test/<name>` - Any updates on test files
  - `style/<name>` - Any changes that does not affect the logic or the way the application runs

**Sample Commit**

```
refactor: add new button

Body of the commit if necessary
```

```
fix: wrong spelling

Change "foo" to "bar"
```

## Pull Request
- Do not commit and push directly to `master` branch.
- All changes must go through the PR process.

## Deploy

```
yarn deploy
```

```
npm run deploy
```
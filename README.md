# typescript-example

Minimal TypeScript web app example used to validate Janitor behavior.

## Files

- `src/`: application source files
- `package.json`: scripts and dependencies
- `.github/workflows/janitor.yml`: Janitor GitHub Actions workflow

## Run locally

```bash
npm install
npm run dev
```

## Build locally

```bash
npm run build
```

## Validate Janitor locally

From this directory, run:

```bash
janitor --no-commit
```

## CI behavior

`janitor.yml` runs on pushes and pull requests to `main` and executes Janitor in `no_commit` mode.

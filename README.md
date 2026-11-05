# Market Peak

Marketing automation application with a React frontend, a TypeScript API, and background workers for research, content generation, and distribution.

[![Repository security](https://github.com/nuttallp/market-peak-pilot/actions/workflows/repository-security.yml/badge.svg)](https://github.com/nuttallp/market-peak-pilot/actions/workflows/repository-security.yml)

## Local development

Use a supported Node.js LTS release and the committed npm lockfile.

```sh
npm ci
npm run dev:web
```

Validation:

```sh
npm run lint
npm run build
npm run build:backend
```

Application builds may need separately configured services. Use local test credentials; do not run workers against production as part of a repository check.

## Maintenance and diagnostics

[Actions](https://github.com/nuttallp/market-peak-pilot/actions) shows repository checks; the [Security tab](https://github.com/nuttallp/market-peak-pilot/security) shows available alerts. A workflow badge reports checks, not application uptime. Include the commit, error code, and sanitized reproduction when reporting a failure.

See [CONTRIBUTING.md](CONTRIBUTING.md) for changes and [SECURITY.md](SECURITY.md) for private vulnerability reports.

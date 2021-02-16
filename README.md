# eslint-config

## Prerequisites

- [node](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)
- [lerna](https://github.com/lerna/lerna)

## Development setup

### For existed package

Install packages and develop for packages

```bash
lerna bootstrap
```

### For new package

1. Init package with lerna

```bash
lerna create <name>
```

2. Install third-party package to target packages

```bash
lerna add <third-party package> --scope=<target package> [--dev|--peer]
```

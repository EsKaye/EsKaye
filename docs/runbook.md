# Runbook

## Local Development

### Prerequisites
- Node.js 20+
- pnpm (if `pnpm-lock.yaml` exists)

### Setup
```bash
pnpm install
```

### Commands
- `pnpm lint`: Run lint checks
- `pnpm test`: Run tests
- `pnpm build`: Build the project

## CI/CD
- CI workflows are triggered on pull requests and pushes to `main`.
- Ensure all tests pass before merging.
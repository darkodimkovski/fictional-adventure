# Fictional Adventure

A sample Next.js application used in the Pluralsight course **GitHub Actions: The Big Picture** to demonstrate CI/CD workflows and automated deployment.

## What this repository includes

- A simple Next.js web app (`pages/`, `styles/`, `public/`)
- GitHub Actions workflows (`.github/workflows/`)
- Docker configuration (`Dockerfile`)
- Example workflow files (`demo-files/`)

## Getting started

### 1) Create your own copy

1. Click **Use this template** and choose **Create a new repository**.
2. Select the owner account.
3. Choose a repository name and description.
4. Prefer a **public** repository to use GitHub-hosted runners without consuming private Actions minutes.

### 2) Install dependencies

```bash
npm ci
```

### 3) Run locally

```bash
npm run dev
```

Open http://localhost:3000.

## Available scripts

- `npm run dev` — start local development server
- `npm run build` — create production build
- `npm run start` — run production server
- `npm test` — run lint checks (`next lint`)

## CI/CD workflows

The workflows in `.github/workflows/` cover common automation scenarios:

- Build and test on push/pull request
- Multi-OS validation
- Docker image build and push for `main`
- Introductory hello-world workflow examples

## Learn more

- [Next.js Documentation](https://nextjs.org/docs)
- [GitHub Actions Documentation](https://docs.github.com/actions)
- [SUPPORT.md](./SUPPORT.md) for support and contribution guidance

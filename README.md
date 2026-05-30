# malsa.ch

Personal CV and notes website for Aslam Idrisov.

## Stack

- Astro
- TypeScript
- Markdown-ready content structure

## Commands

```bash
npm install
npm run dev
npm run build
```

## Deployment

Every push to `main` triggers the GitHub Actions workflow in `.github/workflows/deploy.yml`.
GitHub builds the Astro site and publishes the static output to the `deploy` branch.

For a hosting provider with Git deployment but without Node.js, configure:

```text
Repository: git@github.com:fanat98/malsa.ch.git
Branch: deploy
Document root: repository root
```

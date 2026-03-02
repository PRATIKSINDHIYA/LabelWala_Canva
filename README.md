# Labelwala — Label Design & Print (small label-design web app)

Labelwala is a focused label-design and print web app. It includes a compact design editor where users can create, upload, and export label designs, plus an admin/dashboard area for managing projects and orders. The editor is a small, integrated part of the site — the core product is label printing and design workflows.

## Quick Start

1. Install dependencies

```bash
bun install
```

2. Add environment variables (see `.env.example` or `docs/README/12-ENV-REFERENCE.md`)

3. Run development server

```bash
bun dev
```

## What this repository contains

- A label design editor (canvas-based) for creating or uploading label designs
- Dashboard and project management UI for orders and templates
- Integrations for uploads, AI-assisted generation, and payments (config optional)

## Environment variables

Create a `.env` file with the following values as needed:

```env
DATABASE_URL=
AUTH_SECRET=
NEXT_PUBLIC_APP_URL=http://localhost:3000
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
UPLOADTHING_TOKEN=
REPLICATE_API_TOKEN=
STRIPE_SECRET_KEY=
STRIPE_PRICE_ID=
STRIPE_WEBHOOK_SECRET=
GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

## License & third-party code

This repository includes third-party libraries and components; keep their licenses intact. The `LICENSE` file in the project root remains unchanged and must be preserved.

## Need help?

If you want I can:
- Update in-app text to fully say `Labelwala` instead of previous names
- Replace README images and badges with Labelwala-branded assets
- Remove explicit tutorial/course references (I can do that next)

Tell me which of the above you'd like next.
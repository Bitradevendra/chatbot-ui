# chatbot-ui

`chatbot-ui` is a Next.js chat application with Supabase-backed data storage and support for multiple AI providers. It uses Next.js for the UI layer and Supabase for data and local development workflows.

## Install

```bash
npm install
copy .env.local.example .env.local
```

## Use

```bash
npm run dev
```

For local Supabase plus app startup:

```bash
npm run chat
```

## How It Works

- `app/` contains the Next.js routes and pages.
- `components/`, `context/`, and `lib/` contain UI and app logic.
- `db/` and `supabase/` support data access and generated types.

## Useful Scripts

- `npm run dev`
- `npm run chat`
- `npm run build`
- `npm run start`
- `npm run test`

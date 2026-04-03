# chatbot-ui

`chatbot-ui` is a Next.js web application for multi-provider AI chat with Supabase-backed data storage.

## Overview

The project provides a browser-based chat experience, local database workflows, and a modular codebase for UI, prompts, providers, and persistence.

## Project Structure

```text
chatbot-ui/
|-- app/
|-- components/
|-- context/
|-- db/
|-- lib/
|-- supabase/
|-- package.json
`-- README.md
```

## Requirements

- Node.js 18+
- npm
- Supabase CLI for local database workflows

## Installation

```bash
npm install
copy .env.local.example .env.local
```

## Running The Project

Start the Next.js app:

```bash
npm run dev
```

Start the local Supabase stack and app together:

```bash
npm run chat
```

Build for production:

```bash
npm run build
npm run start
```

## How It Works

- `app/` contains routes, layouts, and page entry points.
- `components/` contains reusable chat and settings UI.
- `context/` manages shared client-side state.
- `db/` and `supabase/` support database access, migrations, and generated types.
- `lib/` contains provider integrations, helpers, and business logic.

## Useful Commands

- `npm run dev`
- `npm run chat`
- `npm run build`
- `npm run start`
- `npm run test`

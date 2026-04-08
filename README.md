# Chatbot UI

A polished multi-provider AI workspace for people who want one chat interface without being locked into one model, one vendor, or one workflow.

## Why This Project Exists

`chatbot-ui` is built for people who treat AI like a daily operating system, not a novelty tab. It brings together chat, files, prompts, database-backed history, provider flexibility, and a modern Next.js interface into one place.

## What It Does

- supports multiple model providers from a single chat surface
- stores chat data and app state with Supabase
- includes reusable chat UI, prompt handling, and provider helpers
- supports local development with typed database workflows

## Project Structure

```text
chatbot-ui/
|-- app/                  # Next.js app routes, layouts, and pages
|-- components/           # reusable chat, settings, and interface components
|-- context/              # shared client state
|-- db/                   # database-facing logic
|-- lib/                  # providers, helpers, prompts, and utilities
|-- supabase/             # migrations and generated types
|-- package.json
`-- README.md
```

## Tech Stack

- Next.js
- React
- TypeScript
- Supabase
- Tailwind CSS
- Jest

## Installation

```bash
npm install
copy .env.local.example .env.local
```

## Run Locally

Start the app:

```bash
npm run dev
```

Run the app with the local Supabase workflow:

```bash
npm run chat
```

Build for production:

```bash
npm run build
npm run start
```

## How It Works

- `app/` defines the application shell and route-level behavior.
- `components/` drives the interactive chat experience and settings UX.
- `context/` keeps client-side state synchronized across the interface.
- `db/` and `supabase/` provide persistence, migrations, and typed database access.
- `lib/` holds the provider-specific and product-specific logic that makes the chat experience extensible.

## Who This Is For

This project fits makers, researchers, and power users who want an extensible chat interface they can run, customize, and evolve instead of relying on a fixed hosted product.

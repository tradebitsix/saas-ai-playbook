# SaaS + AI Playbook — Starter Template

Files generated for a minimal Next.js (App Router) + Tailwind + simple shadcn-style components + AI chat API.

## Quick Start

1. Install:
```bash
npm install
```

2. Add your OpenAI key:
Create `.env.local` with:
```
OPENAI_API_KEY=sk-your-key
```

3. Run dev:
```bash
npm run dev
```

Open http://localhost:3000 and visit `/ai`.

Notes:
- This repo uses minimal UI component stubs to avoid external shadcn setup. Replace with `npx shadcn@latest init` + `add` if you prefer real shadcn components.
- The API route expects `OPENAI_API_KEY` in env.
# SWISH — Swipe. Swap. Social.

A responsive Next.js landing page for a Gen Z clothing-swap and social-discovery app.

## Run locally

Requirements: Node.js 18.17+.

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Deploy to Vercel

### Option A: GitHub
1. Create a new GitHub repository named `swish-landing`.
2. Upload the contents of this folder to the repository root (not the enclosing folder).
3. In Vercel, choose **Add New → Project**, import the repository, and deploy.
4. Vercel should detect Next.js automatically. No environment variables are needed for the visual demo.

### Option B: Vercel CLI

```bash
npm install
npx vercel
```

Follow the prompts, then use `npx vercel --prod` for production deployment.

## Important: waitlist form

The current form validates an email and shows a demo success message, but it does **not** save or send the address anywhere. Before public launch, connect it to a form provider or a database/API (for example, Supabase) and add an appropriate privacy notice and consent flow. Do not collect real sign-ups until persistence and privacy handling are implemented.

## Notes

- Photography uses remote Unsplash image URLs and Google Fonts, so an internet connection is needed for those assets.
- The name SWISH and any domains/trademarks have not been checked for availability.

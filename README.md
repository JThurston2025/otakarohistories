🧩 Week 1 — Ship the Paid MVP (4 → 10 Nov)
Day 1 – Tue 4 Nov – Repository & Hosting

 Confirm folder structure (src, functions, etc.)

 Push latest files to GitHub

 Connect repo to Netlify

 Build command npx @11ty/eleventy, publish _site

 Verify public URL builds successfully

Day 2 – Wed 5 Nov – Auth0 Integration

 Create Auth0 API (Identifier = your audience)

 Add Auth0 SPA SDK + auth.js

 Add Login / Logout buttons

 Confirm isAuthenticated() → true locally

Day 3 – Thu 6 Nov – Gated Content Function

 Write get-pro-content.js (serverless)

 Create one pro lesson Markdown file

 Add unlock.js logic (button → fetch content)

 Test fetch works with Auth0 token

Day 4 – Fri 7 Nov – Stripe Checkout

 Create product + price in Stripe

 Generate test Checkout link

 Add pricing.njk with button

 Test payment with Stripe test card

Day 5 – Sat 8 Nov – Stripe → Auth0 Sync

 Build stripe-webhook.js

 Create Auth0 M2M app + Mgmt API env vars

 Add Auth0 Action to inject plan claim

 Deploy and verify webhook sets plan=pro

Day 6 – Sun 9 Nov – End-to-End Test

 Login as free user → 403 on pro page

 Purchase → refresh token → access granted

 Add free lesson for comparison

Day 7 – Mon 10 Nov – Refactor & Docs

 Clean folder structure

 Add README with setup + env vars

 Tag release v0.1 – Paid MVP

🚀 Week 2 — Enhance & Prototype Interactivity (11 → 17 Nov)
Day 8 – Tue 11 Nov – Navigation & Collections

 Add Eleventy collections (free, pro)

 Generate sidebar + next/previous links

 Create 2 lessons (1 free, 1 pro)

Day 9 – Wed 12 Nov – UX & Accessibility

 Add base CSS in src/assets/

 Check headings, contrast, keyboard nav

 Lighthouse a11y score ≥ 90

Day 10 – Thu 13 Nov – Analytics & Privacy

 Add Plausible or GA4 tracking

 Write Privacy policy page

Day 11 – Fri 14 Nov – Error States & Support

 Friendly 401/403 upgrade messages

 Add Stripe Customer Portal link

Day 12 – Sat 15 Nov – Quiz System Foundation

 Choose storage: Supabase / Netlify Postgres / Vercel KV

 Build submit-quiz and get-progress functions

 Test POST + GET with dummy user ID

Day 13 – Sun 16 Nov – Quiz UI Prototype

 Add MCQ form component to one lesson

 POST score → submit-quiz

 Display progress bar via get-progress

Day 14 – Mon 17 Nov – Review & Next Sprint

 Final smoke test (all flows)

 Write retrospective notes

 Plan next phase (quiz polish, CMS, analytics)

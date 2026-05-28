# Integration Hub

Adapter service managing connections to third-party APIs including Zendesk, Stripe, HubSpot, and Slack. Handles escalation workflows, account enrichment, and webhook delivery. Built with TypeScript + Express and uses Bull for async job processing.

**Tech Stack:** Node.js 20, TypeScript 5.3, Express 4.18, Bull, Redis, Axios (HTTP client)

**Run locally:** `npm install && npm run dev` (requires `.env` with API keys for Zendesk, Stripe, HubSpot)
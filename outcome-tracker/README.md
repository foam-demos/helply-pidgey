# Outcome Tracker

Service tracking billable AI outcomes (ticket resolutions, churn signals, upsell flags) for usage-based pricing. Consumes events from message bus, aggregates metrics, and syncs billing data to Stripe. Built with TypeScript + Express.

**Tech Stack:** Node.js 20, TypeScript 5.3, Postgres 15, Bull (event processing), Stripe SDK

**Run locally:** `npm install && npm run db:migrate && npm run dev`
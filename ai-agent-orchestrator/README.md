# AI Agent Orchestrator

Core AI agent service managing conversation routing, LLM API calls, and confidence-based escalation decisions. Built with TypeScript + Express, integrates with OpenAI GPT-4 for response generation and uses Redis for conversation state management.

**Tech Stack:** Node.js 20, TypeScript 5.3, Express 4.18, OpenAI SDK 4.x, Redis 7, Bull (job queue)

**Run locally:** `npm install && npm run dev` (requires `.env` with `OPENAI_API_KEY` and `REDIS_URL`)
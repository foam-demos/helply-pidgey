# Knowledge Bridge

Knowledge base analysis pipeline that ingests support tickets, identifies documentation gaps, and generates embeddings for RAG-based retrieval. Uses Postgres with pgvector for vector storage and Langchain for embedding generation.

**Tech Stack:** Node.js 20, TypeScript 5.3, Postgres 15 + pgvector, Langchain, OpenAI embeddings, Bull (job scheduling)

**Run locally:** `npm install && npm run db:migrate && npm run dev` (requires Postgres with pgvector extension)
# Armando Villafranca

**AI Solutions Engineer — automation, integrations and internal tools.**
Remote from San Pedro Sula, Honduras (UTC-6, full US Central overlap).

I map a manual business process end to end, then build and ship the system that
replaces it — and I stay with it afterwards. Most of my work is internal tools and
automation for teams with no technical staff of their own: requirements taken face
to face, built on Cloudflare Workers, n8n and the Anthropic API, then documented and
handed over so they run it without me. Self-taught, and all of it is in production.

## Selected work

| | |
|---|---|
| **[LCM CRM](https://lacasadelmotor.com)** | CRM, inventory, clients and finances for an engine importer selling into Honduras and Guatemala. A pnpm monorepo deploying three Cloudflare Workers across staging and production, admin gated behind Cloudflare Access with TOTP 2FA. Scheduled FX sync from the Banco Central de Honduras feed, PDF generation, validated CSV imports. **Staff have run it daily for months with no developer involved.** |
| **[MediHealth](https://medihealthcrm.com)** | Clinical booking and records platform with separate patient, doctor and admin applications: multi-role JWT auth with Google OAuth and Twilio Verify, medical history management, in-app chat, two-level rescheduling approvals. **One of two contributors on a ~600-commit codebase**, working through pull requests and review. Migrated from Express/MongoDB to Workers + Hono + Drizzle without losing the live product. |
| **[Bountyhunter](https://bountyhuntr.com)** | AI job-application copilot, ~25,000 lines: resume parsing, fit scoring, document generation and a Manifest V3 Chrome extension that fills application forms. Rebuilt the LLM layer into a provider registry with configurable routing across 13 call sites, with per-provider attribution logging, timeouts and a health probe. 68 passing tests. Benchmarking overruled my own assumption about which provider to prefer. |
| **[SlicerSmthng](https://github.com/mvillafranca98/slicersmthng)** | Music practice workstation: separates a track into isolated instrument stems and mixes them live in the browser — per-stem mute/solo, pitch-neutral tempo, bar looping, beat-aligned metronome. ~3,300 lines of Python across 11 backend modules serving Demucs (PyTorch) and UVR-MDX-NET (ONNX) on a pluggable serverless-GPU backend. *Inference and integration, not model training.* |
| **Lead intake automation** | Production n8n workflow: a Supabase webhook fires, Claude classifies and drafts the reply, a Code node parses the response defensively with a safe fallback, conditional routing writes back to Postgres and notifies internally. Built after a silent parsing failure was dropping records with no error — the fallback is the point. |

## Also in this profile

[**HRPLAT**](https://github.com/mvillafranca98/HRPLAT) — Honduran labour-law severance and prestaciones calculator ·
[**desc-vlm2**](https://github.com/mvillafranca98/desc-vlm2) — real-time video summarisation with VLM captions, face recognition and semantic scene search ·
[**OC-agent**](https://github.com/mvillafranca98/OC-agent) — research-only agentic lead-scoring workspace ·
[**E2E-test**](https://github.com/mvillafranca98/E2E-test) — Playwright suite with state seeding and web-first assertions ·
[**camstream**](https://github.com/mvillafranca98/camstream) — ffmpeg to FastVLM live captioning pipeline

## Tech

**Automation & AI** n8n · Zapier · GoHighLevel · Anthropic (Claude) and OpenAI APIs · structured output parsing · agentic workflows · Claude Code · Cursor
**Languages** TypeScript · JavaScript · Python
**Backend** Hono · Node.js · Flask · FastAPI · REST APIs, webhooks, OAuth
**Data** PostgreSQL / Supabase with row-level security · Cloudflare D1 · MongoDB · Drizzle ORM · SQL
**Frontend** React 18/19 · Next.js · Tailwind
**Infra & quality** Cloudflare Workers / R2 / Access · Docker · GitHub Actions · Sentry · Playwright · serverless GPU (Modal, Replicate)

## Certifications

Claude Code in Action — Anthropic (2026) · n8n: No Code AI Agent Builder — Simplilearn (2026) · Python Data Structures — University of Michigan (2026) · HIPAA Workforce Proficiency — Compliancy Group (2025)

## Contact

[macawly.dev](https://macawly.dev) · [LinkedIn](https://linkedin.com/in/armando-villafranca) · mvillafranca98@gmail.com

*Available for remote contract work. Spanish (native), English (fluent).*

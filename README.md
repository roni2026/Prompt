# Prompt

Planning notes and troubleshooting logs for the BazarBD marketplace project — not application code.

## What's in here

- `PROMPT` — a phased feature roadmap written out as a build spec: authentication & security, user profiles & reputation, and the phases that follow. Used as a reference/prompt when planning out marketplace features in order.
- `promlems in sql marketplace` — a running log of SQL errors hit while setting up the Supabase schema (missing types, `DO $$ BEGIN` syntax issues, missing functions in RLS policies, etc.), kept as a reference so the same mistakes aren't repeated on the next schema pass.

This repo is a scratchpad, not a deployable project — see [`marketplace`](https://github.com/roni2026/marketplace) for the actual application these notes fed into.

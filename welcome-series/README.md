# Welcome Series — Agentic Onboarding Automation

An agent-based system that automates subscriber welcome and onboarding 
sequences, with tool-calling and webhook-driven triggers.

## What it does
- Runs an autonomous agent that processes due subscribers on a schedule
- Uses a defined toolset for agent operations, rather than hardcoded logic
- Handles signup and resend events via webhooks
- Persists subscriber/sequence state to a database

## Tech stack
Python

## Architecture
- `agent.py` — core agent logic
- `tools.py` — toolset the agent can call
- `runner.py` — processes due subscribers
- `webhook.py` — signup/resend event handling
- `db.py` — persistence layer

## Note
This repo showcases the project's structure. Full source is private.

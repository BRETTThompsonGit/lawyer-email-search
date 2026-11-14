# CLAUDE.md

This file provides shared project guidance to Claude Code (claude.ai/code) and Codex when working in this repository.

## Shared Project Instructions and Memory

- `CLAUDE.md` is the authoritative project instruction and memory file for both Claude Code and Codex.
- Read this file when starting work. Record durable project decisions, conventions, and requested memory updates here.
- Do not create `AGENTS.md`, `AGENTS.override.md`, or a separate project memory file unless the user explicitly requests one.
- Codex can load this file through `project_doc_fallback_filenames = ["CLAUDE.md"]` in its local `~/.codex/config.toml`. Preserve this setup when using Codex on another machine.

---

## Tech Stack

**Status:** To be determined
- **Language/Framework:** [Fill in as development begins]
- **AI boundary:** AI may assist software development; the MVP must use non-AI processing and search, with no AI interpretation or restatement of email evidence.
- **Database:** [If applicable]
- **Deployment:** [If applicable]

---

## Confirmed Project Direction

- The user is building a tool for expert witnesses to search large Outlook email archives and locate relevant source material across conversations spanning years.
- The early MVP should prove archive import, useful search beyond basic Outlook search, conversation threading, readable email presentation, and relationships among messages, correspondents, case roles, and topics of interest.
- Mac and potentially Windows are target environments; platform priority, archive formats and volumes, database, search engine, and implementation approach remain undecided.
- The user wants to explore background processing that can prepare results for review the next day. This is a possibility to investigate, not an agreed performance requirement.
- Long-term direction: a hosted application with archive uploads, processing, search, access controls, and data protection. Production cloud architecture is outside the immediate MVP discussion.
- Later feature candidates: flagging searches and their results; flagging documents and manually associating them with topics, targets, and reports; bug reporting; estimates of time saved; actual review-time tracking for billing; and optional AI analysis in a future phase.
- The meaning of "consolidate and explain" must remain consistent with the no-AI MVP boundary. How to clean presentation without changing source wording, how roles/topics are assigned, and whether attachment contents are searchable still need clarification.
- The original user brief is preserved in `docs/2026-11-14-original-project-brief.txt`. It is a historical scope reference, not an approved design. Keep ongoing project memory in this `CLAUDE.md` file.
- Current phase: brainstorming, MVP scope definition, and market evaluation. No product implementation or technical design has been approved; the decision to build versus adopt an existing product remains open.
- The initial scope baseline is in `docs/2026-11-14-mvp-scope.md`. Candidate search methods and evidence-preservation behavior in that document are proposals, not approved implementation choices.
- Product research and dated vendor pricing are in `docs/2026-11-14-product-research.md`. The recommended first comparisons are MailDex, Intella, and Nextpoint; this is an evaluation shortlist, not a purchase decision.
- A copyable stakeholder email is in `docs/2026-11-14-product-evaluation-email.md`. It has not been sent. No trial account, purchase, or external archive upload has been authorized or performed.

---

## Development Commands

### Setup
```bash
# [Fill in: install dependencies]
# Example: npm install, pip install -r requirements.txt, etc.
```

### Development
```bash
# [Fill in: run dev server]
# Example: npm run dev, python manage.py runserver, etc.
```

### Testing
```bash
# [Fill in: run all tests]
# [Fill in: run single test]
# Example: npm test, pytest tests/test_file.py, etc.
```

### Linting & Formatting
```bash
# [Fill in: run linter]
# [Fill in: format code]
# Example: npm run lint, black ., etc.
```

### Build for Production
```bash
# [Fill in: build command]
# Example: npm run build, python setup.py build, etc.
```

---

## Project Architecture

### High-Level Overview

[Fill in: Describe the main components and how they interact]

**Example structure to replace:**
- **Backend/API:** Handles email search, storage, and retrieval
- **Frontend:** User interface for searching and managing emails
- **Data Layer:** [Describe database schema or data flow]
- **Integration Layer:** Claude/GPT API calls for [specific features]

### Key Design Decisions

[Fill in as development progresses. Examples:]
- Why this tech stack was chosen
- How Claude and GPT integrate (what tasks each handles)
- Data flow and processing pipeline
- Authentication/authorization approach

### Critical File Locations

[Fill in once structure is established. Examples:]
- `src/api/` — API routes and handlers
- `src/ui/` — Frontend components
- `src/models/` — Data models/schema
- `src/services/` — Business logic for email search, LLM calls
- `src/config/` — Configuration and environment setup

---

## Development Workflow

### When Starting a Feature
1. Clarify requirements (what problem does this solve?)
2. Design the data flow (what data moves where?)
3. Identify integration points (Claude vs. GPT vs. internal logic)
4. Implement, test, verify

### Claude vs. GPT Integration
- **Primary documentation:** Markdown in this repo (for Claude)
- **GPT references:** Secondary; Claude-first decisions are authoritative
- **LLM task division:** Claude and Codex may help build the software. The MVP itself must not call AI models to interpret, summarize, or restate case emails.

### Testing Strategy
[Fill in your testing approach:]
- Unit tests for [components]
- Integration tests for [systems]
- Manual QA steps for [features]

---

## Common Patterns & Conventions

[Fill in as patterns emerge:]
- Naming conventions (e.g., files, functions, variables)
- Error handling approach
- Logging and debugging
- Code organization principles

---

## Dependencies & External Services

[Fill in as you add dependencies:]
- Key npm packages / Python libraries
- Claude API (models, rate limits, authentication)
- OpenAI API (models, authentication)
- [Other third-party services]

---

## Debugging & Troubleshooting

[Fill in common issues you encounter:]

**Issue:** [Example problem]
- **Cause:** [What causes it]
- **Solution:** [How to fix]

---

## Deployment & Release

[Fill in as you set up deployment:]
- Staging environment setup
- Production deployment process
- Environment variables checklist
- Rollback procedures (if applicable)

---

## Notes for Future Sessions

- The repository currently contains documentation and empty `src/` and `tests/` placeholders. There are no application dependencies or runnable tests.
- Continue the requested brainstorming discussion before choosing a technical approach. A concrete expert-witness question that ordinary Outlook search handles poorly is still needed to define a useful acceptance scenario.
- Verify the actual input archive format and scale. PST is the likely Outlook export format; direct OST support has not been agreed.
- Preserve the no-AI MVP boundary when proposing topic organization, relationship exploration, or readable conversations. Local model inference is still AI and does not meet this boundary.
- Product capabilities and prices are a research snapshot dated November 14, 2026. Recheck them before purchasing or making a final product decision.
- Keep original briefs and dated research as reference artifacts under `docs/`; update ongoing project decisions and instructions here rather than creating another memory file.

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

---

## Tech Stack

**Status:** To be determined
- **Language/Framework:** [Fill in as development begins]
- **Primary API/LLM Integration:** Claude, OpenAI GPT (Claude is primary in markdown/config)
- **Database:** [If applicable]
- **Deployment:** [If applicable]

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
- **LLM task division:** [Define as you build — e.g., "Claude handles text analysis, GPT handles summarization"]

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

## Notes for Future Claude Sessions

[Ongoing guidance to be added:]
- Current blockers or known issues
- Architectural debt or refactoring candidates
- Recent major changes or decisions
- Links to important issues/PRs

# Candidate Intake & ATS Application Orchestration

## Problem
Manual candidate processing from external campaigns leads to:
- Duplicate candidates
- Missing or inconsistent data
- Delayed application creation
- Poor visibility into failures

---

## Solution
This automation orchestrates the full candidate lifecycle:

- Receives candidate data from an external trigger
- Validates required fields and backfills missing data
- Uses AI to normalize and structure candidate information
- Checks if the candidate already exists
- Creates or updates the candidate record in the ATS
- Checks for existing applications to prevent duplicates
- Creates and updates job applications conditionally
- Sends stakeholder notifications
- Logs all failures for auditing and retry

---

## Key Techniques
- Conditional branching (idempotent design)
- Multi-step API orchestration
- AI structured output parsing
- Database-backed error tracking
- Partial-failure tolerance with safe retries

---

## Screenshots
- `overview.png` – full end-to-end workflow
- `branching-and-errors.png` – candidate/application existence checks and error handling



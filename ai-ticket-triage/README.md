# AI Ticket Triage & First-Response Compliance

## Problem
Support teams struggle with:
- Manual ticket categorization
- Inconsistent prioritization
- Lack of visibility into first-response SLA compliance

---

## Solution
This automation performs intelligent ticket triage:

- Fetches ticket and reply history
- Uses AI to classify ticket type and priority
- Parses AI output into a strict structured format
- Determines if first-response SLA is met
- Updates ticket fields automatically
- Logs classification results for auditing

---

## Key Techniques
- AI agents with deterministic prompts
- Structured output parsing
- Business-rule validation using IF/Switch
- Automated SLA compliance checks
- Safe fallback paths for missing data

---

## Screenshots
- `overview.png` – ticket ingestion to update
- `ai-and-routing.png` – AI classification and decision routing


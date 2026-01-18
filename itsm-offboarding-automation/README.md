# ITSM Offboarding Automation with Escalation

## Problem
Manual offboarding leads to:
- Delayed access removal
- Security risk
- Inconsistent audit trails
- Missed follow-ups on failures

---

## Solution
This automation handles offboarding end-to-end:

- Detects offboarding requests from ITSM tickets
- Validates required user identity fields
- Executes deprovision actions via API
- Updates ticket with actions taken
- Maintains an audit trail
- Escalates failures automatically

---

## Key Techniques
- Input validation and guardrails
- API session management
- Error detection and escalation
- Automated audit logging
- Stakeholder notifications

---

## Screenshots
- `overview.png` – complete offboarding workflow
- `validation-and-escalation.png` – validation checks and failure escalation


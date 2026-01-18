# Infrastructure Monitoring & Severity Alerting

## Problem
Service outages are often detected late,
leading to extended downtime and reactive firefighting.

---

## Solution
This automation provides proactive monitoring:

- Runs scheduled health checks
- Tests critical mail services (SMTP / IMAP)
- Calculates service status and severity
- Routes incidents based on failure type
- Sends targeted alerts to operations teams

---

## Key Techniques
- Scheduled execution
- Command execution for service checks
- Dynamic severity calculation
- Switch-based alert routing
- Clear incident signaling

---

## Screenshots
- `overview.png` – full monitoring pipeline
- `severity-routing.png` – failure classification and alert routing

# Task 05 — Penetration Test Report and Retest

## Project Overview

This project documents a security assessment of the locally hosted OWASP Juice Shop application. It builds on the findings identified during the previous OWASP Web Testing task.

The assessment focuses on documenting confirmed security findings, recommending appropriate remediation measures, and defining retest procedures to evaluate whether the issues have been resolved.

## Scope

- **Target:** OWASP Juice Shop
- **Environment:** Local Docker-based lab
- **Application URL:** `http://127.0.0.1:3000`
- **Testing type:** Authorized web application security assessment
- **Scope restriction:** Testing is limited to the local lab environment.

## Confirmed Findings from the Previous Assessment

| ID | Finding | Initial Status |
|---|---|---|
| WEB-01 | Database error disclosure through product search | Confirmed |
| WEB-02 | Previously issued JWT accepted after logout | Confirmed |

## Project Contents

- `Penetration-Test-Report.md` — Executive summary, scope, methodology, and technical findings.
- `Remediation-Plan.md` — Recommended fixes and mitigation strategies.
- `Retest-Results.md` — Retest procedures and final verification status.
- `Evidence/` — Supporting screenshots from the authorized lab.

## Assessment Disclaimer

This project was conducted exclusively against a locally hosted OWASP Juice Shop instance for educational purposes. No public or third-party systems were tested.

A remediation recommendation does not indicate that a vulnerability has been fixed. Findings will only be marked as resolved after successful verification.

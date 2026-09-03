# Template Status & Verification

**Classification:** Configurable n8n template asset — not a verified production deployment.

This repository proves a version-controlled workflow structure and documented intended use. It does not by itself prove a current configured run, production reliability, SLA, ROI, or client outcome.

## Verification gate
1. Parse/import the JSON into a clean current n8n instance.
2. Inspect connections, expressions, IF/Switch branches, and Code nodes.
3. Replace every placeholder credential, URL, ID, model, webhook, mailbox, label, or resource reference.
4. Confirm current provider/model API requirements.
5. Run representative positive/neutral/negative sentiment cases and a malformed-model-output/provider-failure case.
6. Confirm the generated response is bounded and no unsafe automatic send occurs without the intended approval/routing rule.
7. Record the configured test date/result.

## Security
Never commit API keys, OAuth secrets, mailbox credentials, private webhooks, customer PII, or production email content. Use synthetic messages and fresh test credentials.

## Change record
- **2026-09-03:** Added repository verification/security/status control. No workflow-logic change or runtime pass is implied.
